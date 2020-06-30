# 宋昆达 · 前端开发工程师

## 联系方式

-   手机：152-2216-0477
-   邮箱：<mailto:admin@songkunda.cn>
-   微信：152-2216-0477

## 个人信息

-   **年龄**：32 岁 / 男
-   **学历**：本科 / 计科（软件工程）
-   **期望薪资**：25K/月
-   **工作地点**：天津

## 技能清单

### 技术栈

-   **前端开发**
    -   **React**：⭐⭐⭐⭐⭐
    -   **Vue**：⭐⭐⭐
    -   **Webpack**：⭐⭐⭐⭐
    -   **MobX**：⭐⭐⭐⭐
    -   **Redux**：⭐⭐⭐
-   **移动开发**
    -   **Objective-C / Swift**：⭐⭐⭐⭐
    -   **C++**：⭐⭐⭐
    -   **Flutter**：⭐⭐⭐

### 项目能力

-   快速学习、技术攻关、性能优化、系统重构

## 工作经历

### 世纪空联 <span class="work-time" data-start-date="2016,4,25" data-end-date="now"></span>

**公司简介**：世纪空联专注于移动互联网与飞机航空 WiFi 系统研发，致力于为航空用户提供高效、可靠的服务。总部设在北京，研发与设计中心位于天津和洛杉矶。

#### IFE 组

-   **机上娱乐系统 (IFE Web)**：

    -   **职责**：升级系统为 React 单页应用，改进用户体验，支持流畅的视频播放。
    -   **成就**：上线后系统稳定性提高了 30%，减少了加载时间，用户满意度提升。
    -   **项目技术栈**：React、Antd、MobX、HLS

-   **React 培训**：
    -   **职责**：负责团队的 React 技术培训和推广，提升团队开发效率。
    -   **成就**：提高团队成员的 React 应用熟练度，缩短了 1 倍的开发时间。

#### Console 组

-   **智慧客舱系统 (SCS)**：

    -   **职责**：基于 Flutter 构建跨平台系统，实现多航司机上售卖及服务功能。
    -   **成就**：实现多模块解耦和性能提升，使得系统响应速度提升约 40%。
    -   **项目技术栈**：Flutter、Dart

-   **信息汇总平台 (DashBoard)**：

    -   **职责**：负责开发和维护汇总平台，实现多航司机上数据可视化。
    -   **项目技术栈**：React、ReactFlow、TypeScript

-   **机上中枢控制平台 (Console)**：
    -   **职责**：重构控制平台并迁移至 React + Redux 架构。
    -   **成就**：全后端分离,提升代码维护效率及测试成本.
    -   **项目技术栈**：
        -   FrontEnd：React、Redux (Saga)
        -   BackEnd：Spring Boot、SQL

#### Core 组

-   **机上双离线支付**：
    -   **职责**：与支付宝团队合作，开发离线支付功能和 iOS 离线 SDK。
    -   **成就**：系统稳定性达到 99.99%以上，完成了技术攻关。
    -   **项目技术栈**：SDK、Objective-C

---

### TIMAT <span class="work-time" data-start-date="2022,10,7" data-end-date="2023,4,27"></span>

-   **AIGC 小程序**：
    -   **职责**：开发 AI 图像生成功能小程序，支持图片生成和编辑功能。
    -   **成就**：上线后用户增长率达到 120%，应用稳定性显著提升。
    -   **项目技术栈**：Uni-App、Vue、Stable Diffusion

---

### 金马达 <span class="work-time" data-start-date="2015,4,10" data-end-date="2016,4,25"></span>

**公司简介**：金马达是一个 O2O 汽车服务平台，为车主提供预约、购物及直播等服务。

-   **金马达用户端**：

    -   **职责**：主导 1.0 和 2.0 版本重构与优化，提升了系统的响应和用户体验。
    -   **项目技术栈**：OC、HLS 直播、RN

-   **金马达师傅端**：
    -   **职责**：负责采用 Web + Native 混合开发，优化本地表单存储（SQLite3）。
    -   **成就**：通过提升系统响应速度，汽修师傅反馈和满意度.
    -   **项目技术栈**：WebViewJavaScriptBridge、jQuery、SQLite3
-   **ERP**:
    -   **职责**: 完成进销存及分红管理平台的开发工作。
        -   **项目技术栈**: PHP5

---

### 辰硕科技 <span class="work-time" data-start-date="2013,2,17" data-end-date="2015,2,13"></span>

-   **邮箱项目**：

    -   **职责**：驻场开发企业邮箱功能，独立实现邮件加解密。
    -   **成就**：企业邮件安全性显著提升，业务合规性达标。
    -   **项目技术栈**：Objective-C、加解密算法 (AES + RSA)

-   **医疗 IM 项目**：
    -   **职责**：开发患者/医生聊天模块，实现了即时通讯功能。
    -   **成就**：完成从零到一.
    -   **项目技术栈**：LeanCloud SDK、Objective-C

---

## 致谢

感谢团队和身边支持的伙伴们。

<script type="text/javascript">
function initAllWorkTime() {
    var workTimeItems = document.getElementsByClassName("work-time");
    var allWorkYearsItem = document.getElementById("all-work-years");
    var allWorkMonths = 0;
    for (var i = 0; i < workTimeItems.length; ++i) {
        var workTimeItem = workTimeItems[i];
        var startTimeSplit = workTimeItem.dataset.startDate.split(",");
        var startTime = new Date(startTimeSplit[0], startTimeSplit[1] - 1, startTimeSplit[2])

        var endTimeSplit = workTimeItem.dataset.endDate.split(",");
        var endTime = undefined;
        if (endTimeSplit == "now") {
            endTime = new Date()
        } else {
            endTime = new Date(endTimeSplit[0], endTimeSplit[1] - 1, endTimeSplit[2])
        }
        var mDate = new Date(endTime - startTime);
        var mFullYear = mDate.getFullYear() - 1970;
        var mMonth = mDate.getMonth() + 1;
        var inWork = "  -  ";
        if (mFullYear > 0 || mMonth >= 0) {
        
            if (mMonth >= 12) {
                mMonth = mMonth - 12;
                ++mFullYear;
            }
            if (mFullYear > 0) {
                inWork += mFullYear;
                inWork += "年"
                allWorkMonths += mFullYear * 12;
            }
            if (mMonth > 0) {
                inWork += mMonth;
                inWork += "月"
                allWorkMonths += mMonth;
            }
        }

        workTimeItem.textContent = "(" +startTime.getFullYear().toString()
            + "/"
            + (startTime.getMonth() + 1)
            + " ~ "
            + (endTimeSplit == "now" ? "至今" :
                    (endTime.getFullYear().toString()
                        + "/"
                        + (endTime.getMonth() + 1))
            )
            + inWork
            + ")";
    }
    allWorkYearsItem.textContent = Math.floor(allWorkMonths / 12);
    
}
initAllWorkTime();
</script>
