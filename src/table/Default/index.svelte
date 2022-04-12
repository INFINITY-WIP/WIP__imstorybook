<script>
  let data = {
    
  }
</script>

<div id="popContent" class="w-[900px] overflow-hidden bg-white relative left-1/2 -translate-x-1/2 shadow-[0px_5px_15px_rgba(0,0,0,0.5)] rounded-[4px]">
	<div class="px-[24px] pt-[24px]">
		<div class="text-[20px]">적립금 상세 처리내역</div>
	</div>
	<div class="px-[24px] overflow-hidden mt-[24px] mb-[82px]">
		<div class="overflow-x-scroll w-full border border-[#ddd]">
			<div class="grid gap-x-[14px] grid-cols-[minmax(130px,1fr),minmax(65px,1fr),minmax(200px,1fr),minmax(126px,1fr),minmax(70px,1fr),minmax(83px,1fr)] grid-rows-[34px] items-center border-[#ddd] border-b text-[#757575] bg-[#fafafa]">
				<div class="table__mileage-cell">일자</div>
				<div class="table__mileage-cell text-center">이름(닉네임)</div>
				<div class="table__mileage-cell">사유/내용</div>
				<div class="table__mileage-cell">관련주문</div>
				<div class="table__mileage-cell text-right">지급/차감</div>
				<div class="table__mileage-cell">처리자</div>
			</div>
			<div class="grid gap-x-[14px] grid-cols-[minmax(130px,1fr),minmax(65px,1fr),minmax(200px,1fr),minmax(126px,1fr),minmax(70px,1fr),minmax(83px,1fr)] border-[#ddd] border-b last:border-b-0">
				<div class="table__mileage-cell text-[#212121]">2022-01-27 20:43</div>
				<div class="table__mileage-cell text-[#212121] text-center">홍길동</div>
				<div class="table__mileage-cell text-[#212121]">
					<p>
						상품구매시 할인 차감<br/>
						[2021202020202]
					</p>
				</div>
				<div class="table__mileage-cell text-[#212121]">
					Classic Topper 외 2건
				</div>
				<div class="table__mileage-cell text-[#212121] text-right">
					-500,000원
				</div>
				<div class="table__mileage-cell text-[#212121]">
					시스템 자동발급
				</div>
			</div>
		</div>
	</div>
</div>

<style>
  table {
    border-radius: 0;
  }
</style>