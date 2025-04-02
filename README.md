<html lang="fa">
<head>
    <meta charset="UTF-8">
    <link rel="icon" href="https://card.thecartek.com/images/ct.png">
    <link rel="stylesheet" href="https://card.thecartek.com/css/app.css">
    <link rel="stylesheet" href="https://card.thecartek.com/css/override.css">
    <!-- لینک به FontAwesome برای استفاده از آیکون‌ها -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
</head>
<body x-data="{ openSidebar: false, clipboardCopy: false, modalQrCode: false, clipboard(val) { navigator.clipboard.writeText(val); this.clipboardCopy = true; setTimeout(() => this.clipboardCopy = false, 2000) }}">

    <div class="container-">
        <div class="panel-content mb-3">
            <div class="container-panel mb-15">
                <div class="container-content" style="max-height: 100vh;">
                    <div class="mx-auto border-4 border-gray-200 border-dashed rounded-3xl pb-5 relative">
                        <div class="md:px-3 px-1">
                            <div class="flex justify-center">
                                <div class="text-center space-y-4">
                                    <h3 class="text-xl font-bold mt-3">موبایل رضائی</h3>
                                    <p class="text-sm text-gray-500 mt-0">فروش اقساطی</p>
                                </div>
                            </div>
                            <div class="flex justify-center gap-2 mt-3">
                               
                                <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" aria-label="نمایش لوکیشن">
                                    <i class="fas fa-location-arrow icon"></i> لوکیشن
                                </button>
                                <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" aria-label="دانلود رزومه">
                                    <i class="fas fa-download icon"></i> دانلود رزومه
                                </button>
                                <form action="https://card.thecartek.com/download-vcf/25" method="post">
                                    <input type="hidden" name="_token" value="5bjKvZp2jaVIhv6xf9O9BEY7HCv0EvEC5XvUl7QX">
                                    <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" aria-label="ذخیره مخاطب">
                                        <i class="fas fa-user-plus icon"></i> ذخیره مخاطب
                                    </button>
                                </form>
                            </div>
                            <div class="px-5 pt-3">
                                <div class="grid grid-cols-1 gap-2">
                                    <!-- لینک تماس با شماره تلفن -->
                                    <a href="tel:09189444481" class="button" aria-label="تماس با 09189444481">
                                        <div class="icon-container">
                                            <i class="fas fa-phone-alt icon"></i>
                                        </div>
                                        <span>09189444481</span>
                                    </a>
                                    <!-- لینک تلگرام -->
                                    <a href="https://t.me/username" class="button" aria-label="لینک به تلگرام">
                                        <div class="icon-container">
                                            <i class="fab fa-telegram-plane icon"></i>
                                        </div>
                                        <span>تلگرام</span>
                                    </a>
                                    <!-- لینک واتس اپ -->
                                    <a href="https://wa.me/09189444481" class="button" aria-label="لینک به واتس اپ">
                                        <div class="icon-container">
                                            <i class="fab fa-whatsapp icon"></i>
                                        </div>
                                        <span>واتس‌اپ</span>
                                    </a>
                                    <!-- لینک اینستاگرام -->
                                    <a href="https://instagram.com/username" class="button" aria-label="لینک به اینستاگرام">
                                        <div class="icon-container">
                                            <i class="fab fa-instagram icon"></i>
                                        </div>
                                        <span>اینستاگرام</span>
                                    </a>
                                    <!-- ایمیل -->
                                    <a href="mailto:example@example.com" class="button" aria-label="ارسال ایمیل">
                                        <div class="icon-container">
                                            <i class="fas fa-envelope icon"></i>
                                        </div>
                                        <span>ایمیل</span>
                                    </a>
                                    <!-- آدرس -->
                                    <a href="https://www.google.com/maps?q=your+address" class="button" aria-label="مشاهده آدرس">
                                        <div class="icon-container">
                                            <i class="fas fa-map-marker-alt icon"></i>
                                        </div>
                                        <span>آدرس</span>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
