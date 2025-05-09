# 介绍 
只需要普通的纹理图片，通过算法生成高度贴图，配合shader生成表面凹凸效果，通过算法生成法线贴图，配合shader生成光照效果 
# 部分代码 
```
Constant Buffer "$Globals" (128 bytes) on slot 0 {
  Vector4 _LightColor0 at 32
  Float _Glossiness at 80
  Float _Metallic at 84
  Float _AOPower at 92
  Vector4 _Color at 96
}
Constant Buffer "UnityPerCamera" (144 bytes) on slot 1 {
  Vector3 _WorldSpaceCameraPos at 64
}
Constant Buffer "UnityLighting" (768 bytes) on slot 2 {
  Vector4 _WorldSpaceLightPos0 at 0
  Vector4 unity_OcclusionMaskSelector at 736
}

```

# 截图 
<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <!-- 第1行 -->
  <img src="https://github.com/user-attachments/assets/ac283797-d70f-449f-8d16-e3ba08246474" width="30%">
  <img src="https://github.com/user-attachments/assets/3ec5811e-5d10-4293-a780-27a59ea7eeda" width="30%">
  <img src="https://github.com/user-attachments/assets/9837a723-6e35-4570-9e6c-b169c66017e4" width="30%">
  <!-- 第2行 -->
  <img src="https://github.com/user-attachments/assets/b855c7df-15be-4d62-a979-d91111b371e3" width="80%">


 <img src="https://github.com/user-attachments/assets/ec3efc09-56ba-48d2-bfc4-f2cbe85e2811" width="30%">
  <img src="https://github.com/user-attachments/assets/a6cfd7bf-0967-44d7-aa33-ba95a2ba91d0" width="30%">
  <img src="https://github.com/user-attachments/assets/d5518e31-f57d-409a-b1f2-c84228df7006" width="30%">
  <!-- 第2行 -->
  <img src="https://github.com/user-attachments/assets/5fda219d-ce6e-4e85-a7a5-4faf45c82bbe" width="80%">
  <!-- 重复至5行 -->
  <!-- ... -->
</div>  

# 联系  

 ## 1 完整版本、工作内推（武汉）  
 
 <img src="https://github.com/user-attachments/assets/16a23a4f-2687-4848-8be7-b39eae562ee1" width="400" height="400"> 

