<template>
    <header id="site-header" class="z-50 pl-4 md:px-4 shadow bg-white  sm:hover:bg-white">
        <div class="flex mx-auto items-center h-full justify-between container-main">
            <span class="block site-logo z-40">
                <a href="/" aria-label="Site logo links to homepage">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 122 20" stroke="none">
                    <path d="M4365.8,1109.372h5.77v15.15h3.85v-15.15h4.81v-3.85H4365.8Z" transform="translate(-4282.213 -1105.062)"></path>
                    <path d="M4305.9,1114.182v10.34h4v-8.75l5-5.25,5,5.25v8.75h4v-10.34l-9-9.12Z" transform="translate(-4282.213 -1105.062)"></path>
                    <path d="M4295.213,1112.522h-9v-7h-4v19h4v-8h9v8h4v-19h-4Z" transform="translate(-4282.213 -1105.062)"></path>
                    <path d="M4359.374,1114.593a7.581,7.581,0,0,0-1.981-.978c-.593-.215-1.221-.417-1.848-.6l-1.421-.46a3.425,3.425,0,0,1-.954-.446,1.51,1.51,0,0,1-.476-.484,1.079,1.079,0,0,1-.19-.719l0-.053a1.616,1.616,0,0,1,.194-.824,2.069,2.069,0,0,1,.545-.575,2.844,2.844,0,0,1,.827-.374,3.477,3.477,0,0,1,.9-.13,6.362,6.362,0,0,1,2.788,1.084l.39.273,2.846-2.694-.409-.326a9.489,9.489,0,0,0-1.508-.983,8.852,8.852,0,0,0-2.462-.8,10.513,10.513,0,0,0-1.5-.12,9.1,9.1,0,0,0-2.286.293,6.774,6.774,0,0,0-2.2.968,5.282,5.282,0,0,0-1.683,1.75,4.94,4.94,0,0,0-.044,4.847,4.98,4.98,0,0,0,1.372,1.62,7.557,7.557,0,0,0,1.834,1c.594.225,1.222.436,1.8.6l.413.134,1.158.36a4.99,4.99,0,0,1,1.076.5,1.85,1.85,0,0,1,.593.566,1.915,1.915,0,0,1,0,1.692,2.18,2.18,0,0,1-.608.638,2.922,2.922,0,0,1-.92.422,4.282,4.282,0,0,1-.948.124,4.5,4.5,0,0,1-1.367-.225,6.007,6.007,0,0,1-1.149-.518l-.564-.445-3.187,2.334.38.369a5.92,5.92,0,0,0,.583.5,7.745,7.745,0,0,0,1.6.906,8.6,8.6,0,0,0,1.786.522,10.322,10.322,0,0,0,1.805.173h0a9.547,9.547,0,0,0,2.447-.321,6.835,6.835,0,0,0,2.233-1.041,5.189,5.189,0,0,0,2.282-4.391A4.823,4.823,0,0,0,4359.374,1114.593Z" transform="translate(-4282.213 -1105.062)"></path>
                    <path d="M4393.922,1105.439a9.5,9.5,0,1,0,9.5,9.5A9.5,9.5,0,0,0,4393.922,1105.439Zm0,15a5.5,5.5,0,1,1,5.5-5.5A5.51,5.51,0,0,1,4393.922,1120.439Z" transform="translate(-4282.213 -1105.062)"></path>
                    <path d="M4335.5,1111.072l-6.31-6.01-2.83,2.71,7.14,6.81v9.94h4v-9.94l7.14-6.81-2.83-2.71Z" transform="translate(-4282.213 -1105.062)"></path>
                    </svg>
                </a>
            </span>
            <nav class="site-nav h-full">
                <ul class="flex items-center">
                    <li class="dropdown nav-item--1 inline-block relative">
                    <button class="nav-link--1 flex items-center cursor-pointer">
                        Mortgages
                        <span class="inline-block md:w-5 md:h-5  pointer-events-none md:hidden">
                        <svg xmlns="http://www.w3.org/2000/svg" class="pointer-events-none" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                    </button> 
                    <ul class="dropdown-menu absolute menu-level--1 hidden container-main w-full">
                        <li class="nav-item--2  secondary-has-children">
                        <a href="/bad-credit-mortgages" class="nav-link--2 flex items-center cursor-pointer child-menu-closed ">
                            Bad Credit Mortgages
                            <span class="inline-block md:w-5 md:h-5 menu-toggle-level--2">
                                <svg xmlns="http://www.w3.org/2000/svg" class="pointer-events-none" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
                                </svg>
                            </span>
                        </a> <ul class="menu-level--2  menu-open  " aria-expanded="false">
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/bankruptcy" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Bankruptcy
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/mortgages-with-a-ccj" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        CCJ
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/debt-management-plan" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Debt Management Plan
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/defaults" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Defaults
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/first-time-buyers" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        First Time Buyers
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/guarantor-mortgages" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Guarantor Mortgages
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/iva" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        IVA
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/late-payments" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Late Payments
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/low-credit-score" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Low Credit Score
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/no-credit-history" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        No Credit History
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/payday-loans" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Payday Loans
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/remortgaging" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Remortgaging
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/bad-credit-mortgages/repossession" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Repossession
                        </a> </li>
                        </ul>
                        </li>
                        <li class="nav-item--2  secondary-has-children">
                        <a href="/self-employed-mortgage" class="nav-link--2 flex items-center cursor-pointer child-menu-closed ">
                        Self-Employed Mortgages
                        <span class="inline-block md:w-5 md:h-5 menu-toggle-level--2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="pointer-events-none" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                        </a> <ul class="menu-level--2  menu-open  " aria-expanded="false">
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/1-year-accounts" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        1 Year Accounts
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/2-year-accounts" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        2 Year Accounts
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/agency-workers" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Agency Workers
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/contractor" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Contractors
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/freelancers" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Freelancers
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/company-directors" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Limited Company Directors
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/no-accounts" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        No Accounts
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/retained-profit" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Retained Profits
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/self-employed-mortgage/sole-traders" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Sole Traders &amp; Partnerships
                        </a> </li>
                        </ul>
                        </li>
                        <li class="nav-item--2  secondary-has-children">
                        <a href="/remortgage" class="nav-link--2 flex items-center cursor-pointer child-menu-closed ">
                        Remortgages
                        <span class="inline-block md:w-5 md:h-5 menu-toggle-level--2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="pointer-events-none" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                        </a> <ul class="menu-level--2  menu-open  " aria-expanded="false">
                        <li class="nav-item--3  ">
                        <a href="/remortgage/buy-a-second-home" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Buy a Second Home
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/remortgage/debt-consolidation" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Debt Consolidation
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/remortgage/home-improvements" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Home Improvements
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/remortgage/release-equity" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Release Equity
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/remortgage/second-charge-mortgages" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Second Charge Mortgages
                        </a> </li>
                        </ul>
                        </li>
                        <li class="nav-item--2  secondary-has-children">
                        <a href="/specialist-mortgages" class="nav-link--2 flex items-center cursor-pointer child-menu-closed ">
                        Specialist Mortgages
                        <span class="inline-block md:w-5 md:h-5 menu-toggle-level--2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="pointer-events-none" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                        </a> <ul class="menu-level--2  menu-open  " aria-expanded="false">
                        <li class="nav-item--3  ">
                        <a href="/specialist-mortgages/expat-mortgage" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Expats
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/specialist-mortgages/right-to-buy-mortgage" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Right to Buy
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/specialist-mortgages/shared-ownership-mortgage" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Shared Ownership
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/specialist-mortgages/tier-2-visa-mortgage" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Tier 2 Visas
                        </a> </li>
                        <li class="nav-item--3  ">
                        <a href="/specialist-mortgages/zero-hour-contract-mortgage" class="nav-link--3 flex items-center cursor-pointer child-menu-closed ">
                        Zero Hour Contracts
                        </a> </li>
                        </ul>
                        </li>
                    </ul>
                    </li>
                    <li class="dropdown nav-item--1 inline-block relative">
                    <button class="nav-link--1 flex items-center cursor-pointer">                    Calculators
                        <span class="inline-block md:w-5 md:h-5  pointer-events-none md:hidden">
                            <svg xmlns="http://www.w3.org/2000/svg" class="pointer-events-none" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
                            </svg>
                        </span>
                    </button> 
                    <ul class="dropdown-menu absolute menu-level--1 hidden md:flex-col container-main w-full">
                    <li class="nav-item--2  ">
                    <a href="/mortgage-calculators/bad-credit-calculator" class="nav-link--2 flex items-center cursor-pointer child-menu-closed secondary-nav-item">
                    Bad Credit Mortgage Calculator
                    </a> </li>
                    <li class="nav-item--2  ">
                    <a href="/mortgage-calculators/self-employed-mortgage-calculator" class="nav-link--2 flex items-center cursor-pointer child-menu-closed secondary-nav-item">
                    Self-Employed Mortgage Calculator
                    </a> </li>
                    <li class="nav-item--2  ">
                    <a href="/mortgage-calculators/mortgage-payment-calculator" class="nav-link--2 flex items-center cursor-pointer child-menu-closed secondary-nav-item">
                    Mortgage Payment Calculator
                    </a> </li>
                    <li class="nav-item--2  ">
                    <a href="/mortgage-calculators/remortgage-calculator" class="nav-link--2 flex items-center cursor-pointer child-menu-closed secondary-nav-item">
                    Remortgage Calculator
                    </a> </li>
                    <li class="nav-item--2  ">
                    <a href="/mortgage-calculators/mortgage-affordability-calculator" class="nav-link--2 flex items-center cursor-pointer child-menu-closed secondary-nav-item">
                    Mortgage Affordability Calculator
                    </a> </li>
                    <li class="nav-item--2  ">
                    <a href="https://www.haysto.com/mortgage-calculators" class="nav-link--2 flex items-center cursor-pointer child-menu-closed secondary-nav-item">
                    Our Mortgage Calculators
                    </a> </li>
                    </ul>
                    </li>
                    <div id="page-overlay" class="z-10 hidden"></div>
                    <li class="nav-item--1  ">
                    <a href="/mortgage-guide" class="nav-link--1 flex items-center cursor-pointer child-menu-closed ">
                    Guides
                    </a> </li>
                    <li class="nav-item--1  ">
                    <a href="/about-us" class="nav-link--1 flex items-center cursor-pointer child-menu-closed ">
                    About Us
                    </a> </li>
                </ul>
            </nav>
            <div class="flex items-center">
            <a href="/covid-19" class="text-white bg-primary border border-white text-xs mr-2 rounded-md px-2 py-1">COVID-19</a>
            <ul class="header-actions hidden md:flex font-bold">
            <li class="mx-2 inline-block md:hidden lg:inline-block">
            <a href="            https://my.haysto.com/new-enquiry
                " class="header-btn px-3 py-1 border rounded-full">Get started</a>
            </li>
            <li class="site-login ml-2"><a href="            https://my.haysto.com/login
                ">Login</a></li>
            </ul>
            <button id="toggle-menu" class="relative hamburger hamburger--squeeze z-50 focus:outline-none md:hidden" type="button" aria-label="Open mobile menu">
            <span class="hamburger-box pointer-events-none">
            <span class="hamburger-inner pointer-events-none"></span>
            </span>
            </button>
            </div>
        </div>
    </header>
</template>

<script>
   export default{

   }
</script>

<style scoped>

    .dropdown:hover .dropdown-menu {
        display: flex;
    }

    


    .site-logo {
        width: 120px;
        --text-opacity: 1;
        color: rgba(0,0,0,var(--text-opacity));
    }

    .site-nav {
        display: flex;
    }

    .nav-item--1 {
        align-items: center;
        display: inline-flex;
        height: 100%;
    }

    .nav-link--1 {
        padding-left: 1.5rem;
        padding-right: 1.5rem;
        align-items: center;
        justify-content: center;
        height: 100%;
        position: relative;
        font-weight: 600;
    }


    .nav-link--1:hover:after {
        content: "";
        --bg-opacity: 1;
        background-color: #593ee6;
        background-color: rgba(89,62,230,var(--bg-opacity));
        height: .25rem;
        width: 100%;
        position: absolute;
        bottom: 0;
        left: 0;
        z-index: 10;
    }

    .site-nav>ul li ul {
        transition-property: background-color,border-color,color,fill,stroke,opacity,box-shadow,transform;
        transition-duration: .15s;
        transition-timing-function: cubic-bezier(.4,0,.2,1);
    }

    .menu-level--1:before {
        width: 100%;
        left: 0;
    }

    .nav-link--3:hover {
        --bg-opacity: 1;
        background-color: #f4f4f4;
        background-color: rgba(244,244,244,var(--bg-opacity));
    }

    .menu-level--1:after {
    --bg-opacity: 1;
    background-color: #fff;
    background-color: rgba(255,255,255,var(--bg-opacity));
    position: absolute;
    }

    #page-overlay {
         z-index: -10;
        position: fixed;
        top: 4.5rem;
        right: 0;
        bottom: 0;
        left: 0;
        background-color: rgba(0,0,0,.35);
    }

    
    .dropdown:hover ~ #page-overlay{
        display: flex;
    }

    @media (min-width: 1024px){
        .menu-level--1:before {
            width: 100%;
            left: 0;
        }
        .menu-level--1 {
            padding-top: 1.5rem;
            padding-bottom: 1.5rem;
        }
    }

@media (min-width: 768px) {

    .nav-link--2 {
        display: flex;
        padding-left: .5rem;
        position: relative;
        margin-bottom: .25rem;
        font-weight: 700;
        --text-opacity: 1;
        color: #593ee6;
        color: rgba(89,62,230,var(--text-opacity));
    }

    .menu-level--1:before {
        content: "";
        position: absolute;
        height: .25rem;
        left: 0;
        width: 100%;
        --bg-opacity: 1;
        background-color: #f4f4f4;
        background-color: rgba(244,244,244,var(--bg-opacity));
        top: -4px;
    }
    

    .nav-item--2 {
        padding-right: .75rem;
        font-size: 1rem;
        line-height: 2;
    }
    .nav-link--1:hover:after {
        content: "";
        --bg-opacity: 1;
        background-color: #593ee6;
        background-color: rgba(89,62,230,var(--bg-opacity));
        height: .25rem;
        width: 100%;
        position: absolute;
        bottom: 0;
        left: 0;
        z-index: 10;
    }


    .menu-level--1 {
        justify-content: space-between;
        width: 100vh;
        top: 70px;
        
    }
    .container-main {
        max-width: 1040px;
    }
    .menu-level--1:after {
        content: "";
        height: 100%;
        top: 0;
        width: 400%;
        left: -200%;
        z-index: -1;
    }
    .nav-item--1:hover .nav-link--1:after {
        content: "";
        --bg-opacity: 1;
        background-color: #593ee6;
        background-color: rgba(89,62,230,var(--bg-opacity));
        height: .25rem;
        width: 100%;
        position: absolute;
        bottom: 0;
        left: 0;
        z-index: 10;
    }
    *, :after, :before {
        box-sizing: border-box;
        border: 0 solid #e2e8f0;
    }
    .menu-level--1, .menu-level--1:after {
        --bg-opacity: 1;
        background-color: #fff;
        background-color: rgba(255,255,255,var(--bg-opacity));
        position: absolute;
    }
   
}








    

</style>