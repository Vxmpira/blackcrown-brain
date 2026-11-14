# TikTok-Engine-Live

Auto refreshed from Make, read only. Secrets scrubbed.

TikTok Engine live config (scenario 5822164, read 2026-11-14). The text under each label is what the engine uses today; headers, keys and connections are never shown.

[module 3 util:SetVariables, variable product]
{{switch(2.roll; 0; "KORVUS"; 1; "CROWN"; 2; "ECLIPSE-X"; 3; "BLACKCROWN")}}

[module 3 util:SetVariables, variable brand_id]
{{if(2.roll = 0; "4c2723d4-ad2b-4b52-bd20-f5b3ee65641b"; "c5d8f6df-bb5e-40f8-a064-4e1462d76bf5")}}

[module 3 util:SetVariables, variable dest]
{{switch(2.roll; 0; "korvus.industries"; 1; "blackcrown-intelligence.com"; 2; "discord.gg/eclipse-x"; 3; "blackcrownvxj.com")}}

[module 3 util:SetVariables, variable color]
{{switch(2.roll; 0; 16723592; 1; 5972406; 2; 5793266; 3; 10162462)}}

[module 3 util:SetVariables, variable cta]
{{switch(2.roll; 0; "Create your free Korvus account at korvus.industries"; 1; "Start a free chat at blackcrown-intelligence.com"; 2; "Join Eclipse-X free at discord.gg/eclipse-x"; 3; "See the house at blackcrownvxj.com")}}

[module 3 util:SetVariables, variable why]
{{switch(2.roll; 0; "Targets beginner futures traders drowning in tabs and trading without understanding why price moves. Korvus puts the whole picture on one screen with a directional read. Cold traffic to the homepage for a free account."; 1; "Targets people who do not trust AI tools with their work. Traffic to Crown for a free chat, no card."; 2; "Targets operators building alone in trading, AI, and ecommerce. Free foot in the door to the Eclipse-X Discord at discord.gg/eclipse-x, the top of the funnel toward the paid products."; 3; "House brand awareness for the whole family. Traffic to blackcrownvxj.com.")}}

[module 3 util:SetVariables, variable slides]
{{3 + floor(random*4)}}

[module 3 util:SetVariables, variable brief]
{{switch(2.roll; 0; "KORVUS at korvus.industries. A market intelligence terminal built so index futures traders, especially beginners, get the whole picture on one screen: a scored news feed, the futures board, cross index SMT divergence, and session and macro context. Korvus does not trade headlines. It uses the news to explain what is moving the market and assembles everything into a directional read so the trader walks in prepared and understands why price is moving. It is assistance for those who learn how to wield it. It informs decisions, it never predicts price or promises profit. CTA: create a free account at korvus.industries."; 1; "CROWN, also called BlackCrown Intelligence, at blackcrown-intelligence.com. A private AI workspace. Your chats are nobody's training data, never sold, never trained on. Four private rooms. Crowned tier at 49.99 a month carrying $100 of room credit, metered live like a prepaid balance. Free tier with no card so skeptics judge the output themselves. Hook angle: ownership, your context stays yours. Motto: Intelligence, Crowned. CTA: start a free chat at blackcrown-intelligence.com."; 2; "ECLIPSE-X at discord.gg/eclipse-x. The free Discord community for independent operators in trading, AI, and ecommerce. Hook angle: building alone got slow and lonely, this is a room of people a step ahead. No gurus, no courses, no upsell, just the room. Open invite, free to join. CTA: join Eclipse-X at discord.gg/eclipse-x."; 3; "BLACKCROWN, the parent house brand, at blackcrownvxj.com. One house, three edges for independent operators: the Korvus market terminal, a private AI workspace, and the Eclipse-X community. Built by an operator, edge not hype, your data stays yours. Motto: a crown is not handed down, it is built. Do not describe the AI workspace in any detail. CTA: see the house at blackcrownvxj.com.")}}

[module 8 http:ActionSendData, request body sent to api.anthropic.com]
{"model":"claude-sonnet-4-6","max_tokens":2000,"messages":[{"role":"user","content":"You write TikTok photo carousel posts for the BlackCrown brand family. Voice: anti guru, honest, specific, confident, plain and sharp, short sentences, never hype, never promised outcomes, never financial or trading advice, no fabricated results or testimonials, no em dashes, no emojis, and never use double quote characters, use apostrophes instead. Today's product and its single destination: {{3.brief}} Every post drives to that one destination only. Never mention the other BlackCrown products. Sell by fit, not by push. Open on the real problem the viewer already feels, in plain words, then show how this product fits that need, so a stranger who has never heard of the brand understands what it is and why it matters by slide two. Write for TikTok search, because people search TikTok like Google. Lead the slide 1 headline and the caption first line with the plain keywords this audience actually types, for example how traders read the news, day trading news feed, AI that remembers your work, or private AI chat, so the post can surface in search and not only in the feed, and keep those keywords natural and human, never stuffed. Produce one fresh photo carousel of exactly {{3.slides}} slides that tells one story in swipe order, and vary the hook angle, structure, vocabulary, and headline every time so a repeat viewer never sees the same post twice. Slide 1 is the scroll stopper with one bold capital letter headline and one striking focal image. Each middle slide shows one concrete beat of the story or the mechanism with at most one short capital letter line. The last slide is the CTA card with the destination large and a short push line. All slides share one visual world: dark premium near black aesthetic, royal accents, one focal point per slide, all text kept toward the center of the frame, the far right edge and the bottom 15 percent of every frame left empty, the destination written as small text above the bottom fifth on every slide. Output exactly {{3.slides}} image prompts, each a single line under 480 characters, one per slide in swipe order, then the TikTok caption as the final block. The final block must begin with the word CAPTIONBLOCK on its own line, followed by the caption: a keyword led scroll stopping first line, then two or three short lines that name the need and earn the click, then a line saying Link in bio together with the destination, then exactly 4 hashtags that mix one broad high traffic tag with specific niche tags this audience searches. Separate every block with a line containing only ###. No numbering labels, no other text, and never end the output with ###."}]}

[module 9 util:SetVariables, variable caption_disc]
{{replace(trim(replace(trim(last(split(8.data.content[1].text; "###"))); "CAPTIONBLOCK"; "")); newline; "\n")}}

[module 11 http:ActionSendData, request body sent to www.trybloom.ai]
{"brandSessionId":"{{3.brand_id}}","prompt":"{{replace(trim(10.value); newline; " ")}}","aspectRatio":"9:16","imageSize":"2K","model":"pro"}

[module 16 discord:MakeAPICall, body]
{"content":"**{{3.product}} | {{3.slides}} SLIDE CAROUSEL | AUTO DROP {{formatDate(now; "MM-DD-YYYY")}}** | review queue, not posted","embeds":[{"title":"{{3.product}} carousel, swipe order below","description":"**CAPTION**\n{{9.caption_disc}}","color":{{3.color}},"fields":[{"name":"Why this post","value":"{{3.why}}"},{"name":"CTA","value":"{{3.cta}}"},{"name":"Destination","value":"{{3.dest}}"},{"name":"Format","value":"Photo carousel, {{3.slides}} slides, post in the order shown"}],"footer":{"text":"BlackCrown Content Engine | automated | images by Bloom"}},{{15.text}}]}
