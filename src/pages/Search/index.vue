<template>
  <div>
      <!-- bread  -->
      <div class="bread">
         <ul class="fl sui-breadcrumb">
             <li>
                 <a href="#">全部结果</a>
             </li>
         
         </ul>
         <ul class="fl sui-tag">
             <li class="with-x">手机</li>
             <li class="with-x">iphone</li>
             <li class="with-x">华为</li>
             <li class="with-x">OPPO</li>
         </ul>
      </div>
  </div>
</template>

<script>
export default {
      
}
</script >

<style lang='less' scoped>
   .bread{
       float:left;
      
     
       .sui-breadcrumb{
        //    padding:3px 15px;
        //    margin:0;
        //    font-weight:400;
        //    border-radius:3px;
        //    float:left;
           background-color: #62bff3;
        
       }

        li{
            display:inline-block;
            line-height:18px;
        }
        a{
            color:#666;
            text-decoration:none;
            &:hover{
                color:#62bff3;
            }

        }
        .sui-tag{
             float:left;
             background-color: #666;

        }

   }
   
</style>