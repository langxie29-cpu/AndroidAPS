# AndroidAPS Fork · Agent Rules

This codebase is related to automated insulin delivery; medical and patient safety take precedence. Its upstream documentation and tested device configuration govern development.

1. Never modify dosing, glucose targets, insulin-on-board, safety limits, pump communication, alarms or control algorithms based on guesswork, model suggestions, or unrelated lab experiments.
2. Do not recommend deploying untested modified builds to a live medical device. Keep proposed code changes separate from user-care decisions, require validated tests and qualified clinical oversight for treatment decisions.
3. Never commit real patient data, CGM/pump telemetry, medical records, credentials or device-unique identifiers.
4. Follow upstream project compliance, test, license and contribution constraints. Do not assert medical reliability from passing unit tests alone.
5. This fork is not a general-purpose Σ inventory or engineering repository.

## Universal agent contract
- Obey the user's explicit scope and the current repository's readme, tests, and more-specific documentation. Preserve historical evidence. No destructive rewrites, silent renames, force-push or unverified success claims.
- Σ (U+03A3) is the lab name. The private Obsidian Vault `langxie29-cpu/obsidiandatabase` under `Σ/` holds actual assets, inventory, payments, and repair records; this repository holds only its own source work.
- Never commit raw receipts, private account data, access tokens, addresses, or personal medical information. Public repositories require particular care.
- Distinguish observed facts, user reports, drafts and guesses. Never invent purchase prices, physical measurements, passing tests, or completed deployments.
- Do not generate images without the explicit user instruction “生成图片”.
- Report exactly which files changed, which checks ran, and what remains unknown.
