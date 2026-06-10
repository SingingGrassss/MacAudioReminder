# MacAudioReminder / Mac 音频提醒配置工具

This is a local web tool for quickly configuring audio reminders on macOS.
这是一个本地网页应用，用于在 macOS 上快速配置音频定时提醒。

## 项目用途 / Purpose

- Select local audio files and set reminder times. / 在网页界面中选择本地音频文件并设置提醒时间。
- Save reminder settings in browser `localStorage`. / 将提醒配置保存在浏览器 `localStorage` 中。
- Generate deploy commands that can be copied into Terminal. / 自动生成可复制到终端执行的一键部署命令。
- Use `LaunchAgent` and executable scripts to play audio at scheduled times. / 通过 `LaunchAgent` 和可执行脚本在指定时间播放音频。

## 使用方法 / How to use

1. Open `reminder.html`. / 打开 `reminder.html`。
2. Select an audio file and set a reminder time. / 选择音频文件并设置提醒时间。
3. Click “保存提醒” to save the reminder. / 点击“保存提醒”保存配置。
4. Copy the generated deploy command and paste it into Terminal. / 复制“⼀键部署命令”并粘贴到终端执行。
5. After execution, macOS will play the selected audio at the scheduled time. / 终端执行后，macOS 会在设定时间自动播放对应音频。

