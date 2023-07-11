
  <script setup >
  import mo from '../components/p/mo.vue';
  import mo2 from  '../components/p/mo2.vue';
 import mo3 from '../components/p/mo3.vue';
  import mo4 from '../components/p/mo4.vue';
  import mo5 from '../components/p/mo5.vue'
  </script>
  <template>
      <mo/>
      <mo2/>
      <div class="bocuc">
     <mo3/>
     <mo4/>
     <mo5/>
    </div>
   </template>
 <style>
body{
    margin: 0;
    background-color: #ebebeb;
    font-family: Tahoma,sans-serif,Helvetica,Arial;
}
.bocuc{
  display: flex;
  flex-direction: column;
  background-color:#f9f9f9;
  border: none;
  width: 950px;
  margin-left: 200px;
}
</style>
 