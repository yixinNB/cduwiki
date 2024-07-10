---
description: 本页面提供了成都大学各个网站的索引. 提供了密切相关的各种集成服务。本页面包含多个重要功能模块,为成都大学师生用户提供便捷的教学管理和学习支持。该网站具有丰富的内容资源,持续优化更新以满足师生的需求。作为成都大学师生的重要入口,该网站为用户提供了全面的教育服务。
---

# 网站导航
<script setup>
const NAV_DATA=[
    {
        title: '学校通用',
        items: [
            {
                icon: 'https://www.chaoxing.com/favicon.ico',
                title: '学习通',
                desc: '学习签到全用它',
                link: 'http://i.mooc.chaoxing.com/space/index?t=1699947729643',
            },
            {
                icon: 'https://xsswzx.cdu.edu.cn/favicon.ico',
                title: 'ISP',
                desc: '各种申请都找他 (经常打不开)',
                link: 'https://xsswzx.cdu.edu.cn/isp/',
            },
            {
                icon: 'https://devtool.tech/logo.svg',
                title: 'VPN',
                desc: '校外上不了学校网站就找他',
                link: 'https://vpn.cdu.edu.cn/portal/#!/login',
            },
            {
                icon: 'https://tool.lu/favicon.ico',
                title: '教务系统',
                desc: '查成绩专用',
                link: 'http://jiaowu.cdu.edu.cn/eams/homeExt.action#',
            },
            {
                icon: '/icons/json-cn.ico',
                title: '新教务系统',
                desc: '另一个教务系统',
                link: 'https://cdujx.mh.chaoxing.com/',
            },
            {
                icon: '/icons/json-cn.ico',
                title: '学校导航',
                desc: '学校的网站导航',
                link: 'https://myapp.cdu.edu.cn/index.html',
            },
            {
                icon: '/icons/json-cn.ico',
                title: '图书馆管理',
                desc: '我借的书还有多少天到期',
                link: 'http://libopac-cdu-edu-cn.vpn.cdu.edu.cn:8118/reader/redr_info.php',
            },
            {
                icon: '/icons/json-cn.ico',
                title: '超星课表',
                desc: '今天没课了吧',
                link: 'https://i.chaoxing.com/base',
            },
            {
                icon: '/icons/json-cn.ico',
                title: '智慧树',
                desc: '上网课的地方',
                link: 'https://onlineweb.zhihuishu.com/onlinestuh5',
            },
            {
                icon: '/icons/json-cn.ico',
                title: '财务处',
                desc: '交学费了',
                link: 'https://cwcs.cdu.edu.cn/FINPortal/casCddxLogin.action',
            },
        ],
    },
]
</script>
<MNavLinks v-for="{title, items} in NAV_DATA" :title="title" :items="items"/>
<br/>

## 各学院网站
**[计算机学院](计算机学院.md)**
