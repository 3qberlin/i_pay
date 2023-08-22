# icons

# 01 cart
<span class="material-icons">
shopping_cart
</span>

# 02 member
<span class="material-icons">
person
</span>

# 03 more
<span class="material-icons">
arrow_right
</span>

# 04 male
<span class="material-icons">
male
</span>

# 05 female
<span class="material-icons">
female
</span>

# 06 menu
<span class="material-icons">
menu
</span>

# 07 left
<span class="material-icons">
chevron_left
</span>

# 08 right
<span class="material-icons">
chevron_right
</span>

# 09 favorite
<span class="material-icons">
favorite_border
</span>

# 10 sms  <!-- 第10號找不到，先用這個擋一下 -->
<span class="material-icons-outlined">
sms
</span>


# spacing
## 這裡使用0=0, a=1, b=2, c=3, d=4, e=5, f=6, g=7, h=8, i=9 作為變數名稱
## 個位數使用限制為數字0-9，十位與百位數則使用英文大寫。

  0: 0,                 <!-- 間距0 -->
  4: $spacer * 0.25,    <!-- 間距4 -->
  8: $spacer * 0.5,     <!-- 間距8 -->
  A2: $spacer * 0.75,   <!-- 間距12 -->
  A6: $spacer,          <!-- 間距16 -->
  A8: $spacer * 1.125,  <!-- 間距18 -->
  B0: $spacer * 1.25,   <!-- 間距20 -->
  B4: $spacer * 1.5,    <!-- 間距24 -->
  C2: $spacer * 2,      <!-- 間距32 -->
  D0: $spacer * 2.5,    <!-- 間距40 -->
  D8: $spacer * 3,      <!-- 間距48 -->
  F4: $spacer * 3.375,  <!-- 間距64 -->
  G2: $spacer * 4.5,    <!-- 間距72 -->
  I6: $spacer * 6,      <!-- 間距96 -->
  AB0: $spacer * 7.5,   <!-- 間距120 -->
  AB4: $spacer * 7.75,  <!-- 間距124 -->
  AD0: $spacer * 8.75,  <!-- 間距140 -->


# font-sizing
## 同spacing邏輯
  D8: $font-size-base * 3,     <!-- 間距48 -->
  D0: $font-size-base * 2.5,   <!-- 間距40 -->
  C2: $font-size-base * 2,     <!-- 間距32 -->
  B8: $font-size-base * 1.75,  <!-- 間距28 -->
  B4: $font-size-base * 1.5,   <!-- 間距24 -->
  B0: $font-size-base * 1.25,  <!-- 間距20 -->
  A6: $font-size-base,         <!-- 間距16 -->
  A4: $font-size-base * 0.875, <!-- 間距14 -->
  A2: $font-size-base * 0.75,  <!-- 間距12 -->

# color
## 以main取代primary文字
## 以小駝峰式命名

  主色：main
  主色深：mainDark
  主色淺：mainLight
  主色透明：mainTransparent

  次主色：secondary
  次主色深：secondaryDark
  次主色淺：secondaryLight

  配色橘：orange
  配色膚色：skin
  配色藍：blueLight

  灰淺+：grayLighter
  灰淺：grayLight
  灰：gray
  灰深：grayDark
  灰深+：grayDarker
  灰深++：grayDarkest
 
  Example:
  bg-mainDark , text-grayDark, border-orange
