<template>
	<div class="fater-body-show">
        <Row :gutter="15">
            <Col span="8">
                 <div class="fater-calendar-panel">
                    <Calendar cell-height="40"/>
                </div>
            </Col>
            <Col span="16">
                <Card>
                    <template #title>
                        系统信息
                    </template>
                    <div>
                        <div class="fater-sysinfo-panle">
                            <table>
                                <tr>
                                    <td>系统名称</td>
                                    <td>在线考试系统 V1.0.0</td>
                                </tr>
                                <tr>
                                    <td>运行环境</td>
                                    <td>Python 3.9.9 + NodeJS 16.13.0 + MySQL 8.0</td>
                                </tr>
                                <tr>
                                    <td>客户端开发</td>
                                    <td>Vue3.0 + Vue-Router + Vuex + IView</td>
                                </tr>
                                <tr>
                                    <td>服务端开发</td>
                                    <td>Django4.0 + PyMySQL</td>
                                </tr>
                                <tr>
                                    <td>开发时间</td>
                                    <td>XXX</td>
                                </tr>
                            </table>
                        </div>
                    </div>
                </Card>
            </Col>
        </Row>

        <div class="fater-welcome-panle">
            Welcome Here !
        </div>
    </div>
</template>

<style></style>

<script>
export default{
		
    data(){
        return {

        }
    },
    methods:{
			
			
    },
    mounted(){

    }
}
</script>