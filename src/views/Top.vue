<template>
    <div>
        <el-row><h1 style="margin-top: 30px;margin-right: 1200px">豆瓣电影排行榜</h1>
            <div style="margin-right: 1260px"><h3 style="color: #058304">豆瓣新片榜· · · · · ·</h3></div>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
            <img src="../assets/1.jpg" style="width: 150px; height: 200px">
        </el-col>
                <el-col :span="8" style="text-align: justify">
               <div style="margin-top: 20px; color: #466ba9">小丑/小丑起源电影：罗密欧/Romeo</div>
                    <div style="margin-top: 20px;color: #5d5d5d">2019-08-31(威尼斯电影节) / 2019-10-04(美国) / 杰昆·菲尼克斯 / 罗伯特·德尼罗 / 马克·马龙 / 莎姬·贝兹 / 谢伊·惠格姆 / 弗兰西丝·康罗伊 / 布莱恩·考伦 / 布莱恩·泰里·亨利 / 布莱特·卡伦 / 道格拉斯·霍奇斯 / 格伦·弗莱施勒 / 比尔·坎普...
                    </div>
                    <div style="margin-top: 25px;">
                        <el-rate
                                v-model="value5"
                                disabled
                                text-color="#ff9900"
                                text-template="{value}">
                        </el-rate>
                    </div>
                    <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.8</a>  &nbsp;(143368人评价)</div>
            </el-col>
        </el-row>
    <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/10.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">地久天长‎ (2019)</div>
                <div style="margin-top: 20px;color: #5d5d5d">中国大陆 / 剧情 / 家庭 / So Long, My Son / 175分钟
                    王小帅 / 王景春 / 咏梅 / 齐溪 / 王源 / 杜江 / 艾丽娅 / 徐程 / 李菁菁
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.7</a>  &nbsp;(2964563人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/7.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">攀登者‎ (2019)</div>
                <div style="margin-top: 20px;color: #5d5d5d">中国大陆 / 剧情 / 爱情 / 冒险 / The Climbers / 125分钟
                    李仁港 / 吴京 / 章子怡 / 井柏然 / 张译 / 胡歌 / 成龙 / 陈龙 / 多布杰
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.9</a>  &nbsp;(45358人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/6.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">爱尔兰人 / 爱尔兰杀手(港) / 听说你刷房子了
                    </div>
                <div style="margin-top: 20px;color: #5d5d5d">2019-09-27(纽约电影节) / 2019-11-01(美国点映)
                    罗伯特·德尼罗 / 阿尔·帕西诺 / 乔·佩西 / 安娜·帕奎因 / 杰西·普莱蒙 / 哈威·凯特尔 / 斯蒂芬·格拉汉姆 / 鲍比·坎纳瓦尔 / 杰克·休斯顿 / 阿莱卡萨·帕拉迪诺 / 凯瑟琳·纳杜奇...
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">9.0</a>  &nbsp;(3358人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/5.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">酷刑报告 The Report (2019)</div>
                <div style="margin-top: 20px;color: #5d5d5d">2019-01-26(圣丹斯电影节) / 2019-11-15(美国)
                    亚当·德赖弗 / 寇瑞·斯托尔 / 小伊万德·杜克 / 乔恩·哈姆 / 琳达·鲍威尔 / 安妮特·贝宁 / 桑德拉·兰德斯 / 约翰·罗斯曼 / 维克多·斯勒扎克 / 盖伊·博伊德
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">9.2</a>  &nbsp;(65396人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/8.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">准备好了没 Ready or Not (2019)</div>
                <div style="margin-top: 20px;color: #5d5d5d">2019-08-21(美国)
                    大卫·雷奇 / 道恩·强森 / 杰森·斯坦森 / 伊德里斯·艾尔巴 / 凡妮莎·柯比 / 艾莎·冈萨雷斯 / 海伦·米伦 / 瑞恩·雷诺兹 / 凯
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">9.1</a>  &nbsp;(19758人评价)</div>
            </el-col>
        </el-row>
    </div>
</template>
<script>
    import ElRow from "element-ui/packages/row/src/row";
    export default {
        components: {ElRow},
        data() {
            return {
                value5:3.0}}}
</script>
