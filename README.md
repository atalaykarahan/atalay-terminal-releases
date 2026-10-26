<p align="center">
  <img src="assets/icon.png" width="168" alt="Atalay's Terminal">
</p>

<h1 align="center">Atalay's Terminal</h1>

<p align="center">
  A HUD for your Claude Code sessions on the Mac: every chat on a live orbit map, terminals as flying cars, friends and messages.
</p>

<p align="center">
  <a href="https://github.com/atalaykarahan/atalay-terminal-releases/releases/latest/download/Atalays-Terminal.dmg"><b>⬇&nbsp; Download for macOS</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/atalaykarahan/atalay-terminal-releases/releases">All versions</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/atalaykarahan/atalay-terminal">Source code</a>
</p>

<p align="center"><sub>macOS 13 or later · Apple Silicon and Intel · works with Claude Code</sub></p>

<p align="center">
  <img src="assets/preview.gif" width="900" alt="Claude Code sessions orbiting live, with their subagents, tool calls, files, web research and spend">
</p>

<table>
  <tr>
    <td width="50%"><img src="assets/dashboard.jpg" alt="The dashboard"></td>
    <td width="50%"><img src="assets/chat.jpg" alt="A Claude chat in its own window"></td>
  </tr>
  <tr>
    <td><b>Every session on one screen.</b> Chats orbit while they work; subagents, tool calls, files, web research and spend update live, and the ones that need you glow red.</td>
    <td><b>Each chat in its own window</b>, running in the background: close it or quit the app and Claude keeps working.</td>
  </tr>
  <tr>
    <td><img src="assets/profile.jpg" alt="Your profile with level and rank"></td>
    <td><img src="assets/friend.jpg" alt="A friend's card with their last 7 days"></td>
  </tr>
  <tr>
    <td><b>Levels and ranks</b> for the time you actively work, from Academy Student up to Kage.</td>
    <td><b>Friends:</b> their level, and how many hours they worked each day.</td>
  </tr>
</table>

---

## Install

1. Download **Atalays-Terminal.dmg** (link above) and open it.
2. Drag **Atalay's Terminal** onto **Applications**.
3. Open it from Applications.

The app isn't notarized by Apple yet, so the first time macOS says it can't verify it. Allow it once:

- **System Settings → Privacy & Security**, scroll down to *Security* and click **Open Anyway** next to Atalay's Terminal, then **Open**.
- Or in Terminal: `xattr -dr com.apple.quarantine "/Applications/Atalay's Terminal.app"`

## Updates

You only download it once. When a new version is out, the app tells you and shows what's new; one click installs it and restarts the app, and your chats keep running. Every update is signed, and the app checks the signature before it installs anything.

## Privacy

- The dashboard reads Claude Code's own files on your Mac (`~/.claude`: the session list and transcripts), read only. None of it leaves your Mac: no prompts, no code, no transcripts, no file names, no token counts.
- The app talks to its server only for the social parts and updates: your hacker name and tag, the app and macOS version, whether you're working each minute (for XP) and your time zone, your friends, requests, messages and status, and the leaderboard.
- Your Mac is known to the server by a salted hash of its hardware UUID (never the UUID itself) and a random token kept on the Mac.
- Messages are stored on the server so they reach your friends; they aren't end-to-end encrypted.
- Settings can hide your active time from friends and your name on the leaderboard.
- No analytics or tracking libraries. The app's source code is open: [atalaykarahan/atalay-terminal](https://github.com/atalaykarahan/atalay-terminal).

---

## Türkçe

**Kurulum**

1. Yukarıdaki **Download for macOS** bağlantısından **Atalays-Terminal.dmg**'yi indirip aç.
2. **Atalay's Terminal**'i **Applications** klasörüne sürükle.
3. Applications'tan aç.

Uygulama henüz Apple'a notarize edilmediği için macOS ilk açılışta "doğrulanamadı" der. Bir kez izin ver:

- **Sistem Ayarları → Gizlilik ve Güvenlik**, en alta in ve Atalay's Terminal'in yanındaki **Yine de Aç**'a, sonra **Aç**'a bas.
- Ya da Terminal'de: `xattr -dr com.apple.quarantine "/Applications/Atalay's Terminal.app"`

**Güncellemeler**

Bir kez indirmen yeter. Yeni sürüm çıkınca uygulama haber verir ve yenilikleri gösterir; tek tıkla kurulur, uygulama yeniden açılır, sohbetlerin çalışmaya devam eder. Her güncelleme imzalıdır, uygulama kurmadan önce imzayı kontrol eder.

**Gizlilik**

- Pano, Claude Code'un Mac'indeki kendi dosyalarını (`~/.claude`: oturum listesi ve transcript'ler) sadece okur. Hiçbiri Mac'inden çıkmaz: prompt, kod, transcript, dosya adı ya da token sayısı gönderilmez.
- Uygulama sunucusuyla sadece sosyal kısımlar ve güncellemeler için konuşur: hacker adın ve etiketin, uygulama ve macOS sürümü, her dakika çalışıp çalışmadığın (XP için) ve saat dilimin, arkadaşların, istekler, mesajlar ve durumun, bir de leaderboard.
- Sunucu Mac'ini, donanım kimliğinin tuzlanmış bir hash'i (kimliğin kendisi asla değil) ve Mac'inde duran rastgele bir token ile tanır.
- Mesajlar arkadaşlarına ulaşsın diye sunucuda saklanır; uçtan uca şifreli değildir.
- Ayarlardan aktif süreni arkadaşlarından, adını leaderboard'dan gizleyebilirsin.
- Hiçbir analitik ya da takip kütüphanesi yok. Uygulamanın kaynak kodu açık: [atalaykarahan/atalay-terminal](https://github.com/atalaykarahan/atalay-terminal).
