<html ng-app="ndesktop.main" data-theme-option="dark" data-site="neyine" class="dark" data-theme="dark"><head><style type="text/css">@charset "UTF-8";[ng\:cloak],[ng-cloak],[data-ng-cloak],[x-ng-cloak],.ng-cloak,.x-ng-cloak,.ng-hide:not(.ng-hide-animate){display:none !important;}ng\:form{display:block;}.ng-animate-shim{visibility:hidden;}.ng-anchor{position:absolute;}</style><style type="text/css">@charset "UTF-8";[ng\:cloak],[ng-cloak],[data-ng-cloak],[x-ng-cloak],.ng-cloak,.x-ng-cloak,.ng-hide:not(.ng-hide-animate){display:none !important;}ng\:form{display:block;}.ng-animate-shim{visibility:hidden;}.ng-anchor{position:absolute;}</style>
    <title>NEYİNE | Spor Bahisleri, Casino, Canlı Casino ve En yüksek oranlar</title>


    <!-- Set Base Href -->
    <base href="/">

    <!-- Favicon -->
    <link rel="icon" href="https://cdn.nagcdn.com/_ngamingbase/neyine/favicon.png?v=1" type="image/x-icon">


    <!-- Styles -->
    <link href="https://cdn.nagcdn.com/_ngamingbase/core/assets/styles/app.style.min.css?v=22" rel="stylesheet">
    <link href="https://cdn.nagcdn.com/_ngamingbase/neyine/assets/styles/site.style.min.css?v=22" rel="stylesheet">

    <!-- Ng Styles -->
   
            <!-- Site Header -->






<script type="text/javascript">
    window.hasMobileFirstExtension = true;</script></head><body><div id="siteHeader" class="col-12 uk-flex uk-flex-middle uk-flex-between ng-scope uk-sticky" uk-sticky="animation: uk-animation-slide-top; show-on-up: true; media: (max-width: 500px)">

    <!-- Logo & Nav Link -->
    <div class="logo uk-flex">
        <!-- Responsive Menu Link -->
        <button class="menu-button na-alt-static-button uk-button hide-for-mobile uk-margin-right" type="button" uk-toggle="target: #siteSidebar" aria-expanded="true">
            <span uk-icon="menu" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="menu"><rect x="2" y="4" width="16" height="1"></rect><rect x="2" y="9" width="16" height="1"></rect><rect x="2" y="14" width="16" height="1"></rect></svg></span>
        </button>

        <!-- Logo -->
        <a href="/" class="logo-img">
            <!-- ngIf: activeTheme == 'light' && !isNewYearMode -->
            <!-- ngIf: activeTheme == 'dark' && !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png" ng-if="activeTheme == 'dark' &amp;&amp; !isNewYearMode" class="ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png"><!-- end ngIf: activeTheme == 'dark' && !isNewYearMode -->
            <!-- ngIf: activeTheme == 'light' && isNewYearMode -->
            <!-- ngIf: activeTheme == 'dark' && isNewYearMode -->
        </a>

        <!-- Back -->
        <a class="history-back-button na-alt-static-button uk-button uk-margin-left uk-disabled" ng-class="{'uk-disabled' : !historyBackDisabled}" ng-click="historyBack();" uk-tooltip="title: Geri Dön" aria-expanded="false" title="">
            <span uk-icon="arrow-left" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="arrow-left"><polyline fill="none" stroke="#000" points="10 14 5 9.5 10 5"></polyline><line fill="none" stroke="#000" x1="16" y1="9.5" x2="5" y2="9.52"></line></svg></span>
        </a>

        <!-- Search -->
        <a class="search-button na-alt-static-button uk-button uk-margin-small-left uk-icon uk-search-icon" uk-search-icon="" uk-toggle="" href="#modal-search" uk-tooltip="title: Arama" aria-expanded="false" title=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="search-icon"><circle fill="none" stroke="#000" stroke-width="1.1" cx="9" cy="9" r="7"></circle><path fill="none" stroke="#000" stroke-width="1.1" d="M14,14 L18,18 L14,14 Z"></path></svg></a>

        <div id="modal-search" class="uk-modal-full uk-modal" uk-modal="">
            <div class="uk-modal-dialog uk-flex uk-flex-center uk-flex-middle uk-search-dialog" uk-height-viewport="">
                <button class="uk-modal-close-full uk-icon uk-close" type="button" uk-close=""><svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg" data-svg="close-icon"><line fill="none" stroke="#000" stroke-width="1.1" x1="1" y1="1" x2="13" y2="13"></line><line fill="none" stroke="#000" stroke-width="1.1" x1="13" y1="1" x2="1" y2="13"></line></svg></button>
                <form class="uk-search uk-search-large ng-pristine ng-valid" ng-submit="searchSubmit(searchText)">
                    <input class="uk-search-input uk-text-center ng-pristine ng-untouched ng-valid" type="search" ng-model="searchText" placeholder="Takım ya da oyuncu ara">
                </form>
            </div>
        </div>
</div>
    <!-- Actions -->
    <div class="actions">
        <!-- ngIf: !loginStatus || loginStatus == '' --><div class="before-login ng-scope" ng-if="!loginStatus || loginStatus == ''">
            <a class="na-alt-button register-button uk-button uk-margin-small-right ng-binding" href="#modal-register" ng-click="showRegisterModal();" uk-toggle="" aria-expanded="false">
                Kayıt Ol
            </a>
            <a class="na-button uk-button login-button ng-binding" href="#modal-login" uk-toggle="" aria-expanded="false">
                <span uk-icon="sign-in" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="sign-in"><polygon points="7 2 17 2 17 17 7 17 7 16 16 16 16 3 7 3"></polygon><polygon points="9.1 13.4 8.5 12.8 11.28 10 4 10 4 9 11.28 9 8.5 6.2 9.1 5.62 13 9.5"></polygon></svg></span> Giriş
            </a>
        </div><!-- end ngIf: !loginStatus || loginStatus == '' -->

        <!-- ngIf: loginStatus == 'login' -->

        <!-- Login Modal Begin -->
        <div id="modal-login" class="uk-modal-full membership-modal uk-modal" uk-modal="">
            <div class="uk-modal-dialog">
                <button class="uk-modal-close-full uk-close-large uk-icon uk-close" type="button" uk-close=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="close-large"><line fill="none" stroke="#000" stroke-width="1.4" x1="1" y1="1" x2="19" y2="19"></line><line fill="none" stroke="#000" stroke-width="1.4" x1="19" y1="1" x2="1" y2="19"></line></svg></button>

                <div class="row form-modal">
                    <div class="uk-width-1-1 pre-scrollable" style="min-height:650px;">
                        <div class="uk-margin-bottom uk-text-center membership-logo">
                            <!-- ngIf: activeTheme == 'light' -->
                            <!-- ngIf: activeTheme == 'dark' --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png" ng-if="activeTheme == 'dark'" style="max-width:240px;" class="ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png"><!-- end ngIf: activeTheme == 'dark' -->
                        </div>

                        <!-- Login 1.Step -->
                        <div class="modal-content uk-width-1-1 p-5" id="loginStep1" ng-hide="userModel.naSecurityActive">
                            <form name="loginForm1" ng-submit="loginForm1.$invalid ? '' : playerSecuritySteps(login.username)" novalidate="" class="ng-pristine ng-invalid ng-invalid-required">
                                <div class="uk-margin-small-bottom">
                                    <h2 class="ng-binding">Giriş</h2>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Kullanıcı Adı</label>
                                    <input class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required" type="text" id="usernameInput" name="username" placeholder="Kullanıcı Adı" ng-model="login.username" autocomplete="off" tabindex="1" required="">
                                    <!-- ngIf: loginForm1.username.$touched -->
                                </div>

                                <button type="submit" class="na-button uk-button uk-width-1-1 ng-binding">Devam Et</button>

                                <div class="forgot-pass-link">
                                    <a href="#modal-forgot-password" uk-toggle="" class="ng-binding" aria-expanded="false">Şifremi Yenile</a>
                                </div>
                            </form>
                        </div>

                        <!-- Login 2.Step -->
                        <div class="modal-content uk-width-1-1 p-5 uk-hidden" id="loginStep2" ng-hide="userModel.naSecurityActive">
                            <form name="loginForm2" ng-submit="loginForm2.$invalid ? '' : userService.login(login.username, login.password)" novalidate="" class="ng-pristine ng-invalid ng-invalid-required">

                                <div class="uk-margin-small-bottom">
                                    <h2 class="ng-binding">Güvenliğiniz için kontrol edin!</h2>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">
                                        
                                    </label>

                                    <!-- Captcha -->
                                    <!-- ngIf: captchaDataView -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Şifre</label>
                                    <input class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required" type="password" id="passwordInput" name="password" placeholder="Şifre" ng-model="login.password" autocomplete="off" tabindex="1" required="">
                                    <!-- ngIf: loginForm2.password.$touched -->
                                </div>

                                <button type="submit" class="na-button uk-button uk-width-1-1 uk-margin-small-top ng-binding">Giriş</button>

                                <div class="forgot-pass-link">
                                    <a href="#modal-forgot-password" uk-toggle="" class="ng-binding" aria-expanded="false">Şifremi Yenile</a>
                                </div>
                            </form>
                        </div>

                        <!-- Login 3.Step -->
                        <div class="modal-content uk-width-1-1 p-5 ng-hide" id="loginStep3" ng-show="userModel.naSecurityActive">
                            <form name="loginForm3" ng-submit="loginForm3.$invalid ? '' : userService.loginVerification(login.username, login.securityCode, login.password)" novalidate="" class="ng-pristine ng-invalid ng-invalid-required">

                                <div class="uk-margin-small-bottom">
                                    <h2 class="ng-binding">Mail Onay Kodunuzu Girin!</h2>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Mail Onay Kodu</label>
                                    <input class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required" type="password" id="safety_code" name="safety_code" placeholder="******" ng-model="login.securityCode" autocomplete="off" tabindex="1" required="">
                                    <!-- ngIf: loginForm3.safety_code.$touched -->
                                </div>

                                <button type="submit" class="na-button uk-button uk-width-1-1 uk-margin-small-top ng-binding">Giriş</button>
                            </form>
                        </div>

                        <!-- <div id="555-34UDF-44" class="cf"></div> -->

                        <div class="register-link loginStep1">
                            <a href="#modal-register" uk-toggle="" class="ng-binding" aria-expanded="false">Üye değil misiniz? <b class="ng-binding">Hemen Kayıt Olun!</b></a>
                        </div>

                        <a class="step-back loginStep2 uk-hidden ng-binding" ng-hide="userModel.naSecurityActive" ng-click="stepViewer('loginStep1', 'loginStep2')"> <i class="fas fa-arrow-circle-left"></i> Önceki adıma geri dön </a>
                    </div>
                </div>
                <div class="uk-background-cover"></div>
            </div>

        </div>
        <!-- Login Modal End -->
        <!-- Register Modal Begin -->
        <div id="modal-register" class="uk-modal-full membership-modal uk-modal" uk-modal="">
            <div class="uk-modal-dialog">
                <button class="uk-modal-close-full uk-close-large uk-icon uk-close" type="button" uk-close=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="close-large"><line fill="none" stroke="#000" stroke-width="1.4" x1="1" y1="1" x2="19" y2="19"></line><line fill="none" stroke="#000" stroke-width="1.4" x1="19" y1="1" x2="1" y2="19"></line></svg></button>

                <div class="row form-modal">
                    <div class="uk-width-1-1 pre-scrollable" style="min-height:1800px;">
                        <div class="uk-margin-bottom uk-text-center membership-logo">
                            <!-- ngIf: activeTheme == 'light' -->
                            <!-- ngIf: activeTheme == 'dark' --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png" ng-if="activeTheme == 'dark'" style="max-width:240px;" class="ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png"><!-- end ngIf: activeTheme == 'dark' -->
                        </div>

                        <div class="modal-content uk-width-1-1 p-5">
                            <form name="registerForm" id="register-form" ng-submit="registerForm.$invalid ? '' : userStatus['username'] ? '' : passwordStatus ? '' : isDate ? '' : isChild ? '' : registerFromSubmit(register)" novalidate="" class="ng-pristine ng-valid-mask ng-invalid ng-invalid-required ng-valid-pattern ng-valid-maxlength ng-valid-email ng-invalid-minlength">

                                <div class="uk-margin-small-bottom">
                                    <h2 class="ng-binding">Kayıt Ol</h2>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Ad</label>

                                    <input name="name" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-pattern ng-valid-minlength ng-valid-maxlength" ng-model="register.Name" ng-pattern="w*[A-Za-z_ğüşıöçĞÜŞİÖÇ ]+w*" autocomplete="off" minlength="3" maxlength="30" tabindex="1" required="">

                                    <!-- ngIf: registerForm.name.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Soyad</label>

                                    <input name="surname" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-pattern ng-valid-minlength" ng-model="register.Surname" ng-pattern="w*[A-Za-z_ğüşıöçĞÜŞİÖÇ ]+w*" autocomplete="off" minlength="2" tabindex="2" required="">

                                    <!-- ngIf: registerForm.surname.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Doğum Tarihi</label>

                                    <input type="text" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-valid-mask ng-invalid ng-invalid-required" name="birthdate" ng-model="register.BirthDate" ng-keyup="birthdate(register.BirthDate)" ui-mask="99/99/9999" model-view-value="true" ui-mask-placeholder="gg/aa/yyyy" tabindex="3" ui-mask-placeholder-char="-" autocomplete="off" required="" placeholder="gg/aa/yyyy">

                                    <!-- default validation -->
                                    <!-- ngIf: registerForm.birthdate.$touched -->

                                    <!-- other validation -->
                                    <!-- ngIf: registerForm.birthdate.$modelValue -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Cinsiyet</label>

                                    <select name="gender" class="uk-select uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required" tabindex="4" ng-model="register.Gender" required="">
                                        <option value="" class="ng-binding">Lütfen Seçiniz</option>
                                        <option value="M" class="ng-binding">Erkek</option>
                                        <option value="F" class="ng-binding">Kadın</option>
                                    </select>

                                    <!-- ngIf: registerForm.gender.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Ülke</label>

                                    <select name="country" class="uk-select uk-margin-small-top ng-pristine ng-untouched ng-valid ng-valid-required" placeholder="Ülke" ng-model="register.Country" ng-change="getCity(register.Country);" tabindex="5" required="">
                                        <!-- ngRepeat: item in countryList --><option ng-repeat="item in countryList" value="TUR" class="ng-binding ng-scope">Turkey</option><!-- end ngRepeat: item in countryList --><option ng-repeat="item in countryList" value="ALB" class="ng-binding ng-scope">Albania</option><!-- end ngRepeat: item in countryList --><option ng-repeat="item in countryList" value="ARG" class="ng-binding ng-scope">Argentina</option><!-- end ngRepeat: item in countryList --><option ng-repeat="item in countryList" value="ARM" class="ng-binding ng-scope">Armenia</option><!-- end ngRepeat: item in countryList -->
                                    </select>

                                    <!-- ngIf: registerForm.country.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom" ng-init="autoComplateListVisible()">
                                    <label class="ng-binding">Şehir</label>

                                    <!-- ngIf: cityList == '' -->

                                    <!-- ngIf: cityList != '' --><select class="uk-select uk-margin-small-top ng-pristine ng-untouched ng-scope ng-invalid ng-invalid-required" name="city" tabindex="6" ng-change="cityChange(CityModal);" ng-model="CityModal" ng-if="cityList != ''" ng-options="item as item.value for item in cityList track by item.id" required=""><option value="" class="ng-binding" selected="selected">Lütfen Seçiniz</option><option label="Adana" value="Adana">Adana</option></select><!-- end ngIf: cityList != '' -->

                                    <!-- ngIf: registerForm.city.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Adres</label>

                                    <input type="text" name="address" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-minlength" ng-model="register.AddressDetail" tabindex="7" autocomplete="off" minlength="4" required="">

                                    <!-- ngIf: registerForm.address.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">E-Posta</label>

                                    <input type="email" name="email" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-valid-email ng-invalid ng-invalid-required ng-valid-pattern ng-valid-minlength ng-valid-maxlength" ng-model="register.Email" ng-pattern="/^.+@.+\..+$/" minlength="6" maxlength="32" autocomplete="off" tabindex="8" required="">

                                    <!-- ngIf: registerForm.email.$touched -->

                                    <div class="uk-position-relative">
                                        <!-- ngIf: userStatus['email'] -->
                                    </div>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">GSM</label>

                                    <input name="phone" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-valid-required ng-valid-pattern ng-invalid ng-invalid-minlength ng-valid-maxlength" ng-model="register.Gsm" placeholder="GSM" minlength="10" maxlength="16" tabindex="9" ng-pattern="/^\d+$/" autocomplete="off" required="">

                                    <!-- ngIf: registerForm.phone.$touched -->

                                    <div class="uk-position-relative">
                                        <!-- ngIf: userStatus['gsm'] -->
                                    </div>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Kullanıcı Adı</label>

                                    <input type="text" name="username" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-pattern ng-valid-minlength" ng-model="register.Username" ng-pattern="^[a-zA-Z0-9](_(?!(.|_))|.(?!(_|.))|[a-zA-Z0-9]){3,30}[a-zA-Z0-9]$" minlength="3" tabindex="10" ng-blur="getUserInfo(register.Username, 'username')" autocomplete="off" required="">

                                    <!-- ngIf: registerForm.username.$touched -->

                                    <div class="uk-position-relative">
                                        <!-- ngIf: userStatus['username'] -->
                                    </div>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Şifre</label>

                                    <input type="password" name="password" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-minlength" autocomplete="new-password" ng-model="register.Password" minlength="6" tabindex="11" required="">
                                    <!-- ngIf: registerForm.password.$touched -->
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Şifre (Tekrar)</label>

                                    <input type="password" name="rpassword" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required" autocomplete="new-password" ng-model="rpassword" ng-keyup="register.Password != rpassword ? passwordStatus = true : passwordStatus = false" tabindex="12" required="">
                                    <div ng-messages="registerForm.rpassword.$error" class="uk-position-relative ng-inactive">
                                        <!-- ngIf: register.Password != rpassword -->
                                    </div>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Para Birimi</label>

                                    <select name="currency" class="uk-select uk-margin-small-top ng-pristine ng-untouched ng-valid ng-valid-required" ng-model="register.Currency" ng-disabled="true" tabindex="13" required="" disabled="disabled">
                                        <!-- ngRepeat: item in currencyList --><option ng-repeat="item in currencyList" value="TRY" class="ng-binding ng-scope">TRY</option><!-- end ngRepeat: item in currencyList -->
                                    </select>

                                    <div ng-messages="registerForm.currency.$error" class="uk-position-relative ng-inactive">
                                        <!-- ngMessage: required -->
                                    </div>
                                </div>

                                <div class="uk-margin-bottom">
                                    <label class="ng-binding">Dil Seçimi</label>

                                    <select name="language" class="uk-select uk-margin-small-top uk-margin-small-bottom ng-pristine ng-untouched ng-valid ng-valid-required" ng-model="register.Language" tabindex="14" required="">
                                        <!-- ngRepeat: item in languagesList --><option ng-repeat="item in languagesList" value="en" class="ng-binding ng-scope">English</option><!-- end ngRepeat: item in languagesList --><option ng-repeat="item in languagesList" value="tr" class="ng-binding ng-scope">Türkçe</option><!-- end ngRepeat: item in languagesList -->
                                    </select>

                                    <div ng-messages="registerForm.language.$error" class="uk-position-relative ng-inactive">
                                        <!-- ngMessage: required -->
                                    </div>
                                </div>

                                <div class="uk-margin-bottom uk-margin-top">
                                    <label class="ng-binding"><input class="uk-checkbox ng-pristine ng-untouched ng-valid" name="newsemail" tabindex="15" type="checkbox" ng-model="register.SubscributionEmail" checked=""> Haber ve kampanyaları e-posta ile almak istiyorum.</label>
                                </div>

                                <div class="uk-margin-bottom">
                                    <label class="ng-binding"><input class="uk-checkbox ng-pristine ng-untouched ng-valid" name="newssms" tabindex="16" type="checkbox" ng-model="register.SubscributionSms" checked=""> Haber ve kampanyaları SMS ile almak istiyorum.</label>
                                </div>

                                <div class="uk-margin-bottom">
                                    <label class="ng-binding"><input class="uk-checkbox ng-pristine ng-untouched ng-valid ng-valid-required" name="isActive" tabindex="17" type="checkbox" ng-model="register.IsActive" required=""> 18 Yaşından büyüğüm. Sitenin, şartlar ve kullanım koşullarını okudum. Kabul ediyorum.</label>

                                    <div ng-messages="registerForm.isActive.$error" class="uk-position-relative ng-inactive">
                                        <!-- ngMessage: required -->
                                    </div>
                                </div>

                                <button type="submit" class="na-button uk-button uk-width-1-1 uk-margin-small-top ng-binding" ng-disabled="haveRequest">Kayıt Ol</button>
                            </form>
                        </div>
                        <div class="register-link loginStep1">
                            <a href="#modal-login" uk-toggle="" class="ng-binding" aria-expanded="false">Zaten üye misiniz? <b class="ng-binding">Hemen Giriş Yapın!</b></a>
                        </div>
                    </div>
                </div>
                <div class="uk-background-cover"></div>
            </div>
        </div>
        <!-- Register Modal End -->
        <!-- Forgot Password Modal Begin -->
        <div id="modal-forgot-password" class="uk-modal-full membership-modal uk-modal" uk-modal="">
            <div class="uk-modal-dialog">
                <button class="uk-modal-close-full uk-close-large uk-icon uk-close" type="button" uk-close=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="close-large"><line fill="none" stroke="#000" stroke-width="1.4" x1="1" y1="1" x2="19" y2="19"></line><line fill="none" stroke="#000" stroke-width="1.4" x1="19" y1="1" x2="1" y2="19"></line></svg></button>

                <div class="row form-modal">
                    <div class="uk-width-1-1 pre-scrollable" style="min-height:650px;">
                        <div class="uk-margin-bottom uk-text-center membership-logo">
                            <!-- ngIf: activeTheme == 'light' -->
                            <!-- ngIf: activeTheme == 'dark' --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png" ng-if="activeTheme == 'dark'" style="max-width:240px;" class="ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png"><!-- end ngIf: activeTheme == 'dark' -->
                        </div>

                        <!-- Login 1.Step -->
                        <div class="modal-content uk-width-1-1 p-5">
                            <form name="forgotForm" ng-submit="forgotForm.$invalid ? '' : forgotFromSubmit(forgot)" novalidate="" class="ng-pristine ng-invalid ng-invalid-required ng-valid-minlength ng-valid-maxlength">
                                <div class="uk-margin-small-bottom">
                                    <h2 class="ng-binding">Şifremi Unuttum</h2>
                                </div>

                                <!-- ngIf: !vrfInputs --><div class="uk-margin-small-bottom ng-scope" ng-if="!vrfInputs">
                                    <label class="ng-binding">E-Posta ya da Telefon</label>
                                    <input class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-minlength ng-valid-maxlength" type="text" name="emailorphone" ng-model="forgot.emailorphone" minlength="6" maxlength="32" autocomplete="off" required="">

                                    <!-- ngIf: forgotForm.emailorphone.$touched -->
                                </div><!-- end ngIf: !vrfInputs -->

                                <!-- ngIf: vrfInputs -->

                                <!-- ngIf: vrfInputs -->

                                <button type="submit" class="na-button uk-margin-small-top uk-button uk-width-1-1 ng-binding">Devam Et</button>
                            </form>
                        </div>


                        <div class="register-link loginStep1">
                            <a href="#modal-register" uk-toggle="" class="ng-binding" aria-expanded="false">Üye değil misiniz? <b class="ng-binding">Hemen Kayıt Olun!</b></a>
                        </div>
                    </div>
                </div>
                <div class="uk-background-cover"></div>
            </div>
        </div>
        <!-- Forgot Password Modal End -->
        <!-- Change Password Modal Begin -->
        <div id="modal-change-password" class="uk-modal-full membership-modal uk-modal" uk-modal="">
            <div class="uk-modal-dialog">
                <button class="uk-modal-close-full uk-close-large uk-icon uk-close" type="button" uk-close=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="close-large"><line fill="none" stroke="#000" stroke-width="1.4" x1="1" y1="1" x2="19" y2="19"></line><line fill="none" stroke="#000" stroke-width="1.4" x1="19" y1="1" x2="1" y2="19"></line></svg></button>

                <div class="row form-modal">
                    <div class="uk-width-1-1 pre-scrollable" style="min-height:650px;">
                        <div class="uk-margin-bottom uk-text-center membership-logo">
                            <!-- ngIf: activeTheme == 'light' -->
                            <!-- ngIf: activeTheme == 'dark' --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png" ng-if="activeTheme == 'dark'" style="max-width:240px;" class="ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/logo.png"><!-- end ngIf: activeTheme == 'dark' -->
                        </div>

                        <div class="modal-content uk-width-1-1 p-5">
                            <form name="passwordChange" ng-submit="passwordChange.$invalid ? '' : password.newPassword != password.confirmPassword ? '' : passwordChangeSubmit(password)" novalidate="" class="ng-pristine ng-invalid ng-invalid-required ng-valid-minlength">
                                <div class="uk-margin-small-bottom">
                                    <h2 class="ng-binding">Şifremi Değiştir</h2>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Eski Şifre</label>

                                    <input class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-minlength" type="text" name="oldPassword" ng-model="password.oldPassword" tabindex="1" autocomplete="off" minlength="6" required="">
                                    <div ng-messages="passwordChange.oldPassword.$error" class="uk-position-relative ng-active">
                                        <!-- ngMessage: required --><div class="form-error-tooltip uk-animation-shake ng-binding ng-scope" ng-message="required">Bu alan boş geçilemez.</div>
                                        <!-- ngMessage: minlength -->
                                    </div>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Şifre</label>

                                    <input class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required ng-valid-minlength" type="password" name="newPassword" ng-model="password.newPassword" tabindex="2" autocomplete="off" minlength="6" required="">
                                    <div ng-messages="passwordChange.newPassword.$error" class="uk-position-relative ng-active">
                                        <!-- ngMessage: required --><div class="form-error-tooltip uk-animation-shake ng-binding ng-scope" ng-message="required">Bu alan boş geçilemez.</div>
                                        <!-- ngMessage: minlength -->
                                    </div>
                                </div>

                                <div class="uk-margin-small-bottom">
                                    <label class="ng-binding">Şifre (Tekrar)</label>
                                    <input type="password" name="confirmPassword" class="uk-input uk-margin-small-top ng-pristine ng-untouched ng-invalid ng-invalid-required" ng-model="password.confirmPassword" tabindex="3" autocomplete="off" required="">
                                    <div ng-messages="passwordChange.confirmPassword.$error" class="uk-position-relative ng-active">
                                        <!-- ngMessage: required --><div class="form-error-tooltip uk-animation-shake ng-binding ng-scope" ng-message="required">Bu alan boş geçilemez.</div>
                                        <div class="form-error-tooltip uk-animation-shake ng-binding ng-hide" ng-show="password.newPassword != password.confirmPassword">Şifreler eşleşmiyor.</div>
                                    </div>
                                </div>

                                <button type="submit" class="na-button uk-button uk-margin-small-top uk-width-1-1 ng-binding">Şifremi Değiştir</button>
                            </form>
                        </div>
                    </div>
                </div>
                <div class="uk-background-cover"></div>
            </div>
        </div>
        <!-- Change Password Modal End -->
        <!-- Notification Modal Begin -->
        <!-- ngIf: notifStatus -->
        <!-- Notification Modal End -->

        <div id="second-modal" class="uk-flex-top uk-modal" uk-modal="">
            <div class="uk-modal-dialog uk-width-auto uk-margin-auto-vertical">
                <button class="uk-modal-close-outside uk-icon uk-close" type="button" uk-close=""><svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg" data-svg="close-icon"><line fill="none" stroke="#000" stroke-width="1.1" x1="1" y1="1" x2="13" y2="13"></line><line fill="none" stroke="#000" stroke-width="1.1" x1="13" y1="1" x2="1" y2="13"></line></svg></button>
                <img alt="" ng-hide="modalLoading">
            </div>
        </div>

        <div id="first-modal" class="uk-flex-top uk-modal" uk-modal="">
            <div class="uk-modal-dialog uk-width-auto uk-margin-auto-vertical">
                <button class="uk-modal-close-outside uk-icon uk-close" type="button" uk-close=""><svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg" data-svg="close-icon"><line fill="none" stroke="#000" stroke-width="1.1" x1="1" y1="1" x2="13" y2="13"></line><line fill="none" stroke="#000" stroke-width="1.1" x1="13" y1="1" x2="1" y2="13"></line></svg></button>
                <img alt="" ng-hide="modalLoading">
            </div>
        </div>

        <style>
            .cf{
                bottom:9%; 
                position:absolute;
                left:calc(50% - 35px);
            }

           .cf a img{
                width:70px;
            }
        </style>
    </div>
</div>

            <!-- Spacer Border -->
            <div class="spacer uk-flex uk-flex-column"></div>

            <!-- Site Sidebar -->
            <!-- ngInclude: undefined --><ng-include src="sidebarTemplateUrl" ng-controller="SidebarCtrl" class="col-2 uk-padding-remove-left ng-scope" style="width:auto;"><div id="siteSidebar" class="col-2 ng-scope uk-offcanvas" uk-offcanvas="mode: push; overlay: true;">

    <div class="uk-offcanvas-bar sidebarWrapper">
        <button class="uk-offcanvas-close uk-close-large uk-icon uk-close" type="button" uk-close=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="close-large"><line fill="none" stroke="#000" stroke-width="1.4" x1="1" y1="1" x2="19" y2="19"></line><line fill="none" stroke="#000" stroke-width="1.4" x1="19" y1="1" x2="1" y2="19"></line></svg></button>

        <!-- Notfication -->
        <!-- ngIf: FDuserLoggedIn -->

        <!-- ngRepeat: menu in menuData --><ul class="sideMenu uk-list ng-scope pt-0" ng-repeat="menu in menuData" ng-class="{'pt-0':$index == 0}">
            <li class="uk-link-heading ng-binding">Spor Bahisleri</li>
            <!-- ngIf: menu.GroupDetail[0].GroupNameTranslation == 'Oyunlar' || menu.GroupDetail[0].GroupNameTranslation == 'Games' -->
            <!-- ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/sports/#!/live" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/sports/#!/live">
                    <span class="menuicon-LiveBet"></span>
                    Canlı Bahis
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/sports/#!/prematch" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/sports/#!/prematch">
                    <span class="menuicon-Bet"></span>
                    Bahis
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail -->
        </ul><!-- end ngRepeat: menu in menuData --><ul class="sideMenu uk-list ng-scope" ng-repeat="menu in menuData" ng-class="{'pt-0':$index == 0}">
            <li class="uk-link-heading ng-binding">Casino</li>
            <!-- ngIf: menu.GroupDetail[0].GroupNameTranslation == 'Oyunlar' || menu.GroupDetail[0].GroupNameTranslation == 'Games' -->
            <!-- ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/casino/#!/live-casino" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/casino/#!/live-casino">
                    <span class="menuicon-LiveCasino"></span>
                    Canlı Casino
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/casino/#!/slots" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/casino/#!/slots">
                    <span class="menuicon-Slots"></span>
                    Slotlar
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail -->
        </ul><!-- end ngRepeat: menu in menuData --><ul class="sideMenu uk-list ng-scope" ng-repeat="menu in menuData" ng-class="{'pt-0':$index == 0}">
            <li class="uk-link-heading ng-binding">Oyunlar</li>
            <!-- ngIf: menu.GroupDetail[0].GroupNameTranslation == 'Oyunlar' || menu.GroupDetail[0].GroupNameTranslation == 'Games' --><li ng-if="menu.GroupDetail[0].GroupNameTranslation == 'Oyunlar' || menu.GroupDetail[0].GroupNameTranslation == 'Games'" class="ng-scope">
                <a href="/casino/#!/slots?provider=-1" ng-click="closeSidebar($event, 'JackpotPlay');" ng-class="{'active' : 'JackpotPlay' == AppCode}">
                    <span class="menuicon-jackpotplay"></span>
                    Jackpot Play
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngIf: menu.GroupDetail[0].GroupNameTranslation == 'Oyunlar' || menu.GroupDetail[0].GroupNameTranslation == 'Games' -->
            <!-- ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/games/#!/aviator" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/games/#!/aviator">
                    <span class="menuicon-Aviator"></span>
                    Aviator
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/games/#!/tombala" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/games/#!/tombala">
                    <span class="menuicon-Bingo"></span>
                    Tombala
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail --><li ng-repeat="menuItem in menu.GroupDetail" class="ng-scope">
                <a ng-href="/games/#!/tvbet" ng-click="closeSidebar($event, menuItem.MenuName);" ng-class="{'active' : menuItem.MenuName == AppCode}" class="ng-binding" href="/games/#!/tvbet">
                    <span class="menuicon-TvBet"></span>
                    TVBet
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: menuItem in menu.GroupDetail -->
        </ul><!-- end ngRepeat: menu in menuData -->

        <!-- Other -->
        <ul class="sideMenu uk-list">
            <li class="uk-link-heading ng-binding">Diğer</li>
            <li>
                <a href="/promotions/#!/list" ng-click="closeSidebar($event);" ng-class="{'active' : AppCode == 'Promotions'}" class="ng-binding">
                    <span class="menuicon-promo"></span>
                    Promosyonlar
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li>
            <li>
                <a href="/contents/#!/" ng-click="closeSidebar($event);" ng-class="{'active' : AppCode == 'About'}" class="ng-binding">
                    <span class="menuicon-info"></span>
                    Hakkımızda
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li>
            <li>
                <a href="/contents/#!/site-content" ng-click="closeSidebar($event);" ng-class="{'active' : AppCode == 'Contents'}" class="ng-binding">
                    <span class="menuicon-star"></span>
                    İçerikler
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li>
            <!-- ngRepeat: customMenu in customMenuData --><li ng-repeat="customMenu in customMenuData" class="ng-scope">
                <a ng-href="https://neyinecark3.com/" ng-attr-target="{{(customMenu.UniqueString) ? '_blank' : undefined}}" ng-click="closeSidebar($event);" class="ng-binding" href="https://neyinecark3.com/" target="_blank">
                    <span class="menuicon-wheel-of-fortune"></span>
                    Hediye Çarkı
                    <span class="nav-icon float-right uk-icon" uk-icon="chevron-right"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span>
                </a>
            </li><!-- end ngRepeat: customMenu in customMenuData -->
        </ul>

        <!-- Language -->
        <div class="sideMenu pb-3">
            <div class="uk-link-heading ng-binding">Dil Seçimi</div>
            <select class="uk-select mt-2 ng-pristine ng-untouched ng-valid" ng-options="lang.name for lang in languagesList" ng-change="changeLanguage(selectedLang.code)" ng-model="selectedLang"><option label="English" value="object:40">English</option><option label="Türkçe" value="object:41" selected="selected">Türkçe</option></select>
        </div>

        <!-- Socials -->
        <!-- ngIf: socialsActive --><div class="sideMenu socials pb-3 ng-scope" ng-if="socialsActive">
            <div class="uk-link-heading">Takip Et</div>

            <!-- ngIf: facebookUrl -->
            <!-- ngIf: twitterUrl --><a href="https://twitter.com/neyineresmi" target="_blank" ng-if="twitterUrl" class="ng-scope"> <i class="fab fa-twitter"></i> </a><!-- end ngIf: twitterUrl -->
            <!-- ngIf: instagramUrl --><a href="https://www.instagram.com/neyinedestek/" target="_blank" ng-if="instagramUrl" class="ng-scope"> <i class="fab fa-instagram"></i> </a><!-- end ngIf: instagramUrl -->
            <!-- ngIf: telegramUrl --><a href="https://t.me/NeyineDestek " target="_blank" ng-if="telegramUrl" class="ng-scope"> <i class="fab fa-telegram-plane"></i> </a><!-- end ngIf: telegramUrl -->
            <!-- ngIf: viberUrl -->
            <!-- ngIf: whatsappUrl --><a href="https://wa.me/+905338466425" target="_blank" ng-if="whatsappUrl" class="ng-scope"> <i class="fab fa-whatsapp"></i> </a><!-- end ngIf: whatsappUrl -->
            <!-- ngIf: youtubeUrl --><a href="https://bit.ly/3Tzy2eC" target="_blank" ng-if="youtubeUrl" class="ng-scope"> <i class="fab fa-youtube"></i> </a><!-- end ngIf: youtubeUrl -->
        </div><!-- end ngIf: socialsActive -->

        <!-- Theme Setting-->
        <div class="theme-switcher uk-flex uk-flex-between uk-margin-top pb-2">
            <span class="ng-binding">Koyu</span>
            <label id="switch">
                <input type="checkbox" ng-model="siteColor" ng-checked="siteColor" ng-change="toggleTheme()" id="themeSlider" class="ng-pristine ng-untouched ng-valid">
                <span class="slider round"></span>
            </label>
            <span class="ng-binding">Açık</span>
        </div>
    </div>
</div>

<!-- Secure Login Modal -->
<div id="secure-login-modal" uk-modal="esc-close: false; bg-close: false;" class="ng-scope uk-modal">
    <div class="uk-modal-dialog uk-modal-body payment-modal p-0">
        <button class="uk-modal-close-default uk-icon uk-close" type="button" uk-close=""><svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg" data-svg="close-icon"><line fill="none" stroke="#000" stroke-width="1.1" x1="1" y1="1" x2="13" y2="13"></line><line fill="none" stroke="#000" stroke-width="1.1" x1="13" y1="1" x2="1" y2="13"></line></svg></button>

        <!-- MODAL HEAD -->
        <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/user-activation.png" class="w-100" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/user-activation.png">
        <div class="w-100 payment-title p-4 pt-2 pb-2 uk-flex uk-flex-between uk-flex-middle">
            <h3 class="uk-modal-title m-0"><b class="ng-binding">Güvenli Giriş</b></h3>
        </div>

        <!-- STEP 1 -->
        <!-- ngIf: !userService.userModel.naSecurityActive --><div class="p-4 ng-scope" ng-show="userService.userModel.activeSecurityStep == 1" ng-if="!userService.userModel.naSecurityActive">
            <p class="ng-binding">Hesabınız, kişisel bilgileriniz ve oyuncu bakiyenizi, olası şifre çalınma durumunda koruma altına almak için, Güvenli Giriş özelliğini aktif ediniz!</p>
            <p class="ng-binding">Mail adresiniz güncel değilse, Canlı Destek hattımıza bağlanarak hızlıca güncelleyebilirsiniz.</p>

            <div class="m-0 uk-child-width-1-1 uk-grid uk-grid-stack" uk-grid="">
                <div class="p-1">
                    <form name="sendActivationCodeForm" ng-submit="sendActivationCodeForm.$invalid ? '' : userService.playerAcceptVerification(userService.userModel.username)" novalidate="" class="ng-pristine ng-valid">
                        <button class="uk-button na-button w-100">
                            <span uk-icon="arrow-right" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="arrow-right"><polyline fill="none" stroke="#000" points="10 5 15 9.5 10 14"></polyline><line fill="none" stroke="#000" x1="4" y1="9.5" x2="15" y2="9.5"></line></svg></span>
                            <b class="ng-binding">Aktivasyon Kodu Gönder</b>
                        </button>
                    </form>
                </div>

                <!-- ngIf: userService.userModel.naSecurityActive == null --><div class="mt-2 uk-padding-remove ng-scope" ng-if="userService.userModel.naSecurityActive == null">
                    <button class="uk-button na-alt-button uk-modal-close w-100" ng-click="userService.setVerificationStatus()">
                        <span uk-icon="close" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="close"><path fill="none" stroke="#000" stroke-width="1.06" d="M16,16 L4,4"></path><path fill="none" stroke="#000" stroke-width="1.06" d="M16,4 L4,16"></path></svg></span>
                        <b class="ng-binding">Tekrar Gösterme</b>
                    </button>
                </div><!-- end ngIf: userService.userModel.naSecurityActive == null -->
            </div>
        </div><!-- end ngIf: !userService.userModel.naSecurityActive -->

        <!-- STEP 2 -->
        <!-- ngIf: !userService.userModel.naSecurityActive --><div class="p-4 ng-scope ng-hide" ng-show="userService.userModel.activeSecurityStep == 2" ng-if="!userService.userModel.naSecurityActive">
            <p class="ng-binding">Hesabınız, kişisel bilgileriniz ve oyuncu bakiyenizi, olası şifre çalınma durumunda koruma altına almak için, Güvenli Giriş özelliğini aktif ediniz!</p>
            <p class="ng-binding">Mail adresiniz güncel değilse, Canlı Destek hattımıza bağlanarak hızlıca güncelleyebilirsiniz.</p>

            <form name="confirmActivationCodeForm" ng-submit="confirmActivationCodeForm.$invalid ? '' : userService.playerEnterVerificationCode(userService.userModel.confirmationCode)" novalidate="" class="ng-pristine ng-valid ng-valid-maxlength">
                <div class="uk-margin-bottom">
                    <input class="uk-input ng-pristine ng-untouched ng-valid ng-valid-maxlength" maxlength="20" type="text" ng-model="userService.userModel.confirmationCode" placeholder="Aktivasyon Kodu">
                </div>

                <div class="m-0 uk-child-width-1-1 uk-grid uk-grid-stack" uk-grid="">
                    <div class="p-1">
                        <button class="uk-button na-button w-100">
                            <span uk-icon="check" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="check"><polyline fill="none" stroke="#000" stroke-width="1.1" points="4,10 8,15 17,4"></polyline></svg></span>
                            <b class="ng-binding">Onayla</b>
                        </button>
                    </div>
                </div>
            </form>
        </div><!-- end ngIf: !userService.userModel.naSecurityActive -->

        <!-- STEP 3 -->
        <!-- ngIf: userService.userModel.naSecurityActive || userService.userModel.activeSecurityStep == 3 -->
    </div>
</div></ng-include>

            <!-- Site Content -->

<slider-widget page="home" class="ng-scope ng-isolate-scope"><!-- Banner Alternative Carousel -->
<!-- ngIf: sliderOptions.Data --><div class="splide bannerCarousel mb-3 ng-scope splide--slide splide--ltr splide--draggable is-active is-initialized" ng-if="sliderOptions.Data" data-splide="{&quot;perPage&quot;: 2}" id="splide01">

        <ul class="splide__list" id="splide01-list" style="transform: translateX(0px);">

                <a href="/casino/#!/slots?provider=93" url-target=""><img ng-src="https://cdn.nagcdn.com/neyine/slider/home/bellanasyfslot.png" alt="" src="https://cdn.nagcdn.com/neyine/slider/home/bellanasyfslot.png"></a>
            <!-- end ngRepeat: item in sliderOptions.Data --><li class="splide__slide ng-scope is-visible is-next" ng-repeat="item in sliderOptions.Data" id="splide01-slide02" style="margin-right: 15px; width: calc(50% - 7.5px);" tabindex="0">
                <a href="/promotions/#!/list?id=947" url-target=""><img ng-src="https://cdn.nagcdn.com/neyine/slider/home/freespinanasyf.png" alt="" src="https://cdn.nagcdn.com/neyine/slider/home/freespinanasyf.png"></a>
            </li><!-- end ngRepeat: item in sliderOptions.Data --><li class="splide__slide ng-scope" ng-repeat="item in sliderOptions.Data" id="splide01-slide03" style="margin-right: 15px; width: calc(50% - 7.5px);" aria-hidden="true">
                <a href="/promotions/#!/list?id=967" url-target="" tabindex="-1"><img ng-src="https://cdn.nagcdn.com/neyine/slider/home/arkadas.png" alt="" src="https://cdn.nagcdn.com/neyine/slider/home/arkadas.png"></a>
            </li><!-- end ngRepeat: item in sliderOptions.Data -->
        </ul>
    </div>

    <div class="splide__arrows">
        <button class="splide__arrow splide__arrow--prev uk-slidenav" aria-controls="splide01-track" aria-label="Go to last slide"><span uk-icon="chevron-right" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span></button>
        <button class="splide__arrow splide__arrow--next uk-slidenav" aria-controls="splide01-track" aria-label="Next slide"><span uk-icon="chevron-right" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span></button>
    </div>
<!-- end ngIf: sliderOptions.Data -->
</slider-widget>

<!-- content -->
<div class="contentWrapper pt-0 ng-scope">
    <!-- Categories -->
    <!-- ngIf: widget.shortcuts.status --><div class="uk-width-1-1 pt-3 uk-child-width-1-1 order-2" ng-if="widget.shortcuts.status" style="position:relative;">
        <h4 class="main-page-title ng-binding">Kategoriler</h4>

        <div class="casino-type-navigation homepage-navigation" ng-show="!loading">
            <div class="splide is-initialized splide--slide splide--ltr splide--draggable is-active" id="splide02">
                <div class="splide__track" id="splide02-track" style="padding-left: 0px; padding-right: 0px;">
                    <ul class="splide__list" id="splide02-list" style="transform: translateX(0px);">
                        <!-- ngRepeat: menu in menuData --><li class="splide__slide ng-scope is-active is-visible" ng-repeat="menu in menuData" id="splide02-slide01" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" tabindex="0">
                            <a href="https://www.neyine491.com/sports/#!/live" class="ng-binding">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/LiveBet.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/LiveBet.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Canlı Bahis
                            </a>
                        </li><!-- end ngRepeat: menu in menuData --><li class="splide__slide ng-scope is-visible is-next" ng-repeat="menu in menuData" id="splide02-slide02" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" tabindex="0">
                            <a href="/sports/#!/prematch" class="ng-binding">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Bet.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Bet.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Bahis
                            </a>
                        </li><!-- end ngRepeat: menu in menuData --><li class="splide__slide ng-scope is-visible" ng-repeat="menu in menuData" id="splide02-slide03" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" tabindex="0">
                            <a href="https://www.neyine491.com/casino/#!/live-casino" class="ng-binding">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/LiveCasino.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/LiveCasino.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Canlı Casino
                            </a>
                        </li><!-- end ngRepeat: menu in menuData --><li class="splide__slide ng-scope is-visible" ng-repeat="menu in menuData" id="splide02-slide04" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" tabindex="0">
                            <a href="/casino/#!/slots" class="ng-binding">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Slots.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Slots.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Slotlar
                            </a>
                        </li><!-- end ngRepeat: menu in menuData --><li class="splide__slide ng-scope is-visible" ng-repeat="menu in menuData" id="splide02-slide05" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" tabindex="0">
                            <a href="/games/#!/aviator" class="ng-binding">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Aviator.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Aviator.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Aviator
                            </a>
                        </li><!-- end ngRepeat: menu in menuData --><li class="splide__slide ng-scope is-visible" ng-repeat="menu in menuData" id="splide02-slide06" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" tabindex="0">
                            <a href="/games/#!/tombala" class="ng-binding">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Bingo.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Bingo.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Tombala
                            </a>
                        </li><!-- end ngRepeat: menu in menuData --><li class="splide__slide ng-scope" ng-repeat="menu in menuData" id="splide02-slide07" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" aria-hidden="true">
                            <a href="/games/#!/tvbet" class="ng-binding" tabindex="-1">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/TvBet.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/TvBet.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                TVBet
                            </a>
                        </li><!-- end ngRepeat: menu in menuData -->
                        <li class="splide__slide" id="splide02-slide08" style="margin-right: 10px; width: calc(16.6667% - 8.33333px);" aria-hidden="true">
                            <a href="/promotions/#!/list" class="ng-binding" tabindex="-1">
                                <!-- ngIf: !isNewYearMode --><img ng-src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Promotions.png" ng-if="!isNewYearMode" class="mb-1 ng-scope" src="https://cdn.nagcdn.com/ngamingbase/neyine/assets/images/category_icons/Promotions.png"><!-- end ngIf: !isNewYearMode -->
                                <!-- ngIf: isNewYearMode -->
                                Promosyonlar
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="splide__arrows">
                    <button class="splide__arrow splide__arrow--prev uk-slidenav" aria-controls="splide02-track" aria-label="Go to last slide"><span uk-icon="chevron-right" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span></button>
                    <button class="splide__arrow splide__arrow--next uk-slidenav" aria-controls="splide02-track" aria-label="Next slide"><span uk-icon="chevron-right" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="chevron-right"><polyline fill="none" stroke="#000" stroke-width="1.03" points="7 4 13 10 7 16"></polyline></svg></span></button>
                </div>
            </div>
        </div>

        <!-- loading -->
        <!-- ngIf: loading -->
    </div><!-- end ngIf: widget.shortcuts.status -->

    <!-- Popular Events & Live Events & Winning Coupons -->
    <!-- ngIf: widget.liveEvents.status --><div class="col-12 pt-3 order-6" ng-if="widget.liveEvents.status">
        <div class="uk-child-width-1-3@m uk-grid-small uk-grid" uk-grid="">
            <div class="uk-first-column">
                <live-events><div class="widget-events live">
    <h4 class="widget-title mt-3 ng-binding">Canlı Bahisler</h4>
    <div class="widget-title-background"></div>

    <!-- loading -->
    <!-- ngIf: !liveEventData && !noData -->

    <div tabindex="-1" uk-slider="finite: false; autoplay:true;" class="uk-slider uk-slider-container">
        <div class="uk-position-relative uk-visible-toggle" tabindex="-1">

            <!-- ngIf: liveEventData && !noData --><ul class="uk-slider-items uk-child-width-1-1 ng-scope" ng-if="liveEventData &amp;&amp; !noData" style="transform: translate3d(-398.859px, 0px, 0px);">
                <!-- ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1" style="order: 1;">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Gil Vicente Barcelos</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">90'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">2. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">2:2</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">FC Arouca</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/gil-vicente-barcelos-vs-fc-arouca/4551867" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">10.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/gil-vicente-barcelos-vs-fc-arouca/4551867" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">1.10</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/gil-vicente-barcelos-vs-fc-arouca/4551867" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">9.25</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1" style="order: 1;">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Sport Huancayo</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">55'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">2. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">1:0</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Carlos Mannucci</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/sport-huancayo-vs-carlos-mannucci/4577728" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">1.18</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/sport-huancayo-vs-carlos-mannucci/4577728" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">6.50</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/sport-huancayo-vs-carlos-mannucci/4577728" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">27.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1" style="order: 1;">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">CD Universidad Cesar Vallejo</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">42'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">1. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">0:0</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Sporting Cristal</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/cd-universidad-cesar-vallejo-vs-sporting-cris/4615348" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">9.75</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/cd-universidad-cesar-vallejo-vs-sporting-cris/4615348" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">4.60</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/cd-universidad-cesar-vallejo-vs-sporting-cris/4615348" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">1.40</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1" style="order: 1;">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Kolombiya</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">15'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">1. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">1:0</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Venezuela</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/kolombiya-vs-venezuela/4611700" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">1.20</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/kolombiya-vs-venezuela/4611700" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">7.75</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/kolombiya-vs-venezuela/4611700" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">17.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1" style="order: 1;">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Leones FC U19</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">59'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">2. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">1:1</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Aguilas Doradas U19</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/leones-fc-u19-vs-aguilas-doradas-u19/4614249" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">3.20</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/leones-fc-u19-vs-aguilas-doradas-u19/4614249" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">2.45</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/leones-fc-u19-vs-aguilas-doradas-u19/4614249" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">3.25</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1" style="">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Atletico FC</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">Devre Arasi</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">0:2</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Tigres FC</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/atletico-fc-vs-tigres-fc/4597352" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">1.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/atletico-fc-vs-tigres-fc/4597352" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">1.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/atletico-fc-vs-tigres-fc/4597352" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">1.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope uk-active" tabindex="-1" style="">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">CD Universitario II</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">45'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">1. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">1:2</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">CD Bocas FC</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/cd-universitario-ii-vs-cd-bocas-fc/4617990" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">13.00</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/cd-universitario-ii-vs-cd-bocas-fc/4617990" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">5.80</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/cd-universitario-ii-vs-cd-bocas-fc/4617990" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">1.27</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Los Santos FC</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">15'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">1. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">1:0</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Veraguas United FC B</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/los-santos-fc-vs-veraguas-united-fc-b/4619115" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">1.90</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/los-santos-fc-vs-veraguas-united-fc-b/4619115" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">4.05</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/los-santos-fc-vs-veraguas-united-fc-b/4619115" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">3.90</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Galvez EC AC</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt --><span ng-if="item.Mt" class="ng-binding ng-scope">45'</span><!-- end ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">1. Devre</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding">1:1</span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">AD Vasco Da Gama AC</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/galvez-ec-ac-vs-ad-vasco-da-gama-ac/4611688" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">3.30</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/galvez-ec-ac-vs-ad-vasco-da-gama-ac/4611688" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">3.45</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/galvez-ec-ac-vs-ad-vasco-da-gama-ac/4611688" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">2.30</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 --><!-- ngIf: item.Od != '' --><li ng-repeat="item in liveEventData| limitTo: 10" ng-if="item.Od != ''" class="ng-scope" tabindex="-1">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Futbol</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/home_team_logo2.png">
                                    <p class="team-names ng-binding">Deportivo Santani</p>
                                </div>
                                <div class="event-date">
                                    <!-- ngIf: item.Mt -->
                                    <br>
                                    <!-- ngIf: item.Ms --><span ng-if="item.Ms" class="ng-binding ng-scope">Baslamadi</span><!-- end ngIf: item.Ms -->
                                    <br>
                                    <span class="ng-binding"></span>
                                </div>
                                <div>
                                    <img ng-src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png" class="team-img" width="50" src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/away_team_logo.png">
                                    <p class="team-names ng-binding">Club Fernando</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/deportivo-santani-vs-club-fernando/4611689" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">2.80</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/deportivo-santani-vs-club-fernando/4611689" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">3.45</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><a href="/sports/#!/live-detail/deportivo-santani-vs-club-fernando/4611689" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.Od" ng-if="$index < 3">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">2.65</span>
                                </a><!-- end ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od --><!-- ngIf: $index < 3 --><!-- end ngRepeat: odd in item.Od -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngIf: item.Od != '' --><!-- end ngRepeat: item in liveEventData| limitTo: 10 -->
            </ul><!-- end ngIf: liveEventData && !noData -->
            
            <!-- ngIf: noData -->
        </div>

        <!-- ngIf: !noData --><a class="uk-position-center-left uk-hidden-hover mt-3 ng-scope uk-icon uk-slidenav-previous uk-slidenav" ng-if="!noData" href="#" uk-slidenav-previous="" uk-slider-item="previous"><svg width="14px" height="24px" viewBox="0 0 14 24" xmlns="http://www.w3.org/2000/svg" data-svg="slidenav-previous"><polyline fill="none" stroke="#000" stroke-width="1.4" points="12.775,1 1.225,12 12.775,23 "></polyline></svg></a><!-- end ngIf: !noData -->
        <!-- ngIf: !noData --><a class="uk-position-center-right uk-hidden-hover mt-3 ng-scope uk-icon uk-slidenav-next uk-slidenav" ng-if="!noData" href="#" uk-slidenav-next="" uk-slider-item="next"><svg width="14px" height="24px" viewBox="0 0 14 24" xmlns="http://www.w3.org/2000/svg" data-svg="slidenav-next"><polyline fill="none" stroke="#000" stroke-width="1.4" points="1.225,23 12.775,12 1.225,1 "></polyline></svg></a><!-- end ngIf: !noData -->
    </div>
</div>




</live-events>
            </div>

            <div>
                <winning-coupon><div class="widget-events coupon">
    <h4 class="widget-title mt-3 ng-binding">Kazanan Kuponlar</h4>

    <!-- loading -->
    <!-- ngIf: !winningCouponData && !winningCouponNoData -->

    <!-- ngIf: winningCouponData && !winningCouponNoData --><div tabindex="-1" uk-slider="finite: false; autoplay:true; autoplay-interval:3000" ng-if="winningCouponData &amp;&amp; !winningCouponNoData" class="ng-scope uk-slider uk-slider-container">
        <div class="uk-position-relative uk-visible-toggle" tabindex="-1">

            <ul class="uk-slider-items uk-child-width-1-1" style="transform: translate3d(-398.859px, 0px, 0px);">
                <li tabindex="-1" class="uk-active" style="order: 1;">
                    <table class="uk-table uk-table-divider uk-table-small uk-table-striped">
                        <thead>
                            <tr>
                                <th class="ng-binding">Tarih</th>
                                <th class="ng-binding">Miktar</th>
                                <th class="ng-binding">Kazanç</th>
                                <!--<th>{{'page_el_couponNo' | translate}}</th>-->
                            </tr>
                        </thead>
                        <tbody>
                            <!-- ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? false : true" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">8,600.00 </td>
                                <td class="ng-binding">18,060.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? false : true" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">5,000.00 </td>
                                <td class="ng-binding">10,750.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? false : true" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">2,000.00 </td>
                                <td class="ng-binding">3,880.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? false : true" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">1,133.00 </td>
                                <td class="ng-binding">3,002.45 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? false : true --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? false : true" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">1,000.00 </td>
                                <td class="ng-binding">1,750.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: item in winningCouponData -->
                        </tbody>
                    </table>
                </li>

                <li tabindex="-1" class="">
                    <table class="uk-table uk-table-divider uk-table-small uk-table-striped">
                        <thead>
                            <tr>
                                <th class="ng-binding">Tarih</th>
                                <th class="ng-binding">Miktar</th>
                                <th class="ng-binding">Kazanç</th>
                                <!--<th>{{'page_el_couponNo' | translate}}</th>-->
                            </tr>
                        </thead>
                        <tbody>
                            <!-- ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? true : false" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">7,000.00 </td>
                                <td class="ng-binding">35,910.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? true : false" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">10,000.00 </td>
                                <td class="ng-binding">14,800.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? true : false" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">3,000.00 </td>
                                <td class="ng-binding">5,850.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? true : false" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">1,888.00 </td>
                                <td class="ng-binding">3,115.20 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><tr ng-repeat="item in winningCouponData" ng-if="$index % 2 == 0 ? true : false" uk-toggle="target: #winning-coupon-detail-modal" ng-click="winCouponWidgetModal($event, item.Id)" class="ng-scope" aria-expanded="false">
                                <td class="ng-binding">26/04/2024</td>
                                <td class="ng-binding">1,500.00 </td>
                                <td class="ng-binding">2,130.00 </td>
                                <!--<td class="">{{item.Id}}</td>-->
                            </tr><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: item in winningCouponData -->
                        </tbody>
                    </table>
                </li>
            </ul>

            <!-- ngIf: winningCouponNoData -->
        </div>

        <ul class="uk-slider-nav uk-dotnav"><li uk-slider-item="0" class="uk-active"><a href=""></a></li><li uk-slider-item="1" class=""><a href=""></a></li></ul>
    </div><!-- end ngIf: winningCouponData && !winningCouponNoData -->

</div>


<div id="winning-coupon-detail-modal" uk-modal="" class="uk-modal">
    <div class="uk-modal-dialog uk-modal-body">
        <button class="uk-modal-close-default uk-icon uk-close" type="button" uk-close=""><svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg" data-svg="close-icon"><line fill="none" stroke="#000" stroke-width="1.1" x1="1" y1="1" x2="13" y2="13"></line><line fill="none" stroke="#000" stroke-width="1.1" x1="13" y1="1" x2="1" y2="13"></line></svg></button>

        <h2 class="uk-modal-title ng-binding">Kupon No: </h2>

        <div class="table-responsive">
            <!-- ngIf: winningCouponDetailData -->
        </div>

        <!-- loading -->
        <!-- ngIf: !winningCouponDetailData && !winningCouponModalNoData --><div class="w-100 h-100 d-flex justify-content-center align-items-center accordion-body-preloader ng-scope" ng-if="!winningCouponDetailData &amp;&amp; !winningCouponModalNoData" style="min-height:200px">
            <md-progress-circular md-mode="indeterminate" class="progress-circular">
        </md-progress-circular></div><!-- end ngIf: !winningCouponDetailData && !winningCouponModalNoData -->

        <!-- no data -->
        <!-- ngIf: winningCouponModalNoData -->
    </div>
</div></winning-coupon>
            </div>

            <div>
                <popular-events><div class="widget-events popular">
    <h4 class="widget-title mt-3 ng-binding">Öne Çıkarılan Bahisler</h4>
    <div class="widget-title-background"></div>

    <!-- loading -->
    <!-- ngIf: !popularEventData && !noData -->

    <div tabindex="-1" uk-slider="finite: false; autoplay:true;" class="uk-slider uk-slider-container">
        <div class="uk-position-relative uk-visible-toggle" tabindex="-1">

            <!-- ngIf: popularEventData && !noData --><ul class="uk-slider-items uk-child-width-1-1 ng-scope" ng-if="popularEventData &amp;&amp; !noData" style="transform: translate3d(-398.859px, 0px, 0px);">
                <!-- ngRepeat: item in popularEventData --><li ng-repeat="item in popularEventData" class="ng-scope" tabindex="-1" style="">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Kanada Premier Lig</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <!-- ngIf: item.HomeId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/543891.png" class="team-img ng-scope" alt="" ng-if="item.HomeId" src="https://img-cdn001.akamaized.net/ls/crest/medium/543891.png"><!-- end ngIf: item.HomeId -->
                                    <!-- ngIf: !item.HomeId -->
                                    <p class="team-names ng-binding">York United FC</p>
                                </div>
                                <div class="event-date ng-binding">
                                    27/04/2024
                                    <br>
                                    02:00
                                </div>
                                <div>
                                    <!-- ngIf: item.AwayId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/986603.png" class="team-img ng-scope" alt="" ng-if="item.AwayId" src="https://img-cdn001.akamaized.net/ls/crest/medium/986603.png"><!-- end ngIf: item.AwayId -->
                                    <!-- ngIf: !item.AwayId -->
                                    <p class="team-names ng-binding">Vancouver FC</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=York United FC" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">2.18</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=York United FC" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">3.32</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=York United FC" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">2.71</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngRepeat: item in popularEventData --><li ng-repeat="item in popularEventData" class="ng-scope uk-active" tabindex="-1" style="">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Premier Lig</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <!-- ngIf: item.HomeId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/3163.png" class="team-img ng-scope" alt="" ng-if="item.HomeId" src="https://img-cdn001.akamaized.net/ls/crest/medium/3163.png"><!-- end ngIf: item.HomeId -->
                                    <!-- ngIf: !item.HomeId -->
                                    <p class="team-names ng-binding">O´higgins</p>
                                </div>
                                <div class="event-date ng-binding">
                                    27/04/2024
                                    <br>
                                    02:00
                                </div>
                                <div>
                                    <!-- ngIf: item.AwayId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/3153.png" class="team-img ng-scope" alt="" ng-if="item.AwayId" src="https://img-cdn001.akamaized.net/ls/crest/medium/3153.png"><!-- end ngIf: item.AwayId -->
                                    <!-- ngIf: !item.AwayId -->
                                    <p class="team-names ng-binding">Union Espanola</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=O´higgins" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">2.10</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=O´higgins" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">3.19</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=O´higgins" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">3.17</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngRepeat: item in popularEventData --><li ng-repeat="item in popularEventData" class="ng-scope" tabindex="-1" style="">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Brasilero Seri B</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <!-- ngIf: item.HomeId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/1972.png" class="team-img ng-scope" alt="" ng-if="item.HomeId" src="https://img-cdn001.akamaized.net/ls/crest/medium/1972.png"><!-- end ngIf: item.HomeId -->
                                    <!-- ngIf: !item.HomeId -->
                                    <p class="team-names ng-binding">Guarani FC SP</p>
                                </div>
                                <div class="event-date ng-binding">
                                    27/04/2024
                                    <br>
                                    03:00
                                </div>
                                <div>
                                    <!-- ngIf: item.AwayId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/21845.png" class="team-img ng-scope" alt="" ng-if="item.AwayId" src="https://img-cdn001.akamaized.net/ls/crest/medium/21845.png"><!-- end ngIf: item.AwayId -->
                                    <!-- ngIf: !item.AwayId -->
                                    <p class="team-names ng-binding">Chapecoense SC</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=Guarani FC SP" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">2.08</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=Guarani FC SP" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">2.91</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=Guarani FC SP" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">3.54</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngRepeat: item in popularEventData --><li ng-repeat="item in popularEventData" class="ng-scope" tabindex="-1" style="">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Brasilero Seri B</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <!-- ngIf: item.HomeId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/2025.png" class="team-img ng-scope" alt="" ng-if="item.HomeId" src="https://img-cdn001.akamaized.net/ls/crest/medium/2025.png"><!-- end ngIf: item.HomeId -->
                                    <!-- ngIf: !item.HomeId -->
                                    <p class="team-names ng-binding">Ituano FC SP</p>
                                </div>
                                <div class="event-date ng-binding">
                                    27/04/2024
                                    <br>
                                    01:00
                                </div>
                                <div>
                                    <!-- ngIf: item.AwayId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/39634.png" class="team-img ng-scope" alt="" ng-if="item.AwayId" src="https://img-cdn001.akamaized.net/ls/crest/medium/39634.png"><!-- end ngIf: item.AwayId -->
                                    <!-- ngIf: !item.AwayId -->
                                    <p class="team-names ng-binding">Operario Ferroviario EC PR</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=Ituano FC SP" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">2.52</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=Ituano FC SP" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">2.82</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=Ituano FC SP" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">2.81</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngRepeat: item in popularEventData --><li ng-repeat="item in popularEventData" class="ng-scope" tabindex="-1">
                    <div class="uk-panel">
                        <div class="teams">
                            <div class="event-info uk-child-width-1-1">
                                <div class="uk-text-center ng-binding">Brasilero Seri B</div>
                            </div>

                            <div class="uk-child-width-expand uk-position-relative mt-0 uk-grid" uk-grid="">
                                <div class="uk-first-column">
                                    <!-- ngIf: item.HomeId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/1959.png" class="team-img ng-scope" alt="" ng-if="item.HomeId" src="https://img-cdn001.akamaized.net/ls/crest/medium/1959.png"><!-- end ngIf: item.HomeId -->
                                    <!-- ngIf: !item.HomeId -->
                                    <p class="team-names ng-binding">SC Recife PE</p>
                                </div>
                                <div class="event-date ng-binding">
                                    27/04/2024
                                    <br>
                                    01:00
                                </div>
                                <div>
                                    <!-- ngIf: item.AwayId --><img ng-src="https://img-cdn001.akamaized.net/ls/crest/medium/2021.png" class="team-img ng-scope" alt="" ng-if="item.AwayId" src="https://img-cdn001.akamaized.net/ls/crest/medium/2021.png"><!-- end ngIf: item.AwayId -->
                                    <!-- ngIf: !item.AwayId -->
                                    <p class="team-names ng-binding">Vila Nova FC GO</p>
                                </div>
                            </div>

                            <div class="rates uk-child-width-expand mt-0 uk-grid" uk-grid="">
                                <!-- ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=SC Recife PE" class="bet-btn uk-button ng-scope uk-first-column" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">1</sub>
                                    <span class="ng-binding">1.61</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=SC Recife PE" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">X</sub>
                                    <span class="ng-binding">3.48</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds --><a href="/sports/#!/prematch?search=SC Recife PE" class="bet-btn uk-button ng-scope" ng-repeat="odd in item.ShortOdds">
                                    <sub class="ng-binding">2</sub>
                                    <span class="ng-binding">5.10</span>
                                </a><!-- end ngRepeat: odd in item.ShortOdds -->
                            </div>
                        </div>
                    </div>
                </li><!-- end ngRepeat: item in popularEventData -->
            </ul><!-- end ngIf: popularEventData && !noData -->

            <!-- ngIf: noData -->
        </div>

        <!-- ngIf: popularEventData && !noData --><a class="uk-position-center-left uk-hidden-hover mt-3 ng-scope uk-icon uk-slidenav-previous uk-slidenav" ng-if="popularEventData &amp;&amp; !noData" href="#" uk-slidenav-previous="" uk-slider-item="previous"><svg width="14px" height="24px" viewBox="0 0 14 24" xmlns="http://www.w3.org/2000/svg" data-svg="slidenav-previous"><polyline fill="none" stroke="#000" stroke-width="1.4" points="12.775,1 1.225,12 12.775,23 "></polyline></svg></a><!-- end ngIf: popularEventData && !noData -->
        <!-- ngIf: popularEventData && !noData --><a class="uk-position-center-right uk-hidden-hover mt-3 ng-scope uk-icon uk-slidenav-next uk-slidenav" ng-if="popularEventData &amp;&amp; !noData" href="#" uk-slidenav-next="" uk-slider-item="next"><svg width="14px" height="24px" viewBox="0 0 14 24" xmlns="http://www.w3.org/2000/svg" data-svg="slidenav-next"><polyline fill="none" stroke="#000" stroke-width="1.4" points="1.225,23 12.775,12 1.225,1 "></polyline></svg></a><!-- end ngIf: popularEventData && !noData -->
    </div>
</div></popular-events>
            </div>
        </div>
    </div><!-- end ngIf: widget.liveEvents.status -->

    <!-- Top Leagues -->
    <!-- ngIf: widget.topLeagues.status --><div class="uk-child-width-1-1 uk-width-1-1 order-5" ng-if="widget.topLeagues.status">
        <top-leagues><h4 class="main-page-title mt-3 ng-binding">Favori Ligler</h4>

<div class="widget-top-leagues">
    <div class="uk-grid-collapse uk-child-width-1-2 uk-child-width-1-6@l uk-child-width-1-3@m uk-child-width-1-2@s uk-child-width-1-2@xs uk-grid" uk-grid="">
        <!-- ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><a href="/sports/#!/prematch/futbol/1/ingiltere/1/premier-lig/1?comingHour=All" class="league ng-binding ng-scope uk-first-column" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? true : false">
            <i class="flag flag-eng"></i>
            Premier Lig
        </a><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><a href="/sports/#!/prematch/futbol/1/uluslararasi-kulupler/294/uefa-sampiyonlar-ligi/14?comingHour=All" class="league ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? true : false">
            <i class="flag flag-"></i>
            UEFA Şampiyonlar Ligi
        </a><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><a href="/sports/#!/prematch/futbol/1/ispanya/31/laliga/25?comingHour=All" class="league ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? true : false">
            <i class="flag flag-esp"></i>
            LaLiga
        </a><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><a href="/sports/#!/prematch/futbol/1/almanya/29/bundesliga/31?comingHour=All" class="league ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? true : false">
            <i class="flag flag-deu"></i>
            Bundesliga
        </a><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><a href="/sports/#!/prematch/futbol/1/turkiye/45/super-lig/46?comingHour=All" class="league ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? true : false">
            <i class="flag flag-tur"></i>
            Süper Lig
        </a><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><a href="/sports/#!/prematch/futbol/1/turkiye/45/1-lig/72?comingHour=All" class="league ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? true : false">
            <i class="flag flag-tur"></i>
            1. Lig
        </a><!-- end ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? true : false --><!-- end ngRepeat: league in fleagues | limitTo:12 -->
    </div>

    <div class="uk-grid-collapse uk-child-width-1-2 uk-child-width-1-6@l uk-child-width-1-3@m uk-child-width-1-2@s uk-child-width-1-2@xs uk-grid" uk-grid="">
        <!-- ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><a href="/sports/#!/prematch/futbol/1/fransa/6/ligue-1/4?comingHour=All" class="league alt ng-binding ng-scope uk-first-column" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? false : true">
            <i class="flag flag-fra"></i>
            Ligue 1
        </a><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><a href="/sports/#!/prematch/futbol/1/italya/30/serie-a/22?comingHour=All" class="league alt ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? false : true">
            <i class="flag flag-ita"></i>
            Serie A
        </a><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><a href="/sports/#!/prematch/futbol/1/hollanda/34/eredivisie/28?comingHour=All" class="league alt ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? false : true">
            <i class="flag flag-nld"></i>
            Eredivisie
        </a><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><a href="/sports/#!/prematch/futbol/1/portekiz/43/liga-portugal/39?comingHour=All" class="league alt ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? false : true">
            <i class="flag flag-prt"></i>
            Liga Portugal
        </a><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><a href="/sports/#!/prematch/futbol/1/brezilya/12/brasilero-serie-a/60?comingHour=All" class="league alt ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? false : true">
            <i class="flag flag-bra"></i>
            Brasilero Serie A
        </a><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 --><!-- ngIf: $index % 2 == 0 ? false : true --><a href="/sports/#!/prematch/futbol/1/uluslararasi-kulupler/294/uefa-avrupa-ligi/1931?comingHour=All" class="league alt ng-binding ng-scope" ng-repeat="league in fleagues | limitTo:12" ng-if="$index % 2 == 0 ? false : true">
            <i class="flag flag-"></i>
            UEFA Avrupa Ligi
        </a><!-- end ngIf: $index % 2 == 0 ? false : true --><!-- end ngRepeat: league in fleagues | limitTo:12 -->
    </div>

    <!-- loading -->
    <!-- ngIf: !fleagues && !noData -->
</div></top-leagues>
    </div><!-- end ngIf: widget.topLeagues.status -->

    <!-- Promotions -->
    <!-- ngIf: widget.promotions.status -->

    <!-- Slots -->
    <!-- ngIf: widget.slotGames.status --><div class="uk-child-width-1-1 uk-width-1-1 order-3" ng-if="widget.slotGames.status">
        <slot-games-widget><h4 class="main-page-title mt-3 ng-binding">Slotlar</h4>

<div class="widget-slots uk-width-1-1 uk-grid uk-grid-stack" uk-grid="">
    <!-- ngIf: !slotsLoading --><div class="game-list uk-width-expand uk-child-width-1-2 uk-child-width-1-4@s uk-child-width-1-4@m uk-child-width-1-4@l m-0 ng-scope uk-grid uk-first-column" ng-if="!slotsLoading" uk-grid="">
        <!-- ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item uk-first-column" ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=12631&amp;mode=false&amp;type=s&amp;name=Big Bass Splash" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs10txbigbass.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs10txbigbass.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs10txbigbass.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs10txbigbass.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item " ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=9443&amp;mode=false&amp;type=s&amp;name=Wild Wild Riches" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs576treasures.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs576treasures.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs576treasures.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs576treasures.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item " ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=15742&amp;mode=false&amp;type=s&amp;name=Saray Ruyasi" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20dede.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20dede.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20dede.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20dede.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item " ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=12648&amp;mode=false&amp;type=s&amp;name=Sugar Rush" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrush.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrush.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrush.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrush.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item uk-grid-margin uk-first-column" ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=16161&amp;mode=false&amp;type=s&amp;name=Sugar Rush 1000" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrushx.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrushx.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrushx.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20sugarrushx.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item uk-grid-margin" ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=13514&amp;mode=false&amp;type=s&amp;name=Wild Wild Riches Megaways" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vswayswwriches.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vswayswwriches.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vswayswwriches.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vswayswwriches.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item uk-grid-margin" ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=9496&amp;mode=false&amp;type=s&amp;name=Mustang Gold" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs25mustang.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs25mustang.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs25mustang.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs25mustang.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 --><div class="game-item uk-grid-margin" ng-repeat="item in populerSlotGames | limitTo:8">
            <a href="/casino/#!/game?productId=61&amp;gameId=13086&amp;mode=false&amp;type=s&amp;name=Muertos Multiplier Megaways" class="uk-visible@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20muertos.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20muertos.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>

            <a href="javascript:;" ng-click="openGame(item,false);" class="uk-hidden@s">
                <img img-preload="" ng-src="https://api.pragmaticplay.net/game_pic/rec/325/vs20muertos.png" src="https://api.pragmaticplay.net/game_pic/rec/325/vs20muertos.png">
                <b class="ng-binding">Pragmatic Play</b>
            </a>
        </div><!-- end ngRepeat: item in populerSlotGames | limitTo:8 -->
    </div><!-- end ngIf: !slotsLoading -->

    <!-- ngIf: !slotsLoading -->
<!-- end ngIf: !slotsLoading -->

    <!-- loading -->
    <!-- ngIf: (!populerSlotGames && !noData) || slotsLoading -->
</div></slot-games-widget>
    </div><!-- end ngIf: widget.slotGames.status -->

    <!-- Live Casino -->
    <!-- ngIf: widget.liveCasino.status --><div class="uk-child-width-1-1 uk-width-1-1 order-4" ng-if="widget.liveCasino.status">
        <live-casino-widget><h4 class="main-page-title mt-3 ng-binding">Canlı Casino</h4>

<div class="widget-slots uk-width-1-1 uk-grid uk-grid-stack" uk-grid="">
    <!-- ngIf: !casinoLoading --><div class="game-list uk-width-expand uk-child-width-1-2 uk-child-width-1-4@s uk-child-width-1-4@m uk-child-width-1-4@l m-0 ng-scope uk-grid uk-first-column" ng-if="!casinoLoading" uk-grid="">
        <!-- ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item uk-first-column" ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=60&amp;gameId=345375&amp;mode=false&amp;type=l&amp;name=Live - Sweet Bonanza CandyLand" class="uk-visible@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/pbvzrfk1fyft4dwe/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/pbvzrfk1fyft4dwe/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Casino Holdem</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/pbvzrfk1fyft4dwe/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/pbvzrfk1fyft4dwe/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Casino Holdem</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item " ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=80&amp;gameId=236398&amp;mode=false&amp;type=l&amp;name=First Person Blackjack Lobby" class="uk-visible@s">
                <img ng-src="https://cdn.hub88.io/evolution/evo_firstpersonblackjacklobby.jpg" src="https://cdn.hub88.io/evolution/evo_firstpersonblackjacklobby.jpg">
                <b class="ng-binding">Evolution Gaming</b>
                <span class="ng-binding">Blackjack</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://cdn.hub88.io/evolution/evo_firstpersonblackjacklobby.jpg" src="https://cdn.hub88.io/evolution/evo_firstpersonblackjacklobby.jpg">
                <b class="ng-binding">Evolution Gaming</b>
                <span class="ng-binding">Blackjack</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item " ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=80&amp;gameId=347005&amp;mode=false&amp;type=l&amp;name=Teen Patti" class="uk-visible@s">
                <img ng-src="https://cdn.hub88.io/evolution/evo_teenpatti.jpg" src="https://cdn.hub88.io/evolution/evo_teenpatti.jpg">
                <b class="ng-binding">Evolution Gaming</b>
                <span class="ng-binding">Rulet</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://cdn.hub88.io/evolution/evo_teenpatti.jpg" src="https://cdn.hub88.io/evolution/evo_teenpatti.jpg">
                <b class="ng-binding">Evolution Gaming</b>
                <span class="ng-binding">Rulet</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item " ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=60&amp;gameId=347026&amp;mode=false&amp;type=l&amp;name=Live - PowerUp Roulette" class="uk-visible@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/powruprw1qm3xc25/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/powruprw1qm3xc25/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Rulet</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/powruprw1qm3xc25/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/powruprw1qm3xc25/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Rulet</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item uk-grid-margin uk-first-column" ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=60&amp;gameId=411352&amp;mode=false&amp;type=l&amp;name=Speed Blackjack 21 - Emerald" class="uk-visible@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/sobj253blackjack/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/sobj253blackjack/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Blackjack</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/sobj253blackjack/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/sobj253blackjack/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Blackjack</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item uk-grid-margin" ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=43&amp;gameId=574&amp;mode=false&amp;type=l&amp;name=Andar Bahar" class="uk-visible@s">
                <img ng-src="https://cdn.nagcdn.com/gstatic/games/ezugi/andar_bahar.jpg" src="https://cdn.nagcdn.com/gstatic/games/ezugi/andar_bahar.jpg">
                <b class="ng-binding">Ezugi</b>
                <span class="ng-binding">Andar Bahar</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://cdn.nagcdn.com/gstatic/games/ezugi/andar_bahar.jpg" src="https://cdn.nagcdn.com/gstatic/games/ezugi/andar_bahar.jpg">
                <b class="ng-binding">Ezugi</b>
                <span class="ng-binding">Andar Bahar</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item uk-grid-margin" ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=49&amp;gameId=435481&amp;mode=false&amp;type=l&amp;name=Montecarlo 2 Baccarat" class="uk-visible@s">
                <img ng-src="https://cdn.nagcdn.com/gstatic/games/vivogaming/montecarlo_2_baccarat.jpg" src="https://cdn.nagcdn.com/gstatic/games/vivogaming/montecarlo_2_baccarat.jpg">
                <b class="ng-binding">VivoGaming</b>
                <span class="ng-binding">Baccarat</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://cdn.nagcdn.com/gstatic/games/vivogaming/montecarlo_2_baccarat.jpg" src="https://cdn.nagcdn.com/gstatic/games/vivogaming/montecarlo_2_baccarat.jpg">
                <b class="ng-binding">VivoGaming</b>
                <span class="ng-binding">Baccarat</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 --><div class="game-item uk-grid-margin" ng-repeat="item in populerCasinoGames | limitTo:8">
            <a href="/casino/#!/game?productId=60&amp;gameId=210596&amp;mode=false&amp;type=l&amp;name=Live - Mega Roulette" class="uk-visible@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/1hl65ce1lxuqdrkr/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/1hl65ce1lxuqdrkr/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Rulet</span>
            </a>

            <a href="javascript:;" ng-click="openCasinoGame(item)" class="uk-hidden@s">
                <img ng-src="https://client.pragmaticplaylive.net/desktop/assets/snaps/1hl65ce1lxuqdrkr/poster.jpg?v0.47384406631744" src="https://client.pragmaticplaylive.net/desktop/assets/snaps/1hl65ce1lxuqdrkr/poster.jpg?v0.47384406631744">
                <b class="ng-binding">Pragmatic Play</b>
                <span class="ng-binding">Rulet</span>
            </a>
        </div><!-- end ngRepeat: item in populerCasinoGames | limitTo:8 -->
    </div><!-- end ngIf: !casinoLoading -->

    <!-- ngIf: !casinoLoading --><!-- end ngIf: !casinoLoading -->

    <!-- loading -->
    <!-- ngIf: (!populerCasinoGames && !noData) || casinoLoading -->
</div></live-casino-widget>
    </div><!-- end ngIf: widget.liveCasino.status -->
</div>

<style class="ng-scope">
    .contentWrapper {
        display: flex;
        flex-wrap: wrap;
    }
</style>

            <!-- Site Footer -->
            <!-- ngInclude: undefined --><ng-include src="footerTemplateUrl" class="uk-padding-remove ng-scope" ng-controller="FooterCtrl"><footer class="ng-scope">

    <div class="footer-content">
        <a href="javascript:;" class="back-to-top uk-icon uk-totop" uk-totop="" uk-scroll=""><svg width="18" height="10" viewBox="0 0 18 10" xmlns="http://www.w3.org/2000/svg" data-svg="totop"><polyline fill="none" stroke="#000" stroke-width="1.2" points="1 9 9 1 17 9 "></polyline></svg></a>

        <div class="uk-margin-remove uk-grid uk-grid-stack" uk-grid="" ng-show="!cs.loading">
            <ul class="aboutLinks uk-first-column">
                <!-- ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/about/99" ng-init="$last ? listRender() : ''" class="ng-binding">Hakkımızda</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/rules/101" ng-init="$last ? listRender() : ''" class="ng-binding">Şartlar ve Koşullar</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/aml-kyc-policy/102" ng-init="$last ? listRender() : ''" class="ng-binding">KYC Politikası, Gizlilik ve Kişisel Verilerin Yönetilmesi</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/player-protection/103" ng-init="$last ? listRender() : ''" class="ng-binding">Oyuncu Koruması</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/distancing/104" ng-init="$last ? listRender() : ''" class="ng-binding">Kendini Uzaklaştırma</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/resolution/105" ng-init="$last ? listRender() : ''" class="ng-binding">Anlaşmazlık Çözümleri</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/black-money/106" ng-init="$last ? listRender() : ''" class="ng-binding">Kara Para Aklama Karşıtlığı Politika</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/honesty/107" ng-init="$last ? listRender() : ''" class="ng-binding">Dürüstlük ve RNG Test Yönetimi</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/account/108" ng-init="$last ? listRender() : ''" class="ng-binding">Hesaplar, Ödemeler ve Bonuslar</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/general-rules/109" ng-init="$last ? listRender() : ''" class="ng-binding">Genel Kurallar</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/terms-and-conditions/110" ng-init="$last ? listRender() : ''" class="ng-binding">Terms And Conditions</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/betting-rules/111" ng-init="$last ? listRender() : ''" class="ng-binding">Bahis Kuralları</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/casino-rules/112" ng-init="$last ? listRender() : ''" class="ng-binding">Casino Kuralları</a></li><!-- end ngRepeat: item in siteAbouts --><li ng-repeat="item in siteAbouts" class="ng-scope"><a href="/contents/#!/about/responsible-gaming/113" ng-init="$last ? listRender() : ''" class="ng-binding">Sorumlu Oyunculuk</a></li><!-- end ngRepeat: item in siteAbouts -->
            </ul>

            <ul class="contactList uk-grid-margin uk-first-column">
                <li><a class="ng-binding"><span uk-icon="receiver" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="receiver"><path fill="none" stroke="#000" stroke-width="1.01" d="M6.189,13.611C8.134,15.525 11.097,18.239 13.867,18.257C16.47,18.275 18.2,16.241 18.2,16.241L14.509,12.551L11.539,13.639L6.189,8.29L7.313,5.355L3.76,1.8C3.76,1.8 1.732,3.537 1.7,6.092C1.667,8.809 4.347,11.738 6.189,13.611"></path></svg></span> +905338466425</a></li>
                <li><a class="ng-binding"><span uk-icon="mail" class="uk-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="mail"><polyline fill="none" stroke="#000" points="1.4,6.5 10,11 18.6,6.5"></polyline><path d="M 1,4 1,16 19,16 19,4 1,4 Z M 18,15 2,15 2,5 18,5 18,15 Z"></path></svg></span> info@neyine.com  destek@neyine.com</a></li>
            </ul>

            <div class="license-shields uk-margin-auto mt-4 uk-grid-margin uk-first-column" style="width:80px;">
                <!-- PAGCOR -->
                <div>     
                    <div ng-bind-html="license.html" class="ng-binding"><a href="https://verification.pagcor-regulatory.ph/validate/page?domain=neyine.com" target="_blank"><img src="https://verification.pagcor-regulatory.ph/api/validate/logo?domain=neyine.com" alt="Logo" width="100"></a></div>
                </div>
            </div>

            <!-- ngIf: customImgArea.img && customImgArea.url != null -->
            <!-- ngIf: customImgArea.img && customImgArea.url == null -->

            <div class="spacer uk-grid-margin uk-first-column"></div>

            <div class="uk-width-1-1 providers uk-visible@s uk-grid-margin uk-first-column">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/61.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/7.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/5.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/40.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/52.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/22.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/56.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/54.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/55.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/18.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/35.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/31.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/30.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/3.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/43.svg">
                <img src="https://cdn.nagcdn.com/ngamingbase/core/assets/images/providers/49.svg">
            </div>

            <div class="uk-width-1-1 uk-text-center uk-margin-bottom uk-grid-margin uk-first-column">
                <p class="uk-text-center footer-text ng-binding">Neyine.com is licensed and regulated by Philippine Amusement and Gaming Corporation Offshore Gaming License for Sports Betting &amp; E-Gaming No: 18-0022.</p>
                <p class="uk-margin-bottom footer-text mt-1 ng-binding">
                    Copyright © 2024 NEYİNE. All Rights Reserved.
                </p>
            </div>
        </div>

        <!-- Loading Spinner -->
        <div class="uk-width-1-1 uk-text-center inline-spinner ng-hide" ng-show="cs.loading">
            <div class="uk-margin-bottom uk-icon uk-spinner" uk-spinner=""><svg width="30" height="30" viewBox="0 0 30 30" xmlns="http://www.w3.org/2000/svg" data-svg="spinner"><circle fill="none" stroke="#000" cx="15" cy="15" r="14"></circle></svg></div>
        </div>
    </div>
</footer></ng-include>
        
    

    <!-- Site Bundles -->
    <script type="text/javascript" async="" src="https://vue.comm100.com/livechat.ashx?siteId=90004033"></script><script src="https://cdn.nagcdn.com/_ngamingbase/core/assets/scripts/libs/uikit.min.js"></script>
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/assets/scripts/libs/uikit-icons.min.js"></script>
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/bundles/vendor.min.js?v=22"></script>
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/bundles/services.min.js?v=22"></script>
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/bundles/components.min.js?v=22"></script>
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/bundles/directives.js?v=22"></script>

    <!-- Page Level Scripts -->
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/apps/index/landing/landing.js?v=22"></script>
    <script src="https://cdn.nagcdn.com/_ngamingbase/core/apps/index/index.app.js?v=22"></script>
	

    <!-- Site Settings -->
    <script src="https://cdn.nagcdn.com/_ngamingbase/neyine/settings.js?v=22"></script>

<!--Begin Comm100 Live Chat Code-->
<!--End Comm100 Live Chat Code-->


<iframe id="comm100-iframe" title="comm100-iframe" style="display: none;" lang="tr"></iframe><div id="comm100-container"><div><div></div><div><div></div></div><div aria-live="polite" style="position: absolute; left: -10000px; top: -10000px; width: 1px; height: 1px;"></div></div></div><script type="text/javascript" async="" src="https://validator.pagcorlicence.com/js/09f661d8-a9ab-4c24-bdee-396f913542ce"></script><iframe id="comm100-iframe" title="comm100-iframe" style="display: none;"></iframe></body></html>
