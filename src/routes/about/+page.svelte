<script lang="ts">
	import { people } from '$lib/people';
</script>

<main class="container">
	<h1>About</h1>
	<p>
		Welcome to This or That! This is a simple web app that allows you to compare values of two
		different products. Normally, when products are priced similarly or have sales that are hard to
		compare, we often struggle and waste a lot of time deciding which one to buy. This app aims to
		help you make a decision by using AI to scan the products and compare them for you.
	</p>

	<br />

	<p>
		โครงงาน “ระบบเปรียบเทียบราคาสินค้าในร้านด้วยปัญญาประดิษฐ์ (This or That)” เป็นการพัฒนาเว็บแอปพลิเคชันที่ใช้เทคโนโลยี AI เพื่อช่วยผู้บริโภคในการเปรียบเทียบราคาสินค้า โปรโมชั่น และข้อมูลที่เกี่ยวข้องได้อย่างรวดเร็วและแม่นยำ ระบบนี้ถูกออกแบบมาเพื่อแก้ปัญหาความซับซ้อนในการเลือกซื้อสินค้า ซึ่งมักเกิดจากตัวเลือกที่หลากหลายและเงื่อนไขโปรโมชั่นที่ซับซ้อน

		โครงงานนี้ใช้ AI Vision API ในการประมวลผลภาพสินค้า และพัฒนาเว็บแอปพลิเคชันโดยใช้ React พร้อมออกแบบ UX/UI ผ่าน Figma การดำเนินโครงงานประกอบด้วยการออกแบบระบบ การพัฒนาแอปพลิเคชัน การทดสอบและประเมินผล เพื่อให้ได้ระบบที่สามารถช่วยให้ผู้บริโภคเลือกซื้อสินค้าได้สะดวกขึ้น ประหยัดเวลา และตัดสินใจได้อย่างมั่นใจยิ่งขึ้น

		ผลที่คาดว่าจะได้รับคือ ระบบที่ช่วยลดเวลาและความซับซ้อนในการตัดสินใจซื้อสินค้า พร้อมทั้งเพิ่มประสิทธิภาพในการเลือกสินค้าที่คุ้มค่าที่สุดสำหรับผู้บริโภค

	</p>

	
	<br />

	<p>
		This or That is made with SvelteKit framework, SCSS for styling, and GPT-4o vision api for image
		processing. Programming languages used were Svelte, TypeScript, SCSS, and markdown for text.
	</p>

	

	
</main>

<style lang="scss">
	.team {
		display: grid;
		grid-template-columns: repeat(5, 1fr);
		gap: 1rem;

		.person {
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			border-radius: 5px;
			gap: 0.5rem;
		}

		img {
			width: 100%;
			border-radius: 5px;
		}
	}
</style>
