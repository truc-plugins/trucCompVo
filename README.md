# trucComp@Vo

Prototype of the ultimate vocal compressor — built for nothing but vocals.

---

## Installation (Mac)

- **VST3**: Copy `trucComp@Vo.vst3` to `/Library/Audio/Plug-Ins/VST3/`
- **AU**: Copy `trucComp@Vo.component` to `/Library/Audio/Plug-Ins/Components/`

### ⚠️ macOS Security Warning
macOS may block the plugin on first use. Run this in Terminal:
```bash
xattr -cr ~/Library/Audio/Plug-Ins/VST3/trucComp@Vo.vst3
xattr -cr ~/Library/Audio/Plug-Ins/Components/trucComp@Vo.component
```
Then re-scan in your DAW.

---

## 導入方法（Mac）

1. [Releases](https://github.com/truc-plugins/trucCompVo/releases) から最新の zip をダウンロード
2. zip を解凍する
3. **VST3**: `trucComp@Vo.vst3` を `/Library/Audio/Plug-Ins/VST3/` にコピー
4. **AU**: `trucComp@Vo.component` を `/Library/Audio/Plug-Ins/Components/` にコピー
5. DAW を再起動してスキャン

### ⚠️ セキュリティ警告が出る場合
ターミナルで以下を実行してから、DAW で再スキャンしてください：
```bash
xattr -cr ~/Library/Audio/Plug-Ins/VST3/trucComp@Vo.vst3
xattr -cr ~/Library/Audio/Plug-Ins/Components/trucComp@Vo.component
```

---

## 動作環境

- Mac（Apple Silicon / Intel）
- VST3 / AU 対応 DAW
