<template>
        <div class="body">
            <div class="left-bar-parent">
                    <button class="new" type="button" data-testid="create-new-document">Create new document</button>
                    <div class="input-area">
                            
                            <input type="text" id="input" class="input" placeholder="Search for documents" value="">
                            
                    </div>
                    <div class="folders">Folders</div>
                    <button class="folder" type="button" data-testid="create-new-document">My Contracts</button>
                    
                     

                   
                    
            </div>
            <div class="site-content">
                <div class="row">
                    <div class="col-md-2"><button class="import" type="button" data-testid="create-new-document">Import documents</button></div>
                    <div class="col-md-2 top-bar">
                            <p class="grey-storage">Storage Usage:</p>
                            <p id="legend">12 of 100</p>
                    </div>
                    <div class="col-md-5 progress-barr ">
                            <div class="w3-progress-container w3-round-xlarge">
                                    <div class="w3-progressbar w3-round-xlarge" style="width:12%"></div>
                            </div>
                    </div>
                    <div class="col-md-3 top-bar">
                        <p class="grey-storage">Last update:</p>
                        <p class="blue-text">a few seconds ago</p>
                    </div>
                </div>
               
                
                    
                    <div class="tab-area">
                        
                            <table>
                                <tr>
                                    <td><h3>Contracts / </h3></td>
                                    <td><h3> Team Contracts / </h3></td>
                                    <td><h3 class="current">Simple Lawfirm</h3></td>
                                </tr>
                            </table>
                            
                            <div class="row" id="tab-row">
                                <div class="col-md-7">
                                        <ul class="nav nav-tabs">
                                                <li class="active nav-item"><a class="nav-item" data-toggle="tab" href="#all">All</a></li>
                                                <li class="nav-item"><a class="nav-item" data-toggle="tab" href="#require">Require action</a></li>
                                                <li class="nav-item"><a  class="nav-item" data-toggle="tab" href="#sign">Signed</a></li>
                                                <li class="nav-item"><a class="nav-item" data-toggle="tab" href="#pending">Pending</a></li>
                                                <li class="nav-item"><a class="nav-item" data-toggle="tab" href="#change">Requested changes</a></li>
                                                <li class="nav-item"><a class="nav-item" data-toggle="tab" href="#dismiss">Dismissed</a></li>
                                              </ul>
                                              
                                </div>
                                <div class="col-md-2 sort-item">
                                        <button class=" filter" type="button" data-testid="create-new-document">Filter</button>
        
                                </div>
                                <div class="col-md-3 sort-item">
                                    <div class="flex sort">
                                        <p class="grey-storage">Sort by:</p>
                                        <p class="blue-text">Contract name:</p>
                                        <p class="blue-text">A</p>
                                        <div class="arrow"><i  class="fas fa-arrow-right blue-text"></i></div>
                                        <p class="blue-text">Z</p>
                                    </div>
                                    
                                </div>
                            </div>
                            <div class="tab-content">
                                <div class="tab-content-one tab-pane fade in active" id="all">
                                    <div class="flex-container">
                                        <div class="flex-container-content">
                                            <div class="flex-container-content-one">
                                                <i class="fas fa-file-export"></i>
                                               
                                                <div class="employee">
                                                        <p class="new-employee">NDA_New Employee</p>
                                                        <button class="add-btn"><i class="fas fa-plus"></i>Add tag</button>
                                                </div>
                                            </div>
                                           
                                        </div>
                                        <div class="flex-container-content created" id="top">
                                            <div class="grey">Created at:</div>
                                            <div class="blue">28 Nov 2018</div>
                                            <div class="grey">Owner:</div>
                                            <div class="blue">Lana Sparks</div>
                                        </div>
                                        <div class="flex-container-content share" id="top">Share with</div>
                                        <div class="flex-container-content" id="top">
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                           
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                            <button class="reminder"><i class="far fa-bell"></i>Add Reminder</button>
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                               <div class="flex-container-content-three">
                                                   <div class="signed">
                                                       <p>Signed<span></span><i class="fas fa-check-circle"></i></p>
                                                       <p class="grey" id="">28 Nov 2018</p>
                                                   </div>
                                                   
                                               </div>
                                            </div>
                                        
                                    </div>
                                                                        <div class="flex-container">
                                        <div class="flex-container-content">
                                            <div class="flex-container-content-one">
                                                <i class="fas fa-file-export"></i>
                                               
                                                <div class="employee">
                                                        <p class="new-employee">NDA_New Employee</p>
                                                        <button class="add-btn"><i class="fas fa-plus"></i>Add tag</button>
                                                </div>
                                            </div>
                                           
                                        </div>
                                        <div class="flex-container-content created" id="top">
                                            <div class="grey">Created at:</div>
                                            <div class="blue">28 Nov 2018</div>
                                            <div class="grey">Owner:</div>
                                            <div class="blue">Lana Sparks</div>
                                        </div>
                                        <div class="flex-container-content share" id="top">Share with</div>
                                        <div class="flex-container-content" id="top">
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                           
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                            <button class="reminder"><i class="far fa-bell"></i>Add Reminder</button>
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                               <div class="flex-container-content-three">
                                                   <div class="signed">
                                                       <p>Signed<span></span><i class="fas fa-check-circle"></i></p>
                                                       <p class="grey" id="">28 Nov 2018</p>
                                                   </div>
                                                   
                                               </div>
                                            </div>
                                        
                                    </div>
                                                                        <div class="flex-container">
                                        <div class="flex-container-content">
                                            <div class="flex-container-content-one">
                                                <i class="fas fa-file-export"></i>
                                               
                                                <div class="employee">
                                                        <p class="new-employee">NDA_New Employee</p>
                                                        <button class="add-btn"><i class="fas fa-plus"></i>Add tag</button>
                                                </div>
                                            </div>
                                           
                                        </div>
                                        <div class="flex-container-content created" id="top">
                                            <div class="grey">Created at:</div>
                                            <div class="blue">28 Nov 2018</div>
                                            <div class="grey">Owner:</div>
                                            <div class="blue">Lana Sparks</div>
                                        </div>
                                        <div class="flex-container-content share" id="top">Share with</div>
                                        <div class="flex-container-content" id="top">
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                           
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                            <button class="reminder"><i class="far fa-bell"></i>Add Reminder</button>
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                               <div class="flex-container-content-three">
                                                   <div class="signed">
                                                       <p>Signed<span></span><i class="fas fa-check-circle"></i></p>
                                                       <p class="grey" id="">28 Nov 2018</p>
                                                   </div>
                                                   
                                               </div>
                                            </div>
                                        
                                    </div>
                                                                        <div class="flex-container">
                                        <div class="flex-container-content">
                                            <div class="flex-container-content-one">
                                                <i class="fas fa-file-export"></i>
                                               
                                                <div class="employee">
                                                        <p class="new-employee">NDA_New Employee</p>
                                                        <button class="add-btn"><i class="fas fa-plus"></i>Add tag</button>
                                                </div>
                                            </div>
                                           
                                        </div>
                                        <div class="flex-container-content created" id="top">
                                            <div class="grey">Created at:</div>
                                            <div class="blue">28 Nov 2018</div>
                                            <div class="grey">Owner:</div>
                                            <div class="blue">Lana Sparks</div>
                                        </div>
                                        <div class="flex-container-content share" id="top">Share with</div>
                                        <div class="flex-container-content" id="top">
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                            <div class="flex-container-content-two">
                                                <i class="fas fa-long-arrow-alt-right"></i>
                                                <i class="fas fa-lock"></i>
                                                <div class="company-details">
                                                    <div class="blue">Other Company LTD</div>
                                                    <div class="grey">James Hamesworth</div>
                                                </div>
                                                
                                            </div>
                                           
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                            <button class="reminder"><i class="far fa-bell"></i>Add Reminder</button>
                                        </div>
                                        <div class="flex-contaner-content" id="top">
                                               <div class="flex-container-content-three">
                                                   <div class="signed">
                                                       <p>Signed<span></span><i class="fas fa-check-circle"></i></p>
                                                       <p class="grey" id="">28 Nov 2018</p>
                                                   </div>
                                                   
                                               </div>
                                            </div>
                                        
                                    </div>
                                </div>
                                <div class="tab-content-two tab-pane fade" id="require"></div>
                                <div class="tab-content-two tab-pane fade" id="sign"></div>
                                <div class="tab-content-two tab-pane fade" id="pending"></div>
                                <div class="tab-content-two tab-pane fade" id="change"></div>
                                <div class="tab-content-two tab-pane fade" id="dismiss"></div>
                                
                            </div>
            </div>
            
    </div>
                    <div class="accordion" id="accordionExample">
                <div class="card">
                  <div class="card-header" id="headingOne">
                    <h2 class="mb-0">
                      <button class="btn btn-link" type="button" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        All
                      </button>
                    </h2>
                  </div>
              
                  <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordionExample">
                    <div class="card-body">
                        <div class="mobile-flex-one">
                                <div class="flex-container-content">
                                        <div class="flex-container-content-one">
                                            <i class="fas fa-file-export"></i>
                                           
                                            <div class="employee">
                                                    <p class="new-employee">NDA_New Employee</p>
                                                    <button class="add-btn"><i class="fas fa-plus"></i>Add tag</button>
                                            </div>
                                        </div>
                                       
                                    </div>
                                    <div class="flex-container-content created" id="top">
                                            <div class="grey">Created at:</div>
                                            <div class="blue">28 Nov 2018</div>
                                            <div class="grey">Owner:</div>
                                            <div class="blue">Lana Sparks</div>
                                        </div>
                        </div>
                        <div class="mobile-flex-two">
                                <div class="flex-container-content mobile-flex-two-item" id="top">
                                        <div class="flex-container-content-two">
                                            <i class="fas fa-long-arrow-alt-right"></i>
                                            <i class="fas fa-lock"></i>
                                            <div class="company-details">
                                                <div class="blue">Other Company LTD</div>
                                                <div class="grey">James Hamesworth</div>
                                            </div>
                                            
                                        </div>
                                        <div class="flex-container-content-two">
                                            <i class="fas fa-long-arrow-alt-right"></i>
                                            <i class="fas fa-lock"></i>
                                            <div class="company-details">
                                                <div class="blue">Other Company LTD</div>
                                                <div class="grey">James Hamesworth</div>
                                            </div>
                                            
                                        </div>
                                       
                                    </div>
                                    <div class="flex-container-content share mobile-flex-two-item-share " id="top">Share with</div>
                        </div>
                        <div class="mobile-flex-three">
                                <div class="flex-contaner-content mobile-flex-two-item" id="top">
                                        <button class="reminder"><i class="far fa-bell"></i>Add Reminder</button>
                                    </div>
                                    <div class="flex-contaner-content  mobile-sign" id="top">
                                           <div class="flex-container-content-three">
                                               <div class="signed">
                                                   <p>Signed<span></span><i class="fas fa-check-circle"></i></p>
                                                   <p class="grey" id="">28 Nov 2018</p>
                                               </div>
                                               
                                           </div>
                                    </div>
                        </div>
                                         
                    </div>
                  </div>
                </div>
                <div class="card">
                  <div class="card-header" id="headingTwo">
                    <h2 class="mb-0">
                      <button class="btn btn-link collapsed" type="button" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        Require action
                      </button>
                    </h2>
                  </div>
                  <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordionExample">
                    <div class="card-body">
                                  </div>
                  </div>
                </div>
                <div class="card">
                  <div class="card-header" id="headingThree">
                    <h2 class="mb-0">
                      <button class="btn btn-link collapsed" type="button" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                        Requested changes
                      </button>
                    </h2>
                  </div>
                  <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordionExample">
                    <div class="card-body">
                                          </div>
                  </div>
                </div>
                <div class="card">
                    <div class="card-header" id="headingThree">
                      <h2 class="mb-0">
                        <button class="btn btn-link collapsed" type="button" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                            Pending
                        </button>
                      </h2>
                    </div>
                    <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordionExample">
                      <div class="card-body">
                                              </div>
                    </div>
                  </div>
                  
              </div>
    
    </div>
</template>
<script>
export default {
    
}
</script>
<style>

</style>