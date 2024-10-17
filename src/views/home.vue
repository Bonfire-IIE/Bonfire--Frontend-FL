<template>

	<!--<< Banner Section Here >>-->
	<section class="banner__section" id="ban1" >
		<div style="margin: auto;">
			<el-row>
				<el-col :offset = "4":span = "2" style="font-weight: bold; font-size: large;">盘古大模型</el-col>
				<el-col :span = "2">
					<a>概览</a>
				</el-col>
				<el-col :span = "2">
					<el-dropdown>
						<span class="el-dropdown-link">
							基础大模型
							<el-icon class="el-icon--right">
								<arrow-down />
							</el-icon>
						</span>
					</el-dropdown>
				</el-col>

			</el-row>
		</div>
		
	</section>

	<section class="feature__section section__padding overhid" id="ban2">
	   <div class="container" style="text-align: center;">
	      
			<div style="width: 100%;   align-items: center;    display: flex;justify-content: center;">	    
				<img src="static/image/brain.png" style="position: relative;">
			</div>
			<p class="ban2-title">Bonfire-FL</p>
			<p style="color: black; text-align: center;">盘古大模型是面向行业的大模型，包含L0中5类基础大模型、L1行业大模型及L2场景模型三层架构</p>
			<el-button round = "true" style="margin-top: 2%; width: 20%; height: 35px;">xxxxxx 立即申请</el-button>
			<el-row style="margin-top: 1%;">
				<el-col :span = "3" :offset = "7">
					<el-button  round = "true" type = "primary" color = "black" style="width: 80%; height: 40px;">专家咨询</el-button>
				</el-col>
				<el-col :span = "3">
					<el-button  round = "true" type = "primary"  style="width: 80%; height: 40px;">控制台</el-button>
				</el-col>
				<el-col :span = "3">
					<el-button  round = "true" type = "primary"  style="width: 80%; height: 40px;">AI Gallery</el-button>
				</el-col>
			</el-row>
			<el-row style="margin-top: 4%;">
				<el-col :span = 5>
					<el-card shadow="hover">
						<template #header>
							<div>高质量数据</div>
						</template>

						<div>联邦LLM架构，联合打造行业数据集</div>
					</el-card>
				</el-col>
				<el-col :span = 5 :offset = 1>
					<el-card shadow="hover">
						<template #header>
							<div>高质量数据</div>
						</template>
						<div>联邦LLM架构，联合打造行业数据集</div>
					</el-card>
				</el-col>
				<el-col :span = 5 :offset = 1>
					<el-card shadow="hover">
						<template #header>
							<div>高质量数据</div>
						</template>

						<div>联邦LLM架构，联合打造行业数据集</div>
					</el-card>
				</el-col>
				<el-col :span = 5 :offset = 1>
					<el-card shadow="hover">
						<template #header>
							<div>高质量数据</div>
						</template>

						<div>联邦LLM架构，联合打造行业数据集</div>
					</el-card>
				</el-col>

			</el-row>
	   </div>
	   
	   
	   
	</section>
	<section class="feature__section section__padding overhid" id="p3">
		<div class="container" >
		   
		      
			<h3 style="color: black; text-align: center; font-weight: bold;">盘古大模型：解决行业难题，释放AI生产力
			</h3>		   

			<img src="../static/image/des_2.png	" style="width: 90%; height: 90%; margin-top: 4%">
		</div>
	</section>
	<section class="feature__section section__padding overhid" id="p3">
		<div class="container" >
		   
		      
			<h3 style="color: black; text-align: center; font-weight: bold;">5大基础大模型，夯实基础能力

			</h3>		   

			<img src="static/image/des.jpg	" style="width: 90%; height: 90%; margin-top: 4%">
		</div>
	</section>
	<footer class="footer-section">
	   
	   <div class="footer-bottom">
	     <div class="container">
	      <div class="footer-bottom-wrap">
	         <p>
	            Copyright &copy; 2024.Company name All rights reserved.
	         </p>
	         <ul class="footer-bottom-link">
	            <li>
	               <a href="#0">
	                  Privacy
	               </a>
	            </li>
	            <li>
	               <a href="#0">
	                  Terms &amp; Conditions
	               </a>
	            </li>
	         </ul>
	      </div>
	     </div>
	   </div>
	</footer>
</template>

<script >
import axios from 'axios'
import { ElRow } from 'element-plus';
import {jsPlumb} from 'jsplumb'

export default {
  data() {
    return{
		
    }
  },

  
}

</script>

<style scoped >
	
	
	
	
	
	#ban1{
		background: white;
		color: black;
		width: 100%;
		padding-top: 8%;
		padding-bottom: 1%;

	}	
	#ban2{
		background: #f5f5f5; 
		width: 100%;

		color: black !important;
	}
	.ban2-title{
		color: #000;
		text-align: center;
		font-size: 40px !important;
		font-weight: bold;
	}
	#p3{
		/* background-image: url("../static/image/p2.jpg"); */
		  /* background-color: rgba(124, 124, 124, 0.8); */
			/* opacity: 0.8; */
		background: #fcfcfc;
		background-position: center center;
		
		/* 背景图不平铺 */
		    
		background-size:cover; background-repeat: no-repeat;
		/* 当内容高度大于图片高度时，背景图像的位置相对于viewport固定 */
		
		/* 让背景图基于容器大小伸缩 */
		/* background-size: cover; */
		
	}	
		
	.ban2-flyfishing-des{
		width: 100%;
	}
	.ban2-function-detail{
		margin-top: 6%;
		width: 130%;
		height: 240px;
		background-color: #d0cece;
		border-radius: 20px;
	}
</style>