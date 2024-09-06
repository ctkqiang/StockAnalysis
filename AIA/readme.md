Here's the `README.md` translated into Chinese:

---

# AIA 马来西亚基金分析

本项目旨在从 AIA 马来西亚网站中提取和分析最新的基金详细信息，以便进行全面的比较，帮助做出明智的投资决策。

## 作者
钟智强

## 项目概述

本应用程序自动化下载基金数据的过程，进行探索性数据分析，并可视化关键指标。分析涵盖了 NAV 价格、变动和风险等级等方面，帮助用户识别表现最佳的基金并了解其风险特征。

### 特性：
1. **自动数据检索**：
   - 从 AIA 马来西亚网站下载最新的基金数据。

2. **数据探索与筛选**：
   - 将基金数据加载到 pandas DataFrame 中。
   - 根据 NAV 价格和变动等标准进行筛选，识别表现最佳的基金。

3. **数据可视化**：
   - 生成各种图表（条形图、散点图、小提琴图）以可视化基金表现和风险等级。

4. **综合比较**：
   - 根据 Shariah 合规性和资产配置等标准进一步筛选基金。

## 安装

### 先决条件
- Python 3.x
- Jupyter Notebook
- 以下 Python 库：
  - pandas
  - seaborn
  - matplotlib
  - selenium
  - webdriver_manager

### 安装步骤

1. **克隆仓库**：
   ```bash
   git clone https://github.com/your-repo/aia-malaysia-funds-analysis.git
   cd aia-malaysia-funds-analysis
   ```

2. **安装所需的库**：
   ```bash
   pip install -r requirements.txt
   ```

3. **下载 WebDriver**：
   - 对于 Chrome：从 [ChromeDriver](https://sites.google.com/chromium.org/driver/) 下载。
   - 对于 Safari：确保系统上已安装 Safari。

## 使用方法

### 第一步：下载数据集
- 脚本自动下载 AIA 马来西亚 [投资挂钩基金页面](https://www.aia.com.my/en/our-products/investment-linked-funds.html) 的基金数据。

### 第二步：加载和探索数据
- 将下载的 CSV 文件加载到 pandas DataFrame 中进行探索和初步筛选。

### 第三步：筛选和识别最佳基金
- 根据 NAV 价格和变动等表现指标筛选基金，识别前 5 名表现最佳的基金。

### 第四步：可视化数据
- 生成各种可视化图表：
  - **条形图**：显示 NAV 价格和变动。
  - **散点图**：比较 NAV 价格与变动的风险等级。
  - **小提琴图**：可视化不同风险等级的 NAV 价格和变动分布。

### 第五步：附加筛选
- 根据资产配置、市场或 Shariah 合规性进一步筛选基金。

### 第六步：识别最高回报的基金
- 确定并可视化 NAV 价格或变动最高的基金。

### 第七步：可视化风险等级
- 生成小提琴图和条形图，比较不同风险等级的 NAV 价格和变动。

## 示例笔记本

以下笔记本可用：
- `AIA_Malaysia_Funds_Analysis.ipynb`：包含完整分析的主要笔记本。

## 许可证
本项目采用 MIT 许可证。

---

Feel free to adjust any specifics to better fit your project details!