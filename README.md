<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>船舶运维智能分析系统</title>
		<link href="船舶.css" type="text/css" rel="stylesheet"/>
		<script>
		     function  getD1(){
		         var date=new Date();
		         var d1=date.toLocaleString();
		         document.getElementById("datetime").innerHTML =d1; 
		     }
		 
		     setInterval("getD1();",1000);
		 
		</script>
		 <style>
		html,body{
				height: 100%;
		         }
		 footer{
				position: relative;
		             height: 10%;
		             top: 90%;
		             /*background-color: black;*/
		         }
                 
body{
	height: 100%;

	background-size: auto 870px;
	background-color: #12376E;
}
.ym{
	
	width: 100%;

	
}
.tt{text-align: center;
	font-size: xx-large;
	background: linear-gradient(to bottom,#f4f4f4, #1a81e8);
	-webkit-background-clip: text;
	color: transparent;

}
.t img{
		width: 200px;
		height: auto;
}


.cl{
	color: #f4f4f4;
	text-align: right;
	position: relative;
	top: -50px;
}
.box{
	font-size: large;
	text-align: center;
	color: #ffffff;
	width: 450px;
	height: 600px;
	border: 1px solid #9e9e9e;
	border-radius: 10px;
	position: relative;
	left: 25px;
	top: 0px;
	
}
.box img{
	height: 24%;
	width: 72%;
}
.box button{
	text-align: left;
	background-color: #4567AC;
	width: 35%;
	height: 5%;
	color: #ffffff;
	display: inline-block;
	
}

box.p{
	text-align: left;
	position: relative;
	top: -40px;
	left: 65px;
}
#zt1{
	font-size: 15px;
	color: red;
	font-family: 'Courier New', Courier, monospace;
}
table{
	text-align: center;
	font-size: smaller;
	border: 1px;
}
table tr:nth-child(2n+1){
	background-color: #26407B;
}
table tr:nth-c9ild(2n){
	background-color: #1F3258;
}
table td{padding: 9px;}
.box1{
	display: flex;
	text-align: center;
	width: 968px;
	height: 50px;
	border-radius: 10px;
	position: relative;
	left: 526px;
	top: -600px;
	
}
.box1 button{
	text-align: center;
	color: #ffffff;
	border: 1px solid #ffffff;
	border-radius: 10px;
	background-color: #12376E;
	width: auto;
	margin-right: 20px;
	width: 125px;
	
}
.box2 {
position: relative;

width: 170px;

height: 200px;

left: 878px;

top: -600px;

border-radius: 5px;

background-color: #21498E;
color: yellow;

}
.box2 input{
	border: none;
	background-color: #21498E;
	color: #ffffff;
}
.box3{
	display: flex;
	flex-direction: row;
	justify-content: space-evenly;
	font-size: large;
	text-align: left;
	color: #ffffff;
	width: 450px;
	height: 150px;
	border: 1px solid #9e9e9e;
	border-radius: 10px;
	position: relative;
	left: 1058px;
	top: -800px;
	
}
.box31{
	width: 50%;
	float: left;
	font-size: x-large;
	text-align: center;
}
.box32{
	width: 50%;
	float: left;
	font-size: large;
	text-align: center;
	letter-spacing: 6px;
	margin: 35px;
}
.box4{
	font-size: large;
	text-align: center;
	color: #ffffff;
	width: 450px;
	height: 350px;
	border: 1px solid #9e9e9e;
	border-radius: 10px;
	position: relative;
	left: 1058px;
	top: -783px;
	
}
.ll li{
	background-color: #234078;
	padding: 8px 11px;    
	
	 float: left;   
	
	 list-style: none;   
	
	 color:#fff;
	
}
.box4 img{
	width: 90%;
	height: 60%;
}
.box4 select{
	width: 10%;
	text-align: left;
	background: none;

}
		 </style>
	</head>
	<body  class="body">
		<div class="ym">
			<h1 class="tt">船舶运维智能分析系统</h1>
				</div>
		<div class="t">
		<img src="C:\Users\28445\Desktop\高英伟\图层 0.png"/>
		</div>
		
		<div class="cl" id="datetime"></div>
		<div class="box">
			<p>—————报警雷达————</p>
			<img src="C:\Users\28445\Desktop\高英伟\pngsucai_3383796_c73803.png"/>
			<p >·告警问题                   预警数量·</p>
			<button>告警数量5个</button>
			<button>预警数量2个</button>
			<p>—————预警详情————</p>
			<table>
				<tr>
				<td>设备名称</td>
				<td>设备编码</td>
				<td>预警原因</td>
				<td>预警时间</td>
				</tr>
				<tr>
				<td>柴油机</td>
				<td>Cf8090</td>
				<td>出油口温度过高</td>
				<td>2023/4/13 14:10:10</td>
				</tr>
				<tr>
				<td>柴油机</td>
				<td>Cf8090</td>
				<td>出油口温度过高</td>
				<td>2023/4/13 14:10:10</td>
				</tr>
				<tr>
				<td>柴油机</td>
				<td>Cf8090</td>
				<td>出油口温度过高</td>
				<td>2023/4/13 14:10:10</td>
				</tr>
				<tr>
				<td>柴油机</td>
				<td>Cf8090</td>
				<td>出油口温度过高</td>
				<td>2023/4/13 14:10:10</td>
				</tr>
				<tr>
				<td>柴油机</td>
				<td>Cf8090</td>
				<td>出油口温度过高</td>
				<td>2023/4/13 14:10:10</td>
				</tr>
				
				
			</table>
			
		</div>
		<div class="box1">
			<button>主柴油机</button>
			<button>辅柴油机</button>
			<button>主辅炉锅</button>
			<button>空压机</button>
			<button>燃油加热器</button>
			<button>净油器</button>
			<button>废气锅炉</button>
		</div>
		<div class="box2">
		<h3>传感器01</h3>
		
		<input type="text" value="压力:__________"/>
		<input type="text" value="温度:__________"/>
		<input type="text" value="转速:__________"/>
		<input type="text" value="压力:__________"/>
		<input type="text" value="转速:__________"/>
		<input type="text" value="温度:__________"/>
		</div>
		<div class="box3">
			<div class="box31">
			<p>在线设备 35</p>
			<p>离线设备 02</p>
			</div>
			<div class="box32">
			报警次数：2次<br />
			故障次数：3次<br />
			准确率：82.0%<br />
			</div>
		</div>
		<div class="box4">
			主柴油机
			<div class="ll">
			<ul class="dh" style="font-size: small;">
				<li>燃油积极压力</li>
				<li>重燃燃油温度</li>
				<li>滑油进击压力</li>
				<li>燃油紧急温度</li>
			</ul>
			</div>
	
采样率
    <select>
        <option value="">10k</option>
        <option value="">20k</option>
        <option value="">30k</option>
        <option value="">40k</option>
        <option value="">50k</option>
    </select>
			量程
	<select  >
		<option value="">10k</option>
		<option value="">20k</option>
		<option value="">30k</option>
		<option value="">40k</option>
		<option value="">50k</option>
	</select>
			
			里程
	<select  >
	    <option value="">10k</option>
	    <option value="">20k</option>
	    <option value="">30k</option>
	    <option value="">40k</option>
	    <option value="">50k</option>
	</select>
	<br />
			最大值
    <select  >
        <option value="">10k</option>
        <option value="">20k</option>
        <option value="">30k</option>
        <option value="">40k</option>
        <option value="">50k</option>
    </select>
			最小值
    <select  >
        <option value="">10k</option>
        <option value="">20k</option>
        <option value="">30k</option>
        <option value="">40k</option>
        <option value="">50k</option>
    </select>
			平均值
    <select  >
        <option value="">10k</option>
        <option value="">20k</option>
        <option value="">30k</option>
        <option value="">40k</option>
        <option value="">50k</option>
    </select>
	<img src="C:\Users\28445\Desktop\高英伟\pngsucai_3048055_f00954.png"/>
		</div>
	
	</body>
</html># lunchuan.github.io
