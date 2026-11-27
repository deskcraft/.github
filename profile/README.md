# deskcraft

**机まわりの、小さな便利ツール。**
毎日のパソコン作業を少しだけ快適にする、小さなアプリやツールを作って公開しています。

**Small, handy tools for your desk.**
Little apps and utilities that make everyday computer work a bit more pleasant.

## ツール / Tools

<table>
  <tr>
    <td width="96" align="center" valign="top">
      <a href="https://github.com/deskcraft/clockpane"><img src="https://raw.githubusercontent.com/deskcraft/clockpane/main/docs/images/icon.png" width="80" alt="Clockpane"></a>
    </td>
    <td valign="top">
      <b><a href="https://github.com/deskcraft/clockpane">Clockpane</a></b> — macOS<br>
      デスクトップに置く時計アプリ。17 種類のデザインと自作デザイン、アラーム、タイマー、ポモドーロ、カレンダーの次の予定（会議リンク付き）、世界時計。<br>
      A desktop clock with 17 designs plus your own, alarms, timers, Pomodoro, your next calendar event (with meeting links) and world clocks.<br>
      <a href="https://github.com/deskcraft/clockpane/releases/latest/download/Clockpane.dmg">⬇️ ダウンロード / Download</a>
      ・ <a href="https://github.com/deskcraft/clockpane#readme">使い方 / Guide</a>
      ・ <a href="#homebrew">Homebrew</a>
    </td>
    <td width="200" align="center" valign="top">
      <a href="https://github.com/deskcraft/clockpane"><img src="https://raw.githubusercontent.com/deskcraft/clockpane/main/docs/images/clock-info.png" width="180" alt="Clockpane のスクリーンショット / screenshot"></a>
    </td>
  </tr>
</table>

ツールはこれから少しずつ増やしていきます。
More tools are on the way.

## Homebrew

```bash
brew tap deskcraft/tap
brew trust deskcraft/tap        # Homebrew 7 以降で必要 / required on Homebrew 7+
brew install --cask clockpane
```

## 使うときに / Notes

- どのツールも無料で、[MIT License](https://opensource.org/license/mit) で公開しています。
  All tools are free and released under the MIT License.
- macOS のアプリは Apple の署名（公証）をしていないため、初めて開くときに手順が必要です。各ツールの README をご覧ください。
  The macOS apps are not notarized by Apple, so the first launch needs a few extra steps — see each tool’s README.
- 不具合の報告や要望は、各ツールの Issues へどうぞ。
  For bug reports and requests, please open an issue in each tool’s repository.
