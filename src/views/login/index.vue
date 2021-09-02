<template>
    <div class="tw-bg-main tw-h-screen tw-p-10">
        <div class="tw-block">
            <img src="assets/images/logo.png" alt="" class="tw-w-4/12 tw-h-30">
            <div class="tw-w-full tw-mt-18">
                <div class="tw-w-4/12 tw-mx-auto">
                    
                    <div class="tw-mx-auto tw-w-10/12">
                        <div class="tw-block tw-mb-12 ">
                            <div class="tw-text-4xl tw-text-blacktw-font-bold">
                                CTRA
                            </div>
                            <div class="tw-text-gray-800">
                                Boas vindas, por favor entre com a sua conta
                            </div>
                        </div>
                        <div class="tw-w-full tw-flex tw-flex-wrap tw-border-1 tw-rounded-md">
                            <div class="tw-w-1/12 md:tw-w-2/12 sm:tw-w-2/12 tw-bg-main tw-rounded-l-md">
                                <img src="assets/icons/user.png" alt="" class="tw-mt-4 tw-ml-2 tw-w-6 tw-h-6">
                            </div>
                            <div class="tw-w-11/12 sm:tw-w-10/12 md:tw-w-10/12">
                                <input type="text" class="tw-w-full tw-bg-main tw-rounded-r-md tw-p-4 tw-placeholder-black" placeholder="Email">
                            </div>
                        </div>
                        <div class="tw-w-full tw-flex tw-flex-wrap tw-border-1 tw-rounded-md tw-mt-6">
                            <div class="tw-w-1/12 md:tw-w-2/12 sm:tw-w-2/12 tw-bg-main tw-rounded-l-md">
                                <img src="assets/icons/lock.png" alt="" class="tw-mt-4 tw-ml-2 tw-w-6 tw-h-6">
                            </div>
                            <div class="tw-w-11/12 sm:tw-w-10/12 md:tw-w-10/12">
                                <input type="text" class="tw-w-full tw-bg-main tw-rounded-r-md tw-p-4 tw-placeholder-black" placeholder="Senha">
                            </div>
                        </div>
                        <button class="tw-w-full tw-p-4 tw-rounded-md tw-bg-blue-900 tw-text-white tw-shadow-xl tw-mt-12">
                            LOGIN
                        </button>
                        <div class="tw-text-right tw-mt-2">
                            Esqueceu sua senha?
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    input:focus, textarea:focus, select:focus{
        outline: none;
    }
</style>