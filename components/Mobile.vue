<template>
    <div>
        <b-navbar toggleable class="border-bottom" type="dark" variant="">
            <b-navbar-brand href="#">
                 <span class="hold_logo">
                    <span class="logo">
                        <img src="navdot.png" alt="">
                    </span> 
                    <span class="nav_text">Untitled Ui</span>
               </span>
            </b-navbar-brand>

            <b-navbar-toggle target="navbar-toggle-collapse">
            <template #default="{ expanded }">
                <i><img src="navicon.png" alt=""></i>
            </template>
            </b-navbar-toggle>

            <b-collapse id="navbar-toggle-collapse" is-nav>
            <b-navbar-nav class="text-center">
                <b-nav-item class="my-3" href="#">Home</b-nav-item>
                <b-nav-item  href="#" class="my-3"><span class="active_nav">Dashboard</span></b-nav-item>
                <b-nav-item href="#" class="my-3">Projects</b-nav-item>
                <b-nav-item href="#" class="my-3">Tasks</b-nav-item>
                <b-nav-item href="#" class="my-3">Reporting</b-nav-item>
                <b-nav-item href="#" class="my-3">Users</b-nav-item>
            </b-navbar-nav>
            </b-collapse>
        </b-navbar>
         <section class="landing_page px-5">
            <div class="row">
                <div class="col-12" text-left p-0>
                    <h1 class="welcome_text">Welcome back, Olivia</h1>
                    <p class="welcome_text_paragraph">Track, manage and forecast your customers orders.</p>
                </div>
                <div class="col-12 text-left">
                    <button class="btn p-0 m-0">
                        <img src="import.png" alt="">
                    </button>
                      <button class="btn">
                        <img src="add.png" alt="">
                    </button>
                </div>
            </div>
           <div class="row mt-3">
                <div class="col-md-4 mb-4">
                    <div class="card landing_page_card">
                        <div class="card-body">
                            <div class="row">
                                <div class="col">
                                    <h4 class="card_text">Total customers</h4>
                                    <h1 class="mt-3 card_text_2">2,440</h1>
                                    <span><img src="percent.png" alt=""> <span class="percent_text">40% vs last month</span></span>
                                </div>
                                <div class="col text-right">
                                    <span style="cursor:pointer"><img src="dot.png" alt=""></span>
                                    <div class="mt-4 f_line">
                                        <img class="" src="f_line.png" alt="">
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
                 <div class="col-md-4 mb-4">
                    <div class="card landing_page_card">
                        <div class="card-body">
                            <div class="row">
                                <div class="col">
                                    <h4 class="card_text">Members</h4>
                                    <h1 class="mt-3 card_text_2">1,210</h1>
                                    <span>
                                        <img src="percent_down.png" alt=""> 
                                        <span class="percent_text">10% vs last month</span>
                                    </span>
                                </div>
                                <div class="col text-right">
                                    <span style="cursor:pointer"><img src="dot.png" alt=""></span>
                                    <div class="mt-4 f_line">
                                        <img class="" src="f_line2.png" alt="">
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
                 <div class="col-md-4 mb-4">
                    <div class="card landing_page_card">
                        <div class="card-body">
                            <div class="row">
                                <div class="col">
                                    <h4 class="card_text">Active now</h4>
                                    <h1 class="mt-3 card_text_2">316</h1>
                                    <span><img src="percent.png" alt=""> <span class="percent_text">20% vs last month</span></span>
                                </div>
                                <div class="col text-right">
                                    <span style="cursor:pointer"><img src="dot.png" alt=""></span>
                                    <div class="mt-4 f_line">
                                        <img class="" src="f_line.png" alt="">
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-4">
               
                <div class="col-md-12 mb-3">
                    <input type="text" class="border-0 form-control search_inp" placeholder="Search">
                    <img class="search_icon_pos2"  src="search.png" alt="">
                </div>
                 <div class="col-md-12 mb-3">
                    <button class="ml-1 btn custom_btn3"><img class="pr-1" src="filter.png" alt=""> Edit filters</button>
                </div>
                <div class="col-12 mb-2">
                    <button class="btn custom_btn"> All time <img class="pl-2" src="ex.png" alt=""></button>
                    <button class="ml-2 btn custom_btn2"> US, AU, +4 <img class="pl-2" src="ex.png" alt=""></button>
                </div>
            </div>
            <div class="row mt-5 mb-3">
                <div class="card "  style="width:100%">
                    <div class=" ">
                        <table class="table-responsive-lg table table-striped" style="width:100%;">
                            <thead>
                                <tr>
                                <th class="inc_column_width" style="width:30%"><img src="checkboxheader.png" class="pr-2" alt=""> Company <img class="pl-1" src="percent_down.png" alt=""></th>
                                <th style="width:10%">License Use</th>
                                <th style="width:5%" class="hide_column">Status</th>
                                <th style="width:15%" class="hide_column">Users</th>
                                <th style="width:5%">Action</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td >
                                        <span class="f_column">
                                            <img class="f_column_img" src="checkmark.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Catalog</b></span> 
                                                <span class="catalog_link">catalogapp.io</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Customer
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="user1"></span>
                                            <span class="user2"></span>
                                            <span class="user3"></span>
                                            <span class="user4"></span>
                                            <span class="user5"></span>
                                            <span class="user6"></span>
                                        </div>   
                                    </td>
                                    <td>
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <td >
                                        <span class="f_column">
                                            <img class="f_column_img" src="checkmark.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar1.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Circooles</b></span> 
                                                <span class="catalog_link">getcircles.com</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Churned
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="user7"></span>
                                            <span class="users8"></span>
                                            <span class="users9"></span>
                                            <span class="users10"></span>
                                            <span class="users11"></span>
                                            <span class="users12"></span>
                                        </div>   
                                    </td>
                                    <td>
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <td >
                                        <span class="f_column">
                                            <img class="f_column_img" src="checkmark.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar2.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Command+ R</b></span> 
                                                <span class="catalog_link">cmdr.ai</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Customer
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="users13"></span>
                                            <span class="users14"></span>
                                            <span class="users15"></span>
                                            <span class="users16"></span>
                                            <span class="users17"></span>
                                            <span class="users18"></span>
                                        </div>   
                                    </td>
                                    <td>
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <td >
                                         <span class="f_column">
                                            <img class="f_column_img" src="uncheck.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar3.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Hourglass</b></span> 
                                                <span class="catalog_link">hourglass.app</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Customer
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="suser1"></span>
                                            <span class="suser2"></span>
                                            <span class="suser3"></span>
                                            <span class="suser4"></span>
                                            <span class="suser5"></span>
                                            <span class="suser6"></span>
                                        </div>   
                                    </td>
                                    <td >
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <td >
                                        <span class="f_column">
                                            <img class="f_column_img" src="uncheck.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar4.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Layers</b></span> 
                                                <span class="catalog_link">getlayer.io</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Churned
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="user1"></span>
                                            <span class="user2"></span>
                                            <span class="user3"></span>
                                            <span class="user4"></span>
                                            <span class="user5"></span>
                                            <span class="user6"></span>
                                        </div>   
                                    </td>
                                    <td >
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    
                                    <td >
                                        <span class="f_column">
                                            <img class="f_column_img" src="checkmark.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar5.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Quotient</b></span> 
                                                <span class="catalog_link">quotient.co</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Customer
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="user1"></span>
                                            <span class="user2"></span>
                                            <span class="user3"></span>
                                            <span class="user4"></span>
                                            <span class="user5"></span>
                                            <span class="user6"></span>
                                        </div>   
                                    </td>
                                    <td>
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <td >
                                        <span class="f_column">
                                            <img class="f_column_img" src="checkmark.png" alt="">
                                        </span>
                                        <!-- <p class="m-0 p-0"> -->
                                            <span class="pre_box">
                                                <img class="table_img" src="table_avatar6.png" alt="">
                                            </span>
                                            <span class="box">
                                                <span class="catalog"><b >Sisyphus</b></span> 
                                                <span class="catalog_link">sisphus.com</span>
                                            </span>
                                        <!-- </p> -->
                                    </td>
                                    <td>
                                        <div class="control_table_padding">
                                            <input type="range" class="form-control-range" id="formControlRange">
                                        </div>

                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2">
                                            <span class="table_status">
                                            Customer
                                            </span>
                                        </div>
                                    </td>
                                    <td class="hide_column">
                                        <div class="control_table_padding2" style="position:relative">
                                            <span class="user1"></span>
                                            <span class="user2"></span>
                                            <span class="user3"></span>
                                            <span class="user4"></span>
                                            <span class="user5"></span>
                                            <span class="user6"></span>
                                        </div>   
                                    </td>
                                    <td>
                                        <div class="dropdown control_table_padding2">
                                            <button type="button" class="m-0 p-0 btn dropdown-toggle" data-toggle="dropdown">
                                            <img src="icon.png" alt="">
                                            </button>
                                            <div class="dropdown-menu">
                                                <a class="dropdown-item" href="#">View more</a>
                                            </div>
                                        </div>
                                    </td>
                                </tr>
                            </tbody>
                        </table>

                    </div>
                    <div class="card-footer bg-white">
                       <div class="d-flex justify-content-between">
                           <button class="btn">
                               <img src="arrowleft.png" alt="">
                           </button>
                           <span class="pagination_text pt-2" style="box-sizing:border-box;display:inline-block">
                               Page 1 of 10
                           </span>
                           <button class="btn">
                               <img src="arrowright.png" alt="">
                           </button>
                       </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
export default {
    
}
</script>

<style scoped>
  nav {
        position: relative;
    }
    .nav_text {
        color: #101828;
    }
     .logo {
        text-align: center;
        box-sizing: border-box !important;
        width: 32px !important;
        height: 32px !important;
        background: linear-gradient(180deg, #FFFFFF 0%, #D0D5DD 100%), #FFFFFF;
        border: 0.3px solid #D0D5DD;
        box-sizing: border-box;
        border-radius: 8px;
        display: inline-block !important;
        margin: 0;
        padding: 0;
    }
    .icon {
        width: 28px;
    }
    .px-5 {
        padding-left: 2rem !important;
        padding-right: 2rem !important;
    }
    .navbar-dark .navbar-nav .nav-link {
        font-weight: 500 !important;
        color: #344054 !important;
        font-size: 13px !important;
        line-height: 0 !important;
        font-style: normal !important;
    }
    .active_nav {
        width: 83px !important;
        height: 38px !important;
        border-radius: 6px !important;
        background: #F9FAFB !important;
        padding: 8px 12px 8px 12px;
    }
    .btn:focus {
        outline: none !important;
        box-shadow: none !important;
    }
    .nav_design {
         width: 129px !important;
        /*height: 36px !important; */
        border-radius: 8px !important;
        padding: 8px 6px 10px 6px !important;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);box-sizing: border-box;
        background: #FFFFFF;margin: 0px 0px;display: inline-block !important;
        text-align: center !important;
        font-size: 13px !important;
        font-weight: 500 !important;
        color: #344054 !important;
        border: 1px solid #D0D5DD;
        margin: 10px 0px !important;
         /* width: 83px !important; */
        height: 38px !important;
        /* border-radius: 6px !important; */
        /* background: #F9FAFB !important; */
        padding: 8px 12px 8px 12px;
    }
    .avatar {
        width: 40px !important;
        height: 40px !important;
        border-radius: 200px !important;
        flex-grow: 0;
        margin: 0px 0px;
    }
    .pagination_text {
        font-family: Inter;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */


        /* Gray/700 */

        color: #344054;
    }
    .body {
        font-family: 'Inter', sans-serif !important;
    }

    .sub_navbar {
        height: 70px !important;
        overflow: hidden !important;
        box-sizing: border-box !important;
    }
    .search_inp {
        
         border:  1px solid rgba(208, 213, 221, 1) !important;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05) !important;
        border-radius: 9px !important;
        padding: 5px 7px 5px 39px !important;
        width: 100% !important;
    }
    .search_icon_pos2 {
        position: absolute;
        top: 26%;
        left: 7%;
    }
    .nav_width {
       width: 30% !important;

    }
    .landing_page {
        padding-top: 80px !important;
    }
    .welcome_text {
        font-weight: 500 !important;
        font-style: normal !important;
        font-size: 30px !important;
        line-height: 38px !important;
        color:  rgba(16, 24, 40, 1) !important;
    }
    .welcome_text_paragraph {
        font-weight: 500 !important;
        font-style: normal !important;
        font-size: 15px !important;
        line-height: 24px !important;
        color:  rgba(102, 112, 133, 1) !important;
    }
    .landing_page_card {
        border: 1px solid #EAECF0 !important;
        box-sizing: border-box !important;
        box-shadow: 0px 1px 3px rgba(16, 24, 40, 0.1), 0px 1px 2px rgba(16, 24, 40, 0.06) !important;
        border-radius: 8px !important;
        background: #FFFFFF !important;
    }
    .card_text {
        font-weight: 500 !important;
        font-style: normal !important;
        font-size: 14px !important;
        line-height: 24px !important;
        color: rgba(16, 24, 40, 1) !important;
    }
    .card_text_2 {
         font-weight: 600 !important;
        font-style: normal !important;
        font-size: 36px !important;
        line-height: 44px !important;
        color: #101828 !important;
        letter-spacing: -0.02em !important;line-height: 44px !important;
    }
    .percent_text {
        font-style: normal !important;
        font-weight: 500 !important;
        font-size: 14px !important;
        line-height: 20px !important;color: #667085 !important;
    }
    /* .f_line {
        width: 128px !important;
        height: 64px !important;
        border: 2px solid #12B76A !important;

        background: linear-gradient(180deg, rgba(255, 255, 255, 0) 64.12%, #FFFFFF 100%) !important;
    } */
    .custom_btn {
        width: 110px !important;
        /* height: 40px !important; */
        border-radius: 8px !important;
        /* padding: 10px 16px 10px 16px; */
        border: 1px solid #F9F5FF !important;
        background: #F9F5FF !important;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05) !important;
        box-sizing: border-box !important;
        color: #6941C6;
        font-family: Inter;
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 20px;

    }
     .custom_btn2 {
        width: 133px !important;
        /* height: 40px !important; */
        border-radius: 8px !important;
        /* padding: 10px 16px 10px 16px; */
        border: 1px solid #F9F5FF !important;
        background: #F9F5FF !important;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05) !important;
        box-sizing: border-box !important;
        color: #6941C6;
        font-family: Inter;
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 20px;

    }
    .custom_btn3 {
          width: 100% !important;
        height: 40px !important;
        border-radius: 8px !important;
        padding: 10px 16px 10px 16px;
        border: 1px solid #D0D5DD;
        background: #FFFFFF;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05) !important;
        box-sizing: border-box !important;
        color: #6941C6;
      font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        text-align: center !important;
    }
    th {
        font-family: Inter;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 18px;
        /* identical to box height, or 150% */


        /* Gray/500 */

        color: #667085;
    }
    .pre_box {
        width: 40px !important;
        height: 60px !important;
        overflow: hidden !important;
        position: relative;
        display: inline-block !important;
    }
    .f_column{
         width: 40px !important;
        height: 60px !important;
        overflow: hidden !important;
        position: relative;
        display: inline-block !important;
    }
    .f_column_img {
        position: absolute !important;
        top: 17px !important;
    }
    .table_img {
        position: absolute;
        width: 40px;
        height: 40px;
        left: 0;
        top: 11px;
    }
    .catalog {
        font-family: Inter;
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */


        /* Gray/900 */

        color: #101828;
    }
    .catalog_link {
        font-family: Inter;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */


        /* Gray/500 */

        color: #667085;
    }
    .box {
        overflow: hidden !important;
       width: 107px !important;
        height: 56px !important;
        /* background: red; */
        display: inline-block !important;
    }
    th,td {
        box-sizing: border-box !important;
    }
    .form-control-range {
        background: #7F56D9 !important;
        border-radius: 4px !important;
    }
    .table_status {
        width: 73px !important;
        height: 22px !important;
        border-radius: 16px !important;
        padding: 0px 8px;
        background: #ECFDF3;
        font-family: Inter;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 18px;
        /* identical to box height, or 150% */
        margin: 0;
        text-align: center;

        /* Success/700 */

        color: #027A48;

    }
    .control_table_padding {
        padding-top: 20px !important;
    }
     .control_table_padding2 {
        padding-top: 14px !important;
    }
    .user1 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;display: inline-block;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/user1.png') !important;
        background-repeat: no-repeat !important;
    }
    .user2 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 21px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/user2.png') !important;
        background-repeat: no-repeat !important;
    }
    .user3 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 42px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/user3.png') !important;
        background-repeat: no-repeat !important;
    }
    .user4 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 62px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/user4.png') !important;
        background-repeat: no-repeat !important;
    }
    .user5 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 84px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/user5.png') !important;
        background-repeat: no-repeat !important;
    }
    .user6 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 104px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/5plus.png') !important;
        background-repeat: no-repeat !important;
    }
    .user7 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 0;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users7.png') !important;
        background-repeat: no-repeat !important;
    }
    .users8 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 21px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users8.png') !important;
        background-repeat: no-repeat !important;
    }
     .users9 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 42px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users9.png') !important;
        background-repeat: no-repeat !important;
    }
    .users10 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 62px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users10.png') !important;
        background-repeat: no-repeat !important;
    }
    .users11 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
         left: 84px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users11.png') !important;
        background-repeat: no-repeat !important;
    }
    .users12 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        left: 104px;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users12.png') !important;
        background-repeat: no-repeat !important;
    }
    .users13 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        top: 14px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users11.png') !important;
        background-repeat: no-repeat !important;
    }
    .users14 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        top: 14px;
        left: 21px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users13.png') !important;
        background-repeat: no-repeat !important;
    }
    .users15 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        top: 14px;
         left: 42px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users144.png') !important;
        background-repeat: no-repeat !important;
    }
    .users16 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        top: 14px;
        left: 62px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users10.png') !important;
        background-repeat: no-repeat !important;
    }
    .users17 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        top: 14px;
        left: 84px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users15.png') !important;
        background-repeat: no-repeat !important;
    }
    .users18 {
        width: 30px !important;
        height: 40px !important;
        border-radius: 200px !important;
        display: inline-block;
        position: absolute;
        top: 14px;
        left: 104px;
        /* border: 1.5px solid #FFFFFF !important; */
        background: url('~assets/users16.png') !important;
        background-repeat: no-repeat !important;
    }
    .about_text {
        font-family: Inter;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */


        /* Gray/900 */

        color: #101828;
    }
    .about_text_p {
        font-family: Inter;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 20px;
        margin: 0;
        color: #667085;
    }
    .btn_footer {
        /* White */

        background: #FFFFFF;
        /* Gray/300 */

        border: 1px solid #D0D5DD;
        box-sizing: border-box;
        /* Shadow/xs */

        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);
        border-radius: 6px;
    }
    .footer_text {
        font-family: Inter;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */


        /* Gray/700 */

        color: #344054;
    }

    @media screen and (max-width:877px) {
       .search_icon_pos2 {
            position: absolute;
            top: 26%;
            left: 3%;
        }  
    }
     @media screen and (max-width:640px) {
      .hide_column {
          display: none !important;
      }
      .f_column{
          width: 24px !important;
      }
       .search_icon_pos2 {
            position: absolute;
            top: 26%;
            left: 7%;
        }  
    }
    @media screen and (max-width: 400px) {
        .inc_column_width {
            width: 58px !important;
        }
    }
</style>