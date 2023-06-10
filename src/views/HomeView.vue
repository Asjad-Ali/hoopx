<template>
  
   <HeaderVue />

   <div class="p-4">
      
      <div class="p-4 border-gray-200 rounded-lg dark:border-gray-700 mt-14 content_body">
         <!-- <div class="text-white pb-8 text-4xl mb-5">Dashboard</div> -->
         <div class="grid grid-cols-1 gap-2 mb-4" style="    margin-top: 95px;">
            <div class="rounded bg-gray-50" style="background-color: #222121;">
               <div class="pt-5 pl-5 text-xl text-white">Hoopx</div>
               <div class="flex">
                  <div class="text-white" style="width: 50%;border-right: 1px solid #676767 ;">
                     <div class="text-white" style="width: 45%;float: left;">
                        <PieChart />
                     </div>
                     <div class="text-white" style="width: 55%;float: left;">
                        <table class="activity_table token_table">
                           <thead>
                              <tr>
                                 <th>Token</th>
                                 <th>Amount($)</th>
                                 <th>Price Change</th>
                              </tr>
                           </thead>
                           <tbody>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/doge.svg" alt=""></div>
                                       <div>USD </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow.svg" alt=""></div>
                                       <div>1.5% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/eth.svg" alt=""></div>
                                       <div>ETH </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow_down.svg" alt=""></div>
                                       <div>0.0% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/btc.svg" alt=""></div>
                                       <div>BTC </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow.svg" alt=""></div>
                                       <div>1.5% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/ltc.svg" alt=""></div>
                                       <div>XRP </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow_down.svg" alt=""></div>
                                       <div>2.32% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/eth.svg" alt=""></div>
                                       <div>LTC </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow.svg" alt=""></div>
                                       <div>2.32% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/ltc.svg" alt=""></div>
                                       <div>MDT </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow.svg" alt=""></div>
                                       <div>2.32% </div>
                                    </div>
                                 </td>
                              </tr>
                              <tr>
                                 <td>
                                    <div class="flex justify-center gap-2">
                                       <div><img src="../assets/images/eth.svg" alt=""></div>
                                       <div>PEPE </div>
                                    </div>
                                 </td>
                                 <td>
                                    77654
                                 </td>
                                 <td>
                                    <div class="flex justify-center items-center gap-1">
                                       <div><img src="../assets/images/arrow_down.svg" alt=""></div>
                                       <div>2.32% </div>
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
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/lastevalicon.svg" alt="">
                     </div>
                     <div class="text-white">
                        <p class="smal_txt">Last Valuation</p>
                        <p>$5.367</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/apricon.svg" alt="">
                     </div>                     
                     <div class="text-white">
                        <p class="smal_txt">APR</p>
                        <p>2.367%</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/tvlicon.svg" alt="">
                     </div>                     
                     <div class="text-white">
                        <p class="smal_txt">TVL</p>
                        <p>$468.0000</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/activeusericon.svg" alt="">
                     </div>                     
                     <div class="text-white">
                        <p class="smal_txt">Active Users</p>
                        <p>$12345</p>
                     </div>
                  </div>
              </div>
            </div>
         </div>
         <div class="grid grid-cols-2 :grid-cols-1 gap-6 mb-4">
            <div class="flex rounded flex-col" style="background-color: #222121;">
               <div class="flex justify-between items-center">
                  <div class="py-5 pt-8 pl-5 text-xl text-white">My Stats</div>
                  <!-- <div class="account_detail">Account</div> -->
               </div>
               <div class="flex items-center">
                  <div class="pink_box">
                     <img src="../assets/images/maskgroup.svg" alt="">
                  </div>
                  <div class="text-white">0x75b91....03kgt5
                     <img class="inline ms-2" src="../assets/images/shareicon.svg" alt="">
                  </div>
               </div>
               <p class="smal_txt_color pl-4 text-base">Balance</p>
               <div class="flex items-center">
                  <p class="pl-4 text-white py-3 text-xl">$123456</p>
                  <p class="smal_txt_color pl-4 text-base">2.305  Hoopx</p>
               </div>
               <div class="flex">
                  <button class="text-green-300">Deposit</button>
                  <button class="text-purple-600">Withdraw</button>
               </div>
               <div class="border_bottom" style="width: 92%;"></div>
              <div class="flex justify-between mr-10">
                  <div class="flex items-center">
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/apricon.svg" alt="">
                     </div>
                     <div class="text-white">
                        <p class="smal_txt">Total earnings</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/tvlicon.svg" alt="">
                     </div>
                     <div class="text-white">
                        <p class="smal_txt">Total Withdraw</p>
                        <p>$12345</p>
                     </div>
                  </div>
                  <div class="flex items-center">
                     <div class="footer_box flex items-center justify-center">
                        <img src="../assets/images/totalerningicon.svg" alt="">
                     </div>
                     <div class="text-white">
                        <p class="smal_txt">Your APR</p>
                        <p>$12345</p>
                     </div>
                  </div>
              </div>
            </div>
            <div class=" rounded " style="background-color: #222121;">
               <div class="py-5 pt-8 pl-5 text-xl text-white">Latest Research</div>
               <div class="ps-5">
                  <img src="../assets/images/Player_.svg" alt="">
               </div>
               <h6 class="text-white ml-5 my-4 text-sm">How to empower your trading strategy with AI?</h6>
               <p class="text-white ml-5 text-xs" style="color: #a8a8a8;">For the years people have been trying to develop there own strategy for</p>
               <button class="float-right text-white mt-8 mr-7">Read more</button>
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
                           <div><img src="../assets/images/doge.svg" alt=""></div>
                           <div>DOG</div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status bg-gray-700">Closed</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <img src="../assets/images/arrow.svg" alt="">
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div><img src="../assets/images/eth.svg" alt=""></div>
                           <div>ETH </div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status bg-green-300">Open</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <img src="../assets/images/arrow_down.svg" alt="">
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div><img src="../assets/images/avax.svg" alt=""></div>
                           <div>AVX</div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status bg-gray-700">Closed</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <img src="../assets/images/arrow_down.svg" alt="">
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div><img src="../assets/images/eth.svg" alt=""></div>
                           <div>ETH </div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status bg-green-300">Open</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <img src="../assets/images/arrow.svg" alt="">
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div><img src="../assets/images/doge.svg" alt=""></div>
                           <div>DOG</div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status bg-gray-700">Closed</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <img src="../assets/images/arrow.svg" alt="">
                           <div>1.5% </div>
                        </div>
                     </td>
                     <td>1961</td>
                  </tr>
                  <tr>
                     <td>
                        <div class="flex justify-center gap-2">
                           <div><img src="../assets/images/btc.svg" alt=""></div>
                           <div>BTC </div>
                        </div>
                     </td>
                     <td>
                        <div class="red_status bg-green-300">Open</div>
                     </td>
                     <td>1961</td>
                     <td>456 </td>
                     <td>67879</td>
                     <td>
                        <div class="flex justify-center items-center gap-1">
                           <img src="../assets/images/arrow_down.svg" alt="">
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
