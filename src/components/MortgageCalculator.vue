<template>
    <div class="flex flex-col w-full md:pl-10 md:w-1/2">
    
        <form class="calculator-form bg-white p-6 shadow-lg z-10 rounded-md flex flex-col">
            <div class="input-group mb-4">
                <label for="calc_salary" class="uppercase text-xs">What is your annual salary?</label>
                <div class="flex">
                    <div class="flex bg-black text-white items-center justify-center w-12">
                        <span class="font-bold text-xl">
                        £
                        </span>
                    </div>
                    <div class="relative flex w-full border border-grey-dark border-l-0 border-b-0">
                        <input v-model="annualIncome" class="tracking-wider shadow-md w-full px-3 py-2" type="text" maxlength="9" name="calc_salary" id="calc_salary">
                        <span id="calc_salary_output" class="absolute top-0 left-0 text-xl text-black flex items-center px-3 h-full"></span>
                    </div>
                    <div class="w-8 h-8 p-1 mt-2 ml-2">
                        <span content="The customer’s total annual income i.e £30,000." v-tippy="{ placement : 'left' }">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                    </div>
                </div>
            </div>
            <div class="input-group mb-4">
                <label for="calc_partner_salary" class="uppercase text-xs pr-10">New property cost</label>
                <div class="flex">
                    <div class="flex bg-black text-white items-center justify-center w-12">
                        <span class="font-bold text-xl">
                        £
                        </span>
                    </div>
                    <div class="relative flex w-full border border-grey-dark border-l-0 border-b-0">
                        <input v-model="propertyCost" class="tracking-wider shadow-md w-full px-3 py-2" maxlength="9" type="text" name="calc_partner_salary" id="calc_partner_salary">
                        <span id="calc_partner_salary_output" class="absolute top-0 left-0 text-xl flex items-center px-3 h-full"></span>
                    </div>
                    <div class="w-8 h-8 p-1 mt-2 ml-2">
                        <span content="The cost of the customers new property i.e £200,000." v-tippy="{ placement : 'left' }">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                    </div>
                </div>
            </div>
            <div class="input-group mb-6">
                <label for="calc_deposit" class="uppercase text-xs">Borrow amount</label>
                <div class="relative flex">
                    <div class="flex bg-black text-white items-center justify-center w-12">
                        <span class="font-bold text-xl">
                        £
                        </span>
                    </div>
                    <div class="relative flex w-full border border-grey-dark border-l-0 border-b-0">
                        <input v-model="borrowAmount" class="tracking-wider shadow-md w-full px-3 py-2" maxlength="9" type="text" name="calc_deposit" id="calc_deposit">
                        <span id="calc_deposit_output" class="absolute top-0 left-0 text-xl flex items-center px-3 h-full"></span>
                    </div>
                    <div class="w-8 h-8 p-1 mt-2 ml-2">
                        <span content="How much they need to borrow for the mortgage i.e £180,000." v-tippy="{ placement : 'left' }">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z" clip-rule="evenodd"></path>
                        </svg>
                        </span>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <span class="font-hand font-bold mb-2">Results</span>
                    <p class="font-medium">Loan to value (%) = (Borrow amount ÷ New property cost) x 100</p>
                    <p>Anything over 95% is considered as unlikely to get a mortgage:</p>
                    <span id="calc_result" class="h2 title-font py-2 mb-6 block border-b-2 border-black w-full font-black"> {{loanToValue}}%</span>
                    <p class="font-medium">>Income Multiple (Decimal) = (Borrow amount ÷ Annual Income)</p>
                    <p>Anything over 4.5 is considered as unlikely to get a mortgage:</p>
                    <span id="calc_result" class="h2 title-font py-2 mb-6 block border-b-2 border-black w-full font-black"> {{incomeMultiple}} </span>
                    <p class="font-medium">>Deposit Level (%) = (100 - Loan to value)</p>
                    <p>Anything under 5% is considered as unlikely to get a mortgage:</p>
                <span id="calc_result" class="h2 title-font py-2 mb-6 block border-b-2 border-black w-full font-black"> {{depositLevel}}%</span>

            </div>
            <div class="flex flex-col md:flex-row mt-6">
                <a href="            https://my.haysto.com/new-enquiry
                    " class="inline-block bg-black rounded-full text-white mt-4 w-full title-font text-xl tracking-wide title-font text-center px-12 py-2 uppercase my-0 md:mr-2 md:px-2 lg:w-1/2  hover:bg-primary  ">
                Get started
                </a>
                <a href="            tel:03301333230
                    " class="inline-block bg-black rounded-full text-white mt-4 w-full title-font text-xl tracking-wide title-font text-center px-12 py-2 uppercase my-0 md:ml-2 md:px-2 lg:w-1/2  hover:bg-primary  ">
                Call us
                </a>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    data() {
            return { annualIncome: '',
                    propertyCost: '',
                    borrowAmount: '',
                    helpInput: false,
                    loanToValue: 0,
                    incomeMultiple: 0,
                    depositLevel: 0
            }
        },
    methods: {
       
        updateInput(type, newValue) {
             const result = newValue.replace(/\D/g, "")
                .replace(/\B(?=(\d{3})+(?!\d))/g, ",");
                this.$nextTick(() => this[type] = result);

                if(this.borrowAmount != '' && this.propertyCost != '') {
                    this.calcLoanToValue();
                }

                 if(this.borrowAmount != '' && this.annualIncome != '') {
                    this.calincomeMultiple();
                }

                 if(this.loanToValue != '') {
                    this.calcdepositLevel();
                }
            
        },
        calcLoanToValue() {
            const result = (parseInt(this.borrowAmount) / parseInt(this.propertyCost)) * 100;
            this.loanToValue = result.toFixed(2);
        },
        calincomeMultiple() {
            const result = (parseInt(this.borrowAmount) / parseInt(this.annualIncome));
            this.incomeMultiple = result.toFixed(1);
        },
        calcdepositLevel() {
            const result = (100 - this.loanToValue);
            this.depositLevel = result.toFixed(2);
        }
    },
    // These watchers act if the inputs are updated
        watch: {
            annualIncome(newValue) {
                this.updateInput('annualIncome', newValue);
                
            },
            propertyCost: function(newValue) {
                this.updateInput('propertyCost', newValue);
            },
            borrowAmount: function(newValue) {
                this.updateInput('borrowAmount', newValue);
            
            },
           
            
        }
}
</script>
