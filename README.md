# 个人简历
宋昆达求职iOS/Web开发工程师简历

## 联系方式
- 手机：15222160477
- Email：<574779754@qq.com>
- WeChat: 15222160477

## 个人信息
- 宋昆达/男/1992
- 全日制本科/计科(软件工程)
- 工作年限：<span id="all-work-years"></span>年

- 期望：iOS高级程序员/25k~35k/天津

## 工作经历
### 世纪空联 
<span class="work-time" data-start-date="2016,4,25" data-end-date="now"></span>
> <b>世纪空联是一家从事移动互联网运营业务+飞机航空WIFI系统研发/改装业务的跨界型企业，总部位于北京，在天津和洛杉矶分别设立了研发中心（移动互联网）和设计中心（航电）。公司提供基于航空WIFI业务品牌形象/业务定位相关的增值服务，携手合作伙伴为航旅用户提供简约、安全、可靠的航旅服务。</b>
> #### IFE
> > 

> > * 
> > * 

### 金马达 
<span class="work-time" data-start-date="2015,4,10" data-end-date="2016,4,25"></span>
> <b>金马达研发团队通过移动互联网，将线下实体、线上服务进行完美融合，即是开放式的行业服务平台，又为车主提供无时间限制、无地域限制，透明、实惠、方便快捷的汽车服务O2O平台，营造开放、 共享、可持续发展的人-车-生活的生态圈</b>
> #### 金马达(用户/师傅端) 
> > 养车一站式平台，有预约，购物，和在线直播功能。

> > * 1.0版本的开发
> >     * 到店养车，预约维修，洗车，广告等组件编写
> > * 2.0版本的重写优化
> >     * 帮助组员开发，跟进项目进度
> >     * 在1.0的基础上进行网络请求归总，直播模块的添加，参与第三方直播库的bug提交和解决方案
> >     * 商城组件的编写及单元测试
> > * 师傅端 
> >     * 采用web(html-js-CSS-jQuery)-native(WebViewJavascriptBridge)混合开发 
> >     * 本地表单存储(SQLite3)


### 辰硕科技 
<span class="work-time" data-start-date="2013,2,17" data-end-date="2015,2,13"></span>
> <b></b>
> #### 邮箱项目(企业模块)
> > 主要有以下功能，邮件的账号，收发邮件，集团通讯录，聊天

> > * 主要参与邮箱开发，根据项目需求方提供邮件的加解密
> > * 由于代码审核不能使用第三方库，所以只能团队开发且周期很长

> #### 医疗IM项目(患者/医生端)
> > 介绍

> > * Demo版本开发
> >     * 使用LeanCloud平台开发实现患者与医生实时聊天
> > * 1.0版本独立开发
> >     * 添加聊天群组功能
> >     * 医疗小报开发
> >     * 医疗模板开发

## 技能清单
- iPhone ,iPad APP开发(OC,swift)
- web开发(webpack,React,MobX)
- 应用优化(Debug)
- 项目攻关(根据工作快速学习能力)

# 致谢

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
        var inWork = "";
        if (mFullYear > 0 || mMonth >= 0) {
            inWork += "(";
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
            inWork += ")";
        }

        workTimeItem.textContent = startTime.getFullYear().toString()
            + "/"
            + (startTime.getMonth() + 1)
            + " ~ "
            + (endTimeSplit == "now" ? "至今" :
                    (endTime.getFullYear().toString()
                        + "/"
                        + (endTime.getMonth() + 1))
            )
            + inWork
    }
    allWorkYearsItem.textContent = Math.floor(allWorkMonths / 12);
    
}
initAllWorkTime();
</script>
