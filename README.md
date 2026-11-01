# dm-reply-x

A Claude skill that reads a full X DM thread, sums up where you left off, and drafts one next message in your voice.

It never sends anything. You read, edit and click send yourself.

## What it does

< Reads the whole thread, in your browser or from a thread you paste
< Sums up where you left off and what the other person expects
< Drafts one short next message in your voice

## Install (Claude Code)

1. Create the folder `~/.claude/skills/dm-reply-x/` (on Windows: `%USERPROFILE%\.claude\skills\dm-reply-x\`)
2. Copy `SKILL.md` from this repo into it
3. Write a `voice.md`: 3 to 5 messages you really wrote, plus the words you never use. Keep it next to where you work, or paste it when the skill asks

For automatic reading, connect Claude to your browser (Claude in Chrome) and stay logged in to X. Without it, paste the thread and the skill does the rest.

## Use

Say "dm reply" and give a name or a handle. The skill sorts the thread, reads it from the first message, sums it up in 2 lines and shows you one draft.

You always get this line at the end: "Draft to validate, nothing is sent".

## Good to know

< Opening a thread marks it as read on X
< Warm contacts get a reconnect message first, with no pitch, no link and no price
< Cold contacts get a short public reply idea, not a DM
< Other AI tools can follow the same steps if you paste the text, but the skill format is made for Claude

## Made by @zkjays

I build small AI systems that keep my voice, and I share how I build them.

If you want a free, personal look at where a small system like this could fit your week, start here:
https://www.bonzai.pro/jz/lp/12539/get-a-free-personal-look-at-your-ai-setup
