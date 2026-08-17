# KukuPaste

**Copy several texts. Paste them in order.**

KukuPaste remembers everything you copy with <kbd>Ctrl</kbd>+<kbd>C</kbd> and pastes the
next one with <kbd>Ctrl</kbd>+<kbd>Q</kbd>. Collect the pieces once, then place them one by
one wherever they belong — prompts, replies, notes, review steps, repeated messages.

A small Windows app that lives in the tray. Local-first: nothing leaves the machine.

**[→ Download and full description](https://praviloalex.github.io/kukupaste-site/)**

## How it works

| | |
|---|---|
| <kbd>Ctrl</kbd>+<kbd>C</kbd> | Copy as usual. Each text joins the stack, in order. |
| <kbd>Ctrl</kbd>+<kbd>Q</kbd> | Paste the next one into whatever window you are in. |
| Hold <kbd>Ctrl</kbd>+<kbd>Q</kbd> | Open the stack and pick a specific text. |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Q</kbd> | Paste the whole stack at once. |

A counter appears next to the tray while you paste, so you can see what is left without
leaving the window you are working in. Pasted texts move to a local history and can be
sent back to the stack.

Sequences you repeat can be saved as a library and reloaded with one click.

## Download

[**KukuPaste 1.1.0 for Windows**](https://praviloalex.github.io/kukupaste-site/downloads/KukuPaste_1.1.0_x64-setup.exe)
· 4 MB · Windows 10 and 11

The build is not signed with a certificate yet, so Windows SmartScreen may warn on first
run: choose *More info → Run anyway*. The SHA-256 checksum is published on the
[product page](https://praviloalex.github.io/kukupaste-site/#download) so the file can be
verified. Once installed, the app updates itself: new versions are offered from the tray
and install with one click.

## Free and Pro

| | Free | Pro — one-time $39.99 |
|---|---|---|
| Texts in the stack | 5 | 20 |
| History | 50 | 5000 |
| Libraries | 3 | 100 |
| Export and import libraries | — | yes |

[Buy Pro](https://kukuluku.lemonsqueezy.com/checkout/buy/588de431-dbca-4648-93d8-4d403c2dc849)

## Privacy

Everything stays on the device. There is no account, no cloud, and no telemetry — the app
makes exactly one kind of network request, checking whether a newer version exists.

The stored state is encrypted with Windows DPAPI. Password managers, banking apps and
private browser windows are excluded from capture by default, and text that looks like a
key, token or card number is not collected at all. Window titles are never kept.

## Feedback

Something broken or missing: [@kukuluku_bot](https://t.me/kukuluku_bot)

---

<sub>This repository hosts the product page published at
[praviloalex.github.io/kukupaste-site](https://praviloalex.github.io/kukupaste-site/) —
`index.html`, the installer under `downloads/`, and `latest.json`, which is the manifest
the installed app reads to find new versions.</sub>
