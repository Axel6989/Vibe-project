# Journal

Decisions and why. Append-only, newest entries first. A decision gets a stable name after the ⚖️ sign and three fields: decided, rejected, owner's words. Thinking that is not a decision goes in as a plain entry with a date and the author.

## 2026-09-13 20:00 · codex · ⚖️ pollinations-image-source · Pollinations AI for the five historical images

**Decided.** The five images will be requested one at a time from the user-specified, keyless Pollinations endpoint, requesting 768×1152 JPEG files in `images/`. Each English prompt fixes the same street-corner coffeehouse viewpoint, photorealism, golden-hour lighting, vertical composition, and no people in close-up; the period details vary by era. The service returned optimized 627×940 JPEGs with the same 2:3 ratio.

**Rejected.** Stock-image search and image services requiring an account or API key. They cannot guarantee one consistent fictional location and conflict with the stated no-key constraint.

**Owner's words.** "Картинки бери бесплатно и без ключа, по одной за раз: GET https://image.pollinations.ai/prompt/<описание на английском в URL-кодировке>?width=768&height=1152&nologo=true&seed=<номер>&enhance=true отдаёт JPEG; сохрани в images/."

## [YYYY-MM-DD HH:MM] · [agent or person] · ⚖️ adopt-spec-driven-company · The truth lives in docs, agents execute, status is visible

**Decided.** This project runs as a Spec-Driven Company. Rules live in `AGENTS.md`. The truth lives in `docs/`: this journal for decisions, `README.md` for the one-page summary, one file per zone for how things work. Agents work in branches, write the spec before the code, run the check before every commit, and stop at money, keys, personal data and anything published outside.

**Rejected.** Keeping the truth in chat history and in people's heads. It does not survive a new agent session or a new person.

**Owner's words.** "Установи Spec-Driven Company в этой папке... и дальше работай по нему."
