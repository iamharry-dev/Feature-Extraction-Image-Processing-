## 🖼️ Image Feature Extraction from Videos

This shell script extracts frames from videos using `ffmpeg` and saves them as JPEG images at a rate of **2 frames per second**.

### 📦 Requirements
- `ffmpeg` installed on your system.
- Bash environment.

### 🛠️ Usage

1. **Place your videos**:  
   - Add your video files (**.mp4**) to the `vid` folder.

2. **Run the Script**:  
```bash
bash extract_frames.sh
```

3. **Output**:  
   - Extracted frames will be saved in the `data` folder, with each video having its own subfolder.

### ⚙️ Script Explanation
- **Input**: Videos from `vid` directory with `.mp4` extension.
- **Output**: Frames stored in `data` directory at **2 FPS**.
- **Folder Structure**:  
  ```
  ├── data
  │   ├── video1
  │   │   ├── 1.jpg
  │   │   ├── 2.jpg
  │   ├── video2
  │   │   ├── 1.jpg
  │   │   ├── 2.jpg
  ├── vid
      ├── video1.mp4
      ├── video2.mp4
  ```

### 📝 Notes
- Ensure `vid` and `data` directories exist before running the script.
- Adjust the `-r 2` parameter to change the frame extraction rate.

---

