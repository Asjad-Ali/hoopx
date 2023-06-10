<template>
  
   <HeaderVue />

   <div class="p-4">
      
      <div class="p-4 border-gray-200 rounded-lg dark:border-gray-700 mt-14 content_body">
         <!-- <div class="text-white pb-8 text-4xl mb-5">Dashboard</div> -->
         <div class="grid grid-cols-1 gap-2 mb-4" style="    margin-top: 95px;">
            <div class="rounded bg-gray-50" style="background-color: #222121;">
               <div class="pt-8 pl-5 text-xl text-white">Hoopx</div>
               <div class="flex">
                  <div class="text-white" style="width: 50%;border-right: 1px solid #676767 ;">
                     <div class="text-white" style="width: 45%;float: left;"><PieChart /></div>
                     <div class="text-white" style="width: 55%;float: left;">
                        <table class="activity_table token_table">
                           <thead>
                              <tr>
                                 <th>Token</th>
                                 <th>Amount</th>
                                 <th>Price</th>
                              </tr>
                           </thead>
                           <tbody>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div class="circle"></div>
                                       <div>DOGE </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div class="circle" style="height: 15px;width:15px"></div>
                                       <div>1.5% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div class="circle"></div>
                                       <div>DOGE </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div class="circle" style="height: 15px;width:15px"></div>
                                       <div>1.5% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div class="circle"></div>
                                       <div>DOGE </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div class="circle" style="height: 15px;width:15px"></div>
                                       <div>1.5% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div class="circle"></div>
                                       <div>DOGE </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div class="circle" style="height: 15px;width:15px"></div>
                                       <div>1.5% </div>
                                    </div>
                                 </td>
                              </tr>
                           </tbody>
                        </table>
                     </div>
                  </div>
                  <div class="text-white mx-3" style="width: 50%;"><FilterChart /></div>
               </div>






               <div class="flex justify-between mx-10 mr-20">
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
              </div>
            </div>
         </div>
         <div class="grid grid-cols-2 gap-6 mb-4">
            <div class="flex rounded flex-col" style="background-color: #222121;">
               <div class="flex justify-between items-center">
                  <div class="py-5 pt-8 pl-5 text-xl text-white">My Stats</div>
                  <div class="account_detail">Account</div>
               </div>
               <div class="flex items-center">
                  <div class="pink_box"></div>
                  <div class="text-white">0x75b91....03kgt5</div>
               </div>
               <p class="smal_txt_color pl-4 text-base">Balance</p>
               <div class="flex items-center">
                  <p class="pl-4 text-white py-3 text-xl">$123456</p>
                  <p class="smal_txt_color pl-4 text-base">2.305  Hoopx</p>
               </div>
               <div class="flex">
                  <button>Deposit</button>
                  <button>Withdraw</button>
               </div>
               <div class="border_bottom" style="width: 92%;"></div>
              <div class="flex justify-between mr-10">
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box"></div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
              </div>
            </div>
            <div class=" rounded " style="background-color: #222121;">
               <div class="py-5 pt-8 pl-5 text-xl text-white">Latest Research</div>
               <div class="tranding_video"></div>
               <h6 class="text-white ml-5 mt-1 text-sm">How to empower your trading strategy with AI?</h6>
               <p class="text-white ml-5 text-xs" style="color: #a8a8a8;">For the years people have been trying to develop there own strategy for</p>
               <button class="float-right mt-8 mr-7">Read more</button>
            </div>
         </div>
         <div class="flex justify-center mb-4 rounded flex-col " style="background-color: #222121;">
            <div class="py-5 pt-8 pl-5 text-xl text-white">Latest Activities</div>
            <table class="activity_table">
               <thead>
                  <tr>
                     <th>Token</th>
                     <th>Position</th>
                     <th>Price</th>
                     <th>Value</th>
                     <th>Amount</th>
                     <th>PNL</th>
                     <th>Date</th>
                  </tr>
               </thead>
               <tbody>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div class="circle"></div>
                           <div>DOGE </div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status">Closed</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <div class="circle" style="height: 15px;width:15px"></div>
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div class="circle"></div>
                           <div>DOGE </div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status">Closed</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <div class="circle" style="height: 15px;width:15px"></div>
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                 
               </tbody>
            </table>
         </div>
      </div>
   </div>

</template>

<script setup>
import HeaderVue from "../components/Header.vue";
import PieChart from "../components/PieChart.vue";
import FilterChart from "../components/FilterChart.vue";

</script>
