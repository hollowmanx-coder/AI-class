## TEST TEST

# Introduction to Git and GitHub — Revised Lecture Plan & Slide Outline

## 1. 修訂重點與時間分配（50分鐘）

1. **Subtopic 1: Exploring GitHub — Using Shared Projects and Games（10 mins）**
   * 從下載與遊玩 GitHub 上的開源小遊戲切入，認識 Repository 與 `README.md`。
2. **Subtopic 2: Hands-On Git — Creating a Project and Tracking Changes（20 mins）** *(精簡步驟版)*
   * **投影片保持極簡大字：** 只列出核心動線（New Repo → Create `README.md` → Commit → View Diff），不把視窗縮放、分支保護提示等瑣碎 UI 細節寫進投影片，讓您直接切瀏覽器畫面 Live Demo。
3. **Subtopic 3: Why GitHub over Google Docs? — Direct AI Integration & Visual Diff（20 mins）** *(結合 GitHub Copilot 與個人數位名片作業)*
   * **大一生活化範例：** **「大學分組專題：打造系學會活動／選課問答 AI 助手（或互動小工具）」**。
   * **兩大核心強項對決：**
     1. **一眼看出修改處（Visual Diff & Safe Review）：** 告別 Google Docs 被室友或 AI 偷偷改壞卻找不到改了哪裡的惡夢，用紅綠 **Diff** 與 **Pull Request** 精準把關每一行字。
     2. **與 AI 直接連結（Direct AI Integration）：** 告別在 Google Docs 與 AI 視窗之間無限複製貼上；直接使用 GitHub 網頁內建的 **GitHub Copilot**（或連結外部 AI）讀取儲存庫、自動開分支改檔案，等你檢視 Diff 並按下 Merge！
   * **全新創意回家作業：** **打造「GitHub 個人數位名片（Profile README）」**，並使用內建的 **GitHub Copilot** 進行升級修改，繳交「個人首頁看板」與「紅綠 Diff 比對」兩張截圖，讓老師在課程網站一眼秒判學習成果與個人創意。

---

## 2. 逐頁雙語投影片大綱（Slide-by-Slide Bilingual Outline）

*(嚴格遵循教學指南：4:3 版面邏輯、英文為主且繁中緊隨其下、定義加灰底框、Takeaway 使用 `→` 與直角灰框、每頁聚焦單一教學目的)*

### **Opening**

* **Slide 1 [Title Slide]**
  * **Title:** Introduction to Git and GitHub: Version Control and AI Collaboration
    認識 Git 與 GitHub：版本控制與 AI 專案協作
  * **Subtitle:** From Running Open-Source Projects to Building AI-Connected Workflows
    從執行開源專案到打造連結 AI 的工作流程

---

### **Subtopic 1: Exploring GitHub — Using Shared Projects and Games (10 mins)**

* **Slide 2 [Section Divider]**
  * **Title:** Part 1: Exploring GitHub through Practical Projects
    第一部分：從實用專案探索 GitHub

* **Slide 3 [Introduction / Hook]**
  * **Title:** Where Do Creators Share Ready-to-Use Games and AI Tools?
    創作者都在哪裡分享現成的小遊戲與 AI 工具？
  * **Bullets:**
    * Imagine wanting a web mini-game, a study timer, or tested AI prompt templates without building everything from scratch.
      想像你想要一個網頁小遊戲、讀書計時器或測試過的 AI 提示詞模板，卻不想從零開始自己寫。
    * Millions of creators publish open-source projects online so anyone can download, run, and learn from them immediately.
      數百萬創作者在線上公開開源專案，讓任何人都能立即下載、執行並從中學習。

* **Slide 4 [Definition]** *(Shaded Definition Box)*
  * **Title:** What Is GitHub? What Is a Repository?
    什麼是 GitHub？什麼是專案儲存庫（Repository）？
  * **Definition Box:**
    * **GitHub:** A cloud platform for hosting, sharing, and collaborating on software and text-based projects.
      **GitHub：** 一個用於託管、分享及協作軟體與純文字專案的雲端平台。
    * **Repository (Repo):** A project folder on GitHub that stores all project files and their complete revision history.
      **專案儲存庫（Repo）：** GitHub 上的專案資料夾，存放所有專案檔案及其完整的修改歷史紀錄。

* **Slide 5 [Interaction / Live Demonstration]**
  * **Title:** Live Demo 1: Downloading and Running a Mini-Game from GitHub
    實作示範一：從 GitHub 下載並執行別人製作的小遊戲
  * **Bullets:**
    * **Step 1:** Open a public game repository (e.g., *2048*) and read its **`README.md`** instructions.
      **步驟一：** 打開一個公開遊戲儲存庫（如 *2048*），閱讀它用 Markdown 寫成的 **`README.md`** 說明書。
    * **Step 2:** Click **`<> Code`** → **`Download ZIP`** to run it locally, or play directly via the web link.
      **步驟二：** 點擊 **`<> Code`** → **`Download ZIP`** 下載到電腦執行，或直接透過網頁連結遊玩。

---

### **Subtopic 2: Hands-On Git — Creating a Project & Tracking Changes (20 mins)**

* **Slide 6 [Section Divider]**
  * **Title:** Part 2: Creating Your First Repository and Understanding Git
    第二部分：建立你的第一個專案並理解 Git

* **Slide 7 [Definition]** *(Shaded Definition Box)*
  * **Title:** What Is Git? What Is a Commit?
    什麼是 Git？什麼是提交（Commit）？
  * **Definition Box:**
    * **Git:** A version control system that tracks exact changes in files over time so you can inspect or restore any earlier version.
      **Git：** 一種版本控制系統，能追蹤檔案隨時間發生的精確變更，讓你隨時檢視或還原任何早期版本。
    * **Commit:** A saved snapshot of your project at a specific moment, paired with a brief message explaining what changed.
      **提交（Commit）：** 專案在特定時間點的「存檔快照」，並附帶一段簡短訊息說明這次改了什麼。

* **Slide 8 [Interaction / Live Demonstration]** *(極簡步驟，細節由老師現場切換瀏覽器示範)*
  * **Title:** Live Demo 2: Create a Repository and Upload `README.md`
    實作示範二：建立新專案並完成第一次 Commit 存檔
  * **Bullets:**
    * **Step 1 (Create Repo):** Click **`+`** → **`New repository`**, enter a project name, select **Public**, and click **Create**.
      **步驟一（建立專案）：** 點擊 **`+`** → **`New repository`**，輸入專案名稱、設為 **Public** 並建立。
    * **Step 2 (Add `README.md`):** Create or upload your `README.md` file using Markdown syntax (headings, links, and pasted images).
      **步驟二（新增說明檔）：** 使用 Markdown 語法（標題、超連結、貼上圖片）建立或上傳你的 `README.md`。
    * **Step 3 (First Commit):** Write a short **Commit message** and click **`Commit changes`** to save your first project snapshot.
      **步驟三（首次提交）：** 寫下簡短的 **Commit 訊息**，點擊 **`Commit changes`** 完成第一個版本存檔。

* **Slide 9 [Interaction / Live Demonstration]** *(極簡步驟，現場示範點開 History 與紅綠 Diff)*
  * **Title:** Live Demo 3: Edit Files and Track Exact Changes with "Diff"
    實作示範三：修改檔案並用「Diff」一眼看出差異
  * **Bullets:**
    * **Step 1 (Make an Edit):** Click the **Edit (✏️)** icon on `README.md`, modify a few lines, and Commit your changes.
      **步驟一（修改並存檔）：** 點擊 `README.md` 右上角的**鉛筆圖示（✏️）**修改內容，並再次 Commit 存檔。
    * **Step 2 (Inspect History & Diff):** Click **`History`** to view your timeline of Commits and open the **Diff (Difference)** view.
      **步驟二（檢視歷史與差異）：** 點擊 **`History`** 查看版本時間軸，點選任一版本打開 **Diff（差異比對）**畫面。
    * **Step 3 (Read the Colors):** **Green (`+`)** highlights added lines; **Red (`-`)** highlights deleted or replaced lines.
      **步驟三（判讀紅綠標記）：** **綠底（`+`）**代表新增的行數；**紅底（`-`）**代表被刪除或取代的舊內容。
  * **Takeaway Box:** `→` With Git, you never need filenames like `Project_v3_FINAL.md`—every change is cleanly recorded in one place.
    `→` 有了 Git，你再也不需要取名 `報告_v3_最終版.md`——所有修改歷程都清楚記錄在同一個檔案裡。

---

### **Subtopic 3: Why GitHub Instead of Google Docs? — AI Integration & Visual Diff (20 mins)**

* **Slide 10 [Section Divider]**
  * **Title:** Part 3: Why Use GitHub Instead of Google Docs in the Age of AI?
    第三部分：AI 時代，為什麼要用 GitHub 而不是 Google Docs？

* **Slide 11 [Introduction / Hook — New Freshman Scenario]**
  * **Title:** Scenario: Building a Group Term Project with Teammates and AI
    大一專題情境：4 個組員加上 AI 助手，一起打造「選課與校園問答機器人」
  * **Bullets:**
    * Your group project contains multiple Markdown files: a master `README.md` with AI system instructions, a course FAQ database, and testing rules.
      你們的專題包含多個 Markdown 檔案：寫有 AI 系統指令的 `README.md` 主檔、選課問答題庫，以及測試規則。
    * **The Pain of Google Docs:** Teammate A accidentally overwrites your best prompt, and every time you ask ChatGPT or Claude for help, you have to copy-paste 20 pages of text back and forth!
      **Google Docs 的兩大痛點：** 室友 A 不小心覆蓋掉你調教最好的 Prompt 卻找不到改了哪裡；而且每次請 AI 幫忙修改，都要手動複製貼上幾十頁文字！

* **Slide 12 [Comparison]** *(Two Columns — Highlighting Diff & AI Connection)*
  * **Title:** Collaboration Showdown: Google Docs / Drive vs. GitHub
    協作大對決：Google Docs / 雲端硬碟 vs. GitHub
  * **Left Column — Google Docs / Cloud Drive (Manual & Fragile / 手動搬運且易被改壞):**
    * **Hard to Spot Changes:** When a teammate or AI rewrites a section, changes blend right in—it is exhausting to figure out what broke.
      **難以看出改了哪裡：** 當組員或 AI 改寫某個段落時，文字直接被覆蓋，很難一眼抓出到底改壞了哪一行。
    * **Copy-Paste Bottleneck with AI:** Closed document format requires endless manual copy-pasting between Google Docs and AI chat windows.
      **與 AI 協作需不斷複製貼上：** 封閉的文件格式，讓你必須在 Google Docs 與 AI 視窗之間無限手動搬運文字。
  * **Right Column — GitHub Repository (AI-Connected & Traceable / 直接連 AI 且差異一目瞭然):**
    * **Instant Visual Diff:** Every edit by a human or AI is highlighted line-by-line in **Green (`+`)** and **Red (`-`)** before or after saving.
      **修改處一目瞭然（Visual Diff）：** 無論是組員還是 AI 改的，每一行增減都會用**綠底（`+`）**與**紅底（`-`）**精準標示。
    * **Direct AI Integration:** Built-in **GitHub Copilot** and external AI tools can read your repository directly and propose updates automatically.
      **與 AI 直接連結：** 內建的 **GitHub Copilot** 與外部 AI 工具能直接讀取整個儲存庫，甚至自動幫你提出修改建議。

* **Slide 13 [Example / Application Series — 1/2: Direct AI Connection]** *(Shared Heading Hierarchy)*
  * **Shared Heading:** Core Strengths of GitHub for Student Projects
    GitHub 在大學專題中的核心強項
  * **Category:** Strength 1: Direct AI Integration / 強項一：與 AI 工具直接連結
  * **Specific Subtitle:** Using Built-in GitHub Copilot & External AI Without Copy-Pasting
    直接使用內建的 GitHub Copilot 與外部 AI，徹底告別複製貼上
  * **Bullets:**
    * **Zero Copy-Pasting:** Click the built-in **GitHub Copilot** icon right inside GitHub (or connect ChatGPT / Claude) so the AI immediately reads your entire repository and `[AI System Prompt]`.
      **告別複製貼上：** 直接點擊 GitHub 網頁右上角內建的 **GitHub Copilot**（或綁定外部 AI 工具），AI 就能一次讀懂整個儲存庫的所有檔案與系統提示詞。
    * **AI as a Virtual Teammate:** Ask **GitHub Copilot** to rewrite or upgrade your `.md` files—it can edit files on a new branch and generate a preview of changes right on GitHub for your review!
      **AI 化身虛擬組員：** 請 **GitHub Copilot** 幫忙改寫或升級你的 `.md` 檔案——它能直接在分支上修改檔案，並在 GitHub 畫面上自動產生修改前後的比對預覽等你審核！

* **Slide 14 [Example / Application Series — 2/2: Visual Diff & Safe Review]** *(Shared Heading Hierarchy)*
  * **Shared Heading:** Core Strengths of GitHub for Student Projects
    GitHub 在大學專題中的核心強項
  * **Category:** Strength 2: Crystal-Clear Change Tracking / 強項二：修改處一目瞭然與安全審核
  * **Specific Subtitle:** Reviewing Teammate or AI Edits via Branches and Pull Requests
    透過分支（Branch）與合併申請（Pull Request），一眼看清組員或 AI 改了哪裡
  * **Bullets:**
    * **Draft on a Branch (Sticky Note):** When a teammate or **GitHub Copilot** suggests an update, they edit on a separate **Branch** so your `main` project never breaks unexpectedly.
      **在分支（便利貼）上安全修改：** 當組員或 **GitHub Copilot** 要修改內容時，會先在獨立的 **Branch** 上動工，絕不會直接弄壞 `main` 主專案。
    * **Inspect Diff & Merge:** They submit a **Pull Request**. You check the **Green (`+`) / Red (`-`) Diff** at a glance, click **`Merge pull request`** to approve, and delete the temporary branch!
      **看一眼紅綠 Diff 再按合併：** 對方送出 **Pull Request** 後，你只要看一眼紅綠 **Diff** 確認沒亂改，點擊 **`Merge`** 即可正式併入主檔，並刪除臨時分支！
  * **Takeaway Box:** `→` GitHub lets AI read your whole project directly while giving you 100% visual control over every single line changed.
    `→` GitHub 讓 AI 能直接讀取你的完整專案，同時讓你一眼看清、完全掌控每一行被修改的內容。

* **Slide 15 [Homework Slide]** *(Creative, Visual & Instant-Grading Friendly)*
  * **Title:** Homework: Create Your GitHub Profile Card & Upgrade It with Copilot
    回家作業：打造「GitHub 個人數位名片」，並用 GitHub Copilot 修改與比對差異
  * **Bullets:**
    * **Task 1 (Unlock Your Profile `README.md`):** Create a **Public** repository named **exactly after your GitHub username** (`username/username`). Write a creative first draft (`v1.0`) introducing your college life, hobbies (with emojis!), links, at least **1 image**, and an **`[AI System Prompt]`**.
      **任務一（解鎖個人首頁大看板）：** 建立一個與自己**「GitHub 帳號完全同名」**的公開儲存庫（`帳號/帳號`）。在 `README.md` 寫下初版（`v1.0`）個人介紹、興趣嗜好（加上 Emoji！）、超連結、至少 **1 張圖片**與一段**給 AI 的專屬指令**。
    * **Task 2 (Edit with GitHub Copilot & Compare the "Diff"):** Open **GitHub Copilot** (top-right icon on GitHub) to upgrade or playfully rewrite your profile into `v2.0`. Commit or merge the changes, then open **`History`** to inspect the **Red (`-`) and Green (`+`) Diff**.
      **任務二（用 GitHub Copilot 升級改寫並比對 Diff）：** 點擊網頁右上角的 **GitHub Copilot** 圖示，請 AI 幫你的個人名片升級或改寫成 `v2.0` 版本並完成 Commit 存檔；接著點開 **`History`** 檢視修改前後的 **紅綠 Diff 比對結果**。
    * **Submission (Upload 2 Screenshots + URL to Course Website):**
      **繳交方式（請上傳 1 頁 PDF 或組合截圖至課程網站，讓老師一眼看出成果）：**
      1. **Your Profile URL:** `https://github.com/your-username`
         **你的 GitHub 個人首頁網址**。
      2. **Screenshot 1 (Your Creativity):** Your live **GitHub Profile page** showing your custom `README.md` banner, image, and green contribution graph.
         **截圖一（展現個人創意）：** 你的 **GitHub 個人首頁全貌**（需清楚看到個人看板排版、圖片與下方的綠色貢獻方格）。
      3. **Screenshot 2 (Your Git & Copilot Proof):** The **Commit Diff view** showing the **Red (`-`) deleted lines** and **Green (`+`) Copilot-updated lines**.
         **截圖二（證明學會 Git 與 AI 修改）：** 點開歷史紀錄的 **紅綠 Diff 對照畫面**，清楚呈現初版與 Copilot 修改後的增刪差異。
  * **Takeaway Box:** `→` Turn your GitHub homepage into a unique digital business card—and let the Red/Green Diff prove your Git and Copilot skills at a glance!
    `→` 把 GitHub 首頁變成你獨一無二的數位名片——並用一張清楚的紅綠 Diff 截圖，讓老師一眼看見你的 Git 與 Copilot 實戰力！
