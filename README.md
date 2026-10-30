# yesterday-todayAndTomorrow

用户共有 38 个 clips，其中 10 个不操作，实际处理目标为 28 个。目前已完成 20 个，还需处理 8 个。

- `clips/`：用户原始片段，保持文件名、编号和视频内容不变，使用 Git LFS 保存。
- `firstPicture/`：每个已上传片段的第一帧 PNG，与视频使用同名文件（例如 `shot23V2.mp4` 对应 `shot23V2.png`）。
- `clips/manifest.csv`：当前已接收片段的尺寸、时长及 SHA-256 校验值。
- `codex分割版/`：此前自动切分的 164 个分镜与首帧，仅作历史归档，不用于后续工作。

已处理文件：shot2V2、shot3、shot4、shot5V2、shot6、shot7、shot8V2、shot10、shot11、shot16、shot23V2、shot24、shot26、shot27、shot31、shot32、shot33、shot34、shot36、shot38。

不操作编号：1、14、17、19、22、25、28、30、35、37。

待处理编号：9、12、13、15、18、20、21、29。

后续片段上传后继续加入当前工作集，不以历史归档替代缺失片段。压缩包不上传 GitHub。
