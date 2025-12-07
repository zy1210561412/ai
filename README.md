<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI赋能校地文化融合：重师×沙坪坝非遗联动</title>
    <!-- Tailwind CSS v3 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <!-- 自定义Tailwind配置 -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#1E40AF', // 深蓝色
                        secondary: '#D8B4FE', // 紫色
                        accent: '#F97316', // 橙色
                        light: '#F8FAFC', // 浅色背景
                        dark: '#1E293B', // 深色文字
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                        serif: ['"Noto Serif SC"', 'serif'],
                    },
                    animation: {
                        'float': 'float 3s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-10px)' },
                        }
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            }
            .text-shadow-lg {
                text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.5);
            }
            .bg-blur {
                backdrop-filter: blur(8px);
            }
            .scrollbar-hide::-webkit-scrollbar {
                display: none;
            }
            .scrollbar-hide {
                -ms-overflow-style: none;
                scrollbar-width: none;
            }
        }
    </style>
</head>
<body class="bg-light font-sans text-dark">
    <!-- 导航栏 -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-white bg-opacity-90 shadow-md bg-blur">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center space-x-2">
                <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/80b77053c8e94f41916416ae9786b1e8~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=hz7Cvsb64kvq0nma0oFm8TF2k%2FA%3D" alt="Logo" class="h-10 w-10 rounded-full">
                <span class="text-xl font-bold text-primary">AI校地文化融合</span>
            </a>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="text-primary hover:text-accent transition-colors">首页</a>
                <a href="#postcard" class="text-primary hover:text-accent transition-colors">AI明信片</a>
                <a href="#guide" class="text-primary hover:text-accent transition-colors">非遗体验官</a>
                <a href="#about" class="text-primary hover:text-accent transition-colors">关于项目</a>
            </div>
            <button id="mobile-menu-button" class="md:hidden text-primary text-2xl">
                <i class="fa fa-bars"></i>
            </button>
        </div>
        <!-- 移动端菜单 -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg absolute w-full">
            <div class="container mx-auto px-4 py-2 flex flex-col space-y-3">
                <a href="#home" class="text-primary hover:text-accent transition-colors py-2">首页</a>
                <a href="#postcard" class="text-primary hover:text-accent transition-colors py-2">AI明信片</a>
                <a href="#guide" class="text-primary hover:text-accent transition-colors py-2">非遗体验官</a>
                <a href="#about" class="text-primary hover:text-accent transition-colors py-2">关于项目</a>
            </div>
        </div>
    </nav>

    <!-- 首页 Hero 区域 -->
    <section id="home" class="pt-24 pb-16 md:pt-32 md:pb-24 bg-gradient-to-b from-blue-50 to-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-primary mb-6 leading-tight">
                        AI赋能校地文化融合
                        <span class="block text-accent">重师×沙坪坝非遗联动</span>
                    </h1>
                    <p class="text-lg md:text-xl text-gray-700 mb-8">
                        通过AI技术连接重庆师范大学与沙坪坝区非物质文化遗产，
                        让文化传承更鲜活，校地融合更接地气。
                    </p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="#postcard" class="btn-primary bg-primary hover:bg-blue-800 text-white font-bold py-3 px-6 rounded-lg shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-1 text-center">
                            <i class="fa fa-picture-o mr-2"></i>生成AI明信片
                        </a>
                        <a href="#guide" class="btn-secondary bg-white hover:bg-gray-100 text-primary font-bold py-3 px-6 rounded-lg shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-1 border-2 border-primary text-center">
                            <i class="fa fa-map-marker mr-2"></i>非遗体验指南
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative w-full max-w-md">
                        <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/4d384c551c5b43f9b3a15162f752e4e9~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=6AqETaFHuP6DCj0kGWi0Y%2BMhwSM%3D" alt="文化融合" class="rounded-xl shadow-2xl z-20 relative animate-float">
                        <div class="absolute -bottom-6 -right-6 w-3/4 h-3/4 bg-secondary rounded-xl shadow-xl z-10"></div>
                        <div class="absolute -top-6 -left-6 w-1/2 h-1/2 bg-accent rounded-xl shadow-xl z-10"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 特色展示区 -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-primary mb-12">校地文化融合新玩法</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- 特色1 -->
                <div class="bg-blue-50 rounded-xl p-6 shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center mb-4 text-white text-2xl">
                        <i class="fa fa-image"></i>
                    </div>
                    <h3 class="text-xl font-bold text-primary mb-3">AI明信片生成系统</h3>
                    <p class="text-gray-700">
                        将重师校园地标与沙坪坝非遗元素完美融合，生成个性化明信片，支持双语文案，一键导出打印。
                    </p>
                </div>
                <!-- 特色2 -->
                <div class="bg-blue-50 rounded-xl p-6 shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center mb-4 text-white text-2xl">
                        <i class="fa fa-map-signs"></i>
                    </div>
                    <h3 class="text-xl font-bold text-primary mb-3">非遗体验官智能匹配</h3>
                    <p class="text-gray-700">
                        根据个人兴趣精准匹配沙坪坝非遗活动，提供个性化指南，包括历史知识、出行攻略和互动任务。
                    </p>
                </div>
                <!-- 特色3 -->
                <div class="bg-blue-50 rounded-xl p-6 shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center mb-4 text-white text-2xl">
                        <i class="fa fa-share-alt"></i>
                    </div>
                    <h3 class="text-xl font-bold text-primary mb-3">AI图文打卡模板</h3>
                    <p class="text-gray-700">
                        体验后一键生成精美打卡内容，排版和配文自动完成，方便分享传播，形成完整的文化体验闭环。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- AI明信片生成系统 -->
    <section id="postcard" class="py-16 bg-gradient-to-b from-white to-blue-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-primary mb-4">AI明信片生成系统</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">
                    选择重师校园地标和沙坪坝非遗元素，输入关键词，生成专属于你的校地联名纪念明信片
                </p>
            </div>

            <div class="flex flex-col lg:flex-row gap-8">
                <!-- 左侧：选择区域 -->
                <div class="lg:w-1/2 bg-white rounded-xl shadow-lg p-6">
                    <h3 class="text-xl font-bold text-primary mb-4">选择元素</h3>
                    
                    <!-- 校园地标选择 -->
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">校园地标</label>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-3" id="campus-elements">
                            <div class="element-item cursor-pointer border-2 border-transparent hover:border-primary rounded-lg overflow-hidden transition-all" data-element="library">
                                <img src="https://p26-doubao-search-sign.byteimg.com/labis/e6a7be062ddab87b8a6214c7db52a5be~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644921&x-signature=8QaUN07wBaSboIcpGK0N69O8hKI%3D" alt="图书馆" class="w-full h-32 object-cover">
                                <div class="p-2 text-center">
                                    <span class="text-sm font-medium">图书馆</span>
                                </div>
                            </div>
                            <div class="element-item cursor-pointer border-2 border-transparent hover:border-primary rounded-lg overflow-hidden transition-all" data-element="school-stone">
                                <img src="https://p3-doubao-search-sign.byteimg.com/labis/0feaa0c53f99b5726a25678eca591f8e~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644921&x-signature=F87MqGqMP%2FoNc32ULmKv%2F08PvGw%3D" alt="校训石" class="w-full h-32 object-cover">
                                <div class="p-2 text-center">
                                    <span class="text-sm font-medium">校训石</span>
                                </div>
                            </div>
                            <div class="element-item cursor-pointer border-2 border-transparent hover:border-primary rounded-lg overflow-hidden transition-all" data-element="teaching-building">
                                <img src="https://p26-doubao-search-sign.byteimg.com/labis/9f5005d8b7c7e0480f940247e22bc354~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644921&x-signature=mmTn%2Bo3UvaSaU0MhUI4lI9ELofg%3D" alt="教学楼" class="w-full h-32 object-cover">
                                <div class="p-2 text-center">
                                    <span class="text-sm font-medium">教学楼</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- 非遗元素选择 -->
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">非遗元素</label>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-3" id="heritage-elements">
                            <div class="element-item cursor-pointer border-2 border-transparent hover:border-primary rounded-lg overflow-hidden transition-all" data-element="jiang-ceramic">
                                <img src="https://p11-doubao-search-sign.byteimg.com/ecom-shop-material/jpeg_m_310a4f65614628ac41fa3862a1c90ddc_sx_285843_www640-640~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644941&x-signature=KZKEjhCEPmrDCbfJRoSqs%2FXDBdY%3D" alt="江家瓷" class="w-full h-32 object-cover">
                                <div class="p-2 text-center">
                                    <span class="text-sm font-medium">江家瓷纹样</span>
                                </div>
                            </div>
                            <div class="element-item cursor-pointer border-2 border-transparent hover:border-primary rounded-lg overflow-hidden transition-all" data-element="li-shuttlecock">
                                <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/80b77053c8e94f41916416ae9786b1e8~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=hz7Cvsb64kvq0nma0oFm8TF2k%2FA%3D" alt="李氏花毽" class="w-full h-32 object-cover">
                                <div class="p-2 text-center">
                                    <span class="text-sm font-medium">李氏花毽</span>
                                </div>
                            </div>
                            <div class="element-item cursor-pointer border-2 border-transparent hover:border-primary rounded-lg overflow-hidden transition-all" data-element=" Gele-mountain">
                                <img src="https://p26-doubao-search-sign.byteimg.com/tos-cn-i-xv4ileqgde/c79ac24e6da549b7ab8e01741690a88b~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644929&x-signature=axJWxbK8%2FFo6NmCcY0B40kokGFE%3D" alt="歌乐山" class="w-full h-32 object-cover">
                                <div class="p-2 text-center">
                                    <span class="text-sm font-medium">歌乐山剪影</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- 关键词输入 -->
                    <div class="mb-6">
                        <label for="keywords" class="block text-gray-700 font-medium mb-2">输入关键词（如"重师教学楼+江家瓷纹样"）</label>
                        <input type="text" id="keywords" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="输入关键词...">
                    </div>

                    <!-- 文案语言选择 -->
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">文案语言</label>
                        <div class="flex space-x-4">
                            <label class="inline-flex items-center">
                                <input type="radio" name="language" value="both" class="form-radio text-primary" checked>
                                <span class="ml-2">普通话+重庆方言</span>
                            </label>
                            <label class="inline-flex items-center">
                                <input type="radio" name="language" value="mandarin" class="form-radio text-primary">
                                <span class="ml-2">仅普通话</span>
                            </label>
                        </div>
                    </div>

                    <!-- 生成按钮 -->
                    <button id="generate-postcard" class="w-full bg-primary hover:bg-blue-800 text-white font-bold py-3 px-6 rounded-lg shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-1">
                        <i class="fa fa-magic mr-2"></i>生成明信片
                    </button>
                </div>

                <!-- 右侧：预览区域 -->
                <div class="lg:w-1/2">
                    <div class="bg-white rounded-xl shadow-lg p-6 h-full flex flex-col">
                        <h3 class="text-xl font-bold text-primary mb-4">预览效果</h3>
                        
                        <div id="postcard-preview" class="flex-grow flex items-center justify-center bg-gray-100 rounded-lg p-4 mb-4">
                            <div class="text-center text-gray-500">
                                <i class="fa fa-image text-5xl mb-3"></i>
                                <p>请选择元素并点击生成按钮</p>
                            </div>
                        </div>

                        <div id="postcard-actions" class="hidden space-y-3">
                            <div class="flex justify-between items-center p-3 bg-blue-50 rounded-lg">
                                <div>
                                    <h4 class="font-medium text-primary" id="postcard-title">重师×沙坪坝非遗联名明信片</h4>
                                    <p class="text-sm text-gray-600" id="postcard-description">图书馆 × 江家瓷纹样</p>
                                </div>
                                <div class="flex space-x-2">
                                    <button id="download-postcard" class="bg-primary hover:bg-blue-800 text-white p-2 rounded-lg">
                                        <i class="fa fa-download"></i>
                                    </button>
                                    <button id="share-postcard" class="bg-accent hover:bg-orange-600 text-white p-2 rounded-lg">
                                        <i class="fa fa-share-alt"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 示例展示 -->
            <div class="mt-12">
                <h3 class="text-xl font-bold text-primary mb-4 text-center">示例作品</h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all">
                        <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/4d384c551c5b43f9b3a15162f752e4e9~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=6AqETaFHuP6DCj0kGWi0Y%2BMhwSM%3D" alt="示例1" class="w-full h-64 object-cover">
                        <div class="p-4">
                            <h4 class="font-bold text-primary">图书馆 × 江家瓷纹样</h4>
                            <p class="text-sm text-gray-600">传统与现代的完美融合</p>
                        </div>
                    </div>
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all">
                        <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/80b77053c8e94f41916416ae9786b1e8~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=hz7Cvsb64kvq0nma0oFm8TF2k%2FA%3D" alt="示例2" class="w-full h-64 object-cover">
                        <div class="p-4">
                            <h4 class="font-bold text-primary">校训石 × 李氏花毽</h4>
                            <p class="text-sm text-gray-600">厚德笃学，创意无限</p>
                        </div>
                    </div>
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all">
                        <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/43a73e58b33c450b9b2cf20e135da845~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=U519%2BcMn%2BwiOHT5dP%2BKQ4VNPpLE%3D" alt="示例3" class="w-full h-64 object-cover">
                        <div class="p-4">
                            <h4 class="font-bold text-primary">校园风光 × 歌乐山</h4>
                            <p class="text-sm text-gray-600">山水之间，文化传承</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 非遗体验官智能匹配系统 -->
    <section id="guide" class="py-16 bg-gradient-to-b from-blue-50 to-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-primary mb-4">非遗体验官智能匹配系统</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">
                    根据你的兴趣标签，精准匹配沙坪坝非遗活动，生成个性化体验指南
                </p>
            </div>

            <div class="flex flex-col lg:flex-row gap-8">
                <!-- 左侧：兴趣标签选择 -->
                <div class="lg:w-1/2 bg-white rounded-xl shadow-lg p-6">
                    <h3 class="text-xl font-bold text-primary mb-4">选择你的兴趣标签</h3>
                    
                    <!-- 兴趣标签网格 -->
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 mb-6" id="interest-tags">
                        <div class="tag-item cursor-pointer bg-gray-100 hover:bg-primary hover:text-white rounded-lg p-3 text-center transition-colors" data-tag="handcraft">
                            <i class="fa fa-paint-brush text-xl mb-1"></i>
                            <p class="text-sm">手工爱好者</p>
                        </div>
                        <div class="tag-item cursor-pointer bg-gray-100 hover:bg-primary hover:text-white rounded-lg p-3 text-center transition-colors" data-tag="traditional">
                            <i class="fa fa-book text-xl mb-1"></i>
                            <p class="text-sm">传统文化迷</p>
                        </div>
                        <div class="tag-item cursor-pointer bg-gray-100 hover:bg-primary hover:text-white rounded-lg p-3 text-center transition-colors" data-tag="history">
                            <i class="fa fa-history text-xl mb-1"></i>
                            <p class="text-sm">历史探索者</p>
                        </div>
                        <div class="tag-item cursor-pointer bg-gray-100 hover:bg-primary hover:text-white rounded-lg p-3 text-center transition-colors" data-tag="food">
                            <i class="fa fa-cutlery text-xl mb-1"></i>
                            <p class="text-sm">美食达人</p>
                        </div>
                        <div class="tag-item cursor-pointer bg-gray-100 hover:bg-primary hover:text-white rounded-lg p-3 text-center transition-colors" data-tag="photography">
                            <i class="fa fa-camera text-xl mb-1"></i>
                            <p class="text-sm">摄影爱好者</p>
                        </div>
                        <div class="tag-item cursor-pointer bg-gray-100 hover:bg-primary hover:text-white rounded-lg p-3 text-center transition-colors" data-tag="performance">
                            <i class="fa fa-music text-xl mb-1"></i>
                            <p class="text-sm">表演艺术迷</p>
                        </div>
                    </div>

                    <!-- 额外兴趣描述 -->
                    <div class="mb-6">
                        <label for="additional-info" class="block text-gray-700 font-medium mb-2">额外兴趣描述（可选）</label>
                        <textarea id="additional-info" rows="3" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="描述你的其他兴趣爱好..."></textarea>
                    </div>

                    <!-- 匹配按钮 -->
                    <button id="match-heritage" class="w-full bg-primary hover:bg-blue-800 text-white font-bold py-3 px-6 rounded-lg shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-1">
                        <i class="fa fa-search mr-2"></i>匹配非遗体验
                    </button>
                </div>

                <!-- 右侧：匹配结果 -->
                <div class="lg:w-1/2">
                    <div class="bg-white rounded-xl shadow-lg p-6 h-full flex flex-col">
                        <h3 class="text-xl font-bold text-primary mb-4">你的个性化非遗体验</h3>
                        
                        <div id="heritage-result" class="flex-grow flex items-center justify-center bg-gray-100 rounded-lg p-4 mb-4">
                            <div class="text-center text-gray-500">
                                <i class="fa fa-map-signs text-5xl mb-3"></i>
                                <p>请选择兴趣标签并点击匹配按钮</p>
                            </div>
                        </div>

                        <!-- 体验指南内容 -->
                        <div id="heritage-guide" class="hidden space-y-4">
                            <!-- 非遗小知识 -->
                            <div class="bg-blue-50 rounded-lg p-4">
                                <h4 class="font-bold text-primary flex items-center">
                                    <i class="fa fa-lightbulb-o mr-2"></i>非遗小知识
                                </h4>
                                <div id="heritage-knowledge" class="mt-2 text-gray-700">
                                    <!-- 内容将通过JS动态填充 -->
                                </div>
                            </div>

                            <!-- 出行攻略 -->
                            <div class="bg-green-50 rounded-lg p-4">
                                <h4 class="font-bold text-green-700 flex items-center">
                                    <i class="fa fa-map-marker mr-2"></i>出行攻略
                                </h4>
                                <div id="heritage-transport" class="mt-2 text-gray-700">
                                    <!-- 内容将通过JS动态填充 -->
                                </div>
                            </div>

                            <!-- 互动任务 -->
                            <div class="bg-orange-50 rounded-lg p-4">
                                <h4 class="font-bold text-orange-700 flex items-center">
                                    <i class="fa fa-tasks mr-2"></i>互动任务
                                </h4>
                                <div id="heritage-tasks" class="mt-2 text-gray-700">
                                    <!-- 内容将通过JS动态填充 -->
                                </div>
                            </div>

                            <!-- 分享按钮 -->
                            <button id="share-guide" class="w-full bg-accent hover:bg-orange-600 text-white font-bold py-3 px-6 rounded-lg shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-1">
                                <i class="fa fa-share-alt mr-2"></i>生成打卡模板
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 热门非遗体验 -->
            <div class="mt-12">
                <h3 class="text-xl font-bold text-primary mb-4 text-center">热门非遗体验</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- 热门体验1 -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all">
                        <img src="https://p11-doubao-search-sign.byteimg.com/ecom-shop-material/jpeg_m_310a4f65614628ac41fa3862a1c90ddc_sx_285843_www640-640~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644941&x-signature=KZKEjhCEPmrDCbfJRoSqs%2FXDBdY%3D" alt="江家瓷烧制" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="font-bold text-primary">江家瓷烧制体验</h4>
                            <p class="text-sm text-gray-600 mb-2">体验传统制瓷工艺，亲手制作精美瓷器</p>
                            <div class="flex items-center text-sm text-gray-500">
                                <i class="fa fa-map-marker mr-1"></i>
                                <span>磁器口古镇</span>
                                <span class="mx-2">|</span>
                                <i class="fa fa-clock-o mr-1"></i>
                                <span>2小时</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- 热门体验2 -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all">
                        <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/80b77053c8e94f41916416ae9786b1e8~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=hz7Cvsb64kvq0nma0oFm8TF2k%2FA%3D" alt="李氏花毽" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="font-bold text-primary">李氏花毽体验</h4>
                            <p class="text-sm text-gray-600 mb-2">学习传统花毽制作，体验民间体育乐趣</p>
                            <div class="flex items-center text-sm text-gray-500">
                                <i class="fa fa-map-marker mr-1"></i>
                                <span>沙坪坝区文化馆</span>
                                <span class="mx-2">|</span>
                                <i class="fa fa-clock-o mr-1"></i>
                                <span>1.5小时</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- 热门体验3 -->
                    <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all">
                        <img src="https://p3-doubao-search-sign.byteimg.com/labis/1e0e7579770b7afcece258517dfeed94~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644929&x-signature=d6%2FXNB33gRL8zhSqVjGR%2Br9XLmo%3D" alt="磁器口古镇" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="font-bold text-primary">磁器口古镇文化之旅</h4>
                            <p class="text-sm text-gray-600 mb-2">探访千年古镇，感受巴渝文化魅力</p>
                            <div class="flex items-center text-sm text-gray-500">
                                <i class="fa fa-map-marker mr-1"></i>
                                <span>磁器口古镇</span>
                                <span class="mx-2">|</span>
                                <i class="fa fa-clock-o mr-1"></i>
                                <span>半天</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 关于项目 -->
    <section id="about" class="py-16 bg-gradient-to-b from-white to-blue-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-primary mb-4">关于项目</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto">
                    AI赋能校地文化融合项目旨在通过人工智能技术，促进重庆师范大学与沙坪坝区非物质文化遗产的深度联动
                </p>
            </div>

            <div class="flex flex-col lg:flex-row gap-8 items-center">
                <div class="lg:w-1/2">
                    <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/43a73e58b33c450b9b2cf20e135da845~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=U519%2BcMn%2BwiOHT5dP%2BKQ4VNPpLE%3D" alt="项目介绍" class="rounded-xl shadow-lg w-full">
                </div>
                <div class="lg:w-1/2">
                    <h3 class="text-2xl font-bold text-primary mb-4">项目背景</h3>
                    <p class="text-gray-700 mb-4">
                        非物质文化遗产是中华民族优秀传统文化的重要组成部分，承载着历史记忆和文化基因。然而，随着时代发展，许多非遗项目面临传承困境。同时，高校作为文化传承与创新的重要阵地，拥有丰富的人才资源和创新能力。
                    </p>
                    <p class="text-gray-700 mb-4">
                        本项目通过AI技术连接重庆师范大学与沙坪坝区非物质文化遗产，搭建校地文化融合平台，既为非遗传承注入青春活力，也丰富了校园文化生活。
                    </p>
                    
                    <h3 class="text-2xl font-bold text-primary mb-4 mt-6">核心价值</h3>
                    <ul class="space-y-2 text-gray-700">
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>促进校地资源共享，实现文化传承与创新</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>降低文化参与门槛，让更多人了解和体验非遗文化</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>通过AI技术创新文化传播方式，提升文化体验感</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>搭建青年学生参与文化传承的平台，培养文化自信</span>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- 合作单位 -->
            <div class="mt-16">
                <h3 class="text-xl font-bold text-primary mb-6 text-center">合作单位</h3>
                <div class="flex flex-wrap justify-center items-center gap-8">
                    <div class="bg-white rounded-lg shadow-md p-4 flex items-center justify-center w-48 h-24">
                        <span class="text-xl font-bold text-primary">重庆师范大学</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-4 flex items-center justify-center w-48 h-24">
                        <span class="text-xl font-bold text-primary">沙坪坝区文化和旅游发展委员会</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-4 flex items-center justify-center w-48 h-24">
                        <span class="text-xl font-bold text-primary">沙坪坝区非物质文化遗产保护中心</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-primary text-white py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between">
                <div class="mb-8 md:mb-0">
                    <h3 class="text-xl font-bold mb-4">AI赋能校地文化融合</h3>
                    <p class="text-blue-200">
                        重师×沙坪坝非遗联动新玩法
                    </p>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-3 gap-8">
                    <div>
                        <h4 class="text-lg font-bold mb-3">快速链接</h4>
                        <ul class="space-y-2">
                            <li><a href="#home" class="text-blue-200 hover:text-white transition-colors">首页</a></li>
                            <li><a href="#postcard" class="text-blue-200 hover:text-white transition-colors">AI明信片</a></li>
                            <li><a href="#guide" class="text-blue-200 hover:text-white transition-colors">非遗体验官</a></li>
                            <li><a href="#about" class="text-blue-200 hover:text-white transition-colors">关于项目</a></li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-lg font-bold mb-3">相关资源</h4>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-blue-200 hover:text-white transition-colors">沙坪坝非遗名录</a></li>
                            <li><a href="#" class="text-blue-200 hover:text-white transition-colors">重师校园文化</a></li>
                            <li><a href="#" class="text-blue-200 hover:text-white transition-colors">文化体验活动</a></li>
                            <li><a href="#" class="text-blue-200 hover:text-white transition-colors">志愿者招募</a></li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-lg font-bold mb-3">联系我们</h4>
                        <ul class="space-y-2">
                            <li class="flex items-center">
                                <i class="fa fa-envelope mr-2"></i>
                                <a href="mailto:contact@aiculture.com" class="text-blue-200 hover:text-white transition-colors">contact@aiculture.com</a>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-phone mr-2"></i>
                                <span class="text-blue-200">023-12345678</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="border-t border-blue-800 mt-8 pt-8 text-center">
                <p class="text-blue-200">© 2025 AI赋能校地文化融合项目. 保留所有权利.</p>
            </div>
        </div>
    </footer>

    <!-- 返回顶部按钮 -->
    <button id="back-to-top" class="fixed bottom-8 right-8 bg-primary hover:bg-blue-800 text-white w-12 h-12 rounded-full shadow-lg flex items-center justify-center transition-all transform hover:-translate-y-1 opacity-0 invisible">
        <i class="fa fa-arrow-up"></i>
    </button>

    <!-- JavaScript -->
    <script>
        // 移动端菜单切换
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // 返回顶部按钮
        const backToTopButton = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', function() {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('opacity-0', 'invisible');
                backToTopButton.classList.add('opacity-100', 'visible');
            } else {
                backToTopButton.classList.remove('opacity-100', 'visible');
                backToTopButton.classList.add('opacity-0', 'invisible');
            }
        });
        
        backToTopButton.addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    // 关闭移动端菜单
                    document.getElementById('mobile-menu').classList.add('hidden');
                    
                    // 滚动到目标位置
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // AI明信片生成系统
        (function() {
            const generateButton = document.getElementById('generate-postcard');
            const postcardPreview = document.getElementById('postcard-preview');
            const postcardActions = document.getElementById('postcard-actions');
            const postcardTitle = document.getElementById('postcard-title');
            const postcardDescription = document.getElementById('postcard-description');
            const downloadButton = document.getElementById('download-postcard');
            const shareButton = document.getElementById('share-postcard');
            
            // 元素选择
            const campusElements = document.querySelectorAll('#campus-elements .element-item');
            const heritageElements = document.querySelectorAll('#heritage-elements .element-item');
            
            let selectedCampus = null;
            let selectedHeritage = null;
            
            // 校园地标选择
            campusElements.forEach(element => {
                element.addEventListener('click', function() {
                    campusElements.forEach(el => el.classList.remove('border-primary'));
                    this.classList.add('border-primary');
                    selectedCampus = this.dataset.element;
                });
            });
            
            // 非遗元素选择
            heritageElements.forEach(element => {
                element.addEventListener('click', function() {
                    heritageElements.forEach(el => el.classList.remove('border-primary'));
                    this.classList.add('border-primary');
                    selectedHeritage = this.dataset.element;
                });
            });
            
            // 生成明信片
            generateButton.addEventListener('click', function() {
                const keywords = document.getElementById('keywords').value.trim();
                const language = document.querySelector('input[name="language"]:checked').value;
                
                // 验证选择
                if (!selectedCampus || !selectedHeritage) {
                    alert('请选择校园地标和非遗元素');
                    return;
                }
                
                // 模拟生成过程
                generateButton.disabled = true;
                generateButton.innerHTML = '<i class="fa fa-spinner fa-spin mr-2"></i>生成中...';
                
                setTimeout(() => {
                    // 根据选择的元素获取对应的图片
                    let previewImage = '';
                    let title = '重师×沙坪坝非遗联名明信片';
                    let description = '';
                    
                    if (selectedCampus === 'library' && selectedHeritage === 'jiang-ceramic') {
                        previewImage = 'https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/4d384c551c5b43f9b3a15162f752e4e9~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=6AqETaFHuP6DCj0kGWi0Y%2BMhwSM%3D';
                        description = '图书馆 × 江家瓷纹样';
                    } else if (selectedCampus === 'school-stone' && selectedHeritage === 'li-shuttlecock') {
                        previewImage = 'https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/80b77053c8e94f41916416ae9786b1e8~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=hz7Cvsb64kvq0nma0oFm8TF2k%2FA%3D';
                        description = '校训石 × 李氏花毽';
                    } else {
                        previewImage = 'https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/43a73e58b33c450b9b2cf20e135da845~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=U519%2BcMn%2BwiOHT5dP%2BKQ4VNPpLE%3D';
                        description = '校园风光 × 歌乐山';
                    }
                    
                    // 如果用户输入了关键词，使用关键词生成标题
                    if (keywords) {
                        title = keywords + ' 联名明信片';
                    }
                    
                    // 更新预览
                    postcardPreview.innerHTML = `<img src="${previewImage}" alt="明信片预览" class="max-h-full max-w-full object-contain rounded-lg">`;
                    postcardTitle.textContent = title;
                    postcardDescription.textContent = description;
                    
                    // 显示操作按钮
                    postcardActions.classList.remove('hidden');
                    
                    // 恢复按钮状态
                    generateButton.disabled = false;
                    generateButton.innerHTML = '<i class="fa fa-magic mr-2"></i>生成明信片';
                }, 1500);
            });
            
            // 下载明信片
            downloadButton.addEventListener('click', function() {
                alert('明信片已开始下载');
            });
            
            // 分享明信片
            shareButton.addEventListener('click', function() {
                alert('分享功能已触发，可分享到社交媒体');
            });
        })();

        // 非遗体验官智能匹配系统
        (function() {
            const matchButton = document.getElementById('match-heritage');
            const heritageResult = document.getElementById('heritage-result');
            const heritageGuide = document.getElementById('heritage-guide');
            const heritageKnowledge = document.getElementById('heritage-knowledge');
            const heritageTransport = document.getElementById('heritage-transport');
            const heritageTasks = document.getElementById('heritage-tasks');
            const shareGuideButton = document.getElementById('share-guide');
            
            // 兴趣标签选择
            const tagItems = document.querySelectorAll('#interest-tags .tag-item');
            const selectedTags = new Set();
            
            tagItems.forEach(tag => {
                tag.addEventListener('click', function() {
                    const tagName = this.dataset.tag;
                    
                    if (selectedTags.has(tagName)) {
                        selectedTags.delete(tagName);
                        this.classList.remove('bg-primary', 'text-white');
                        this.classList.add('bg-gray-100');
                    } else {
                        selectedTags.add(tagName);
                        this.classList.remove('bg-gray-100');
                        this.classList.add('bg-primary', 'text-white');
                    }
                });
            });
            
            // 匹配非遗体验
            matchButton.addEventListener('click', function() {
                const additionalInfo = document.getElementById('additional-info').value.trim();
                
                // 验证选择
                if (selectedTags.size === 0) {
                    alert('请至少选择一个兴趣标签');
                    return;
                }
                
                // 模拟匹配过程
                matchButton.disabled = true;
                matchButton.innerHTML = '<i class="fa fa-spinner fa-spin mr-2"></i>匹配中...';
                
                setTimeout(() => {
                    // 根据选择的标签生成匹配结果
                    let heritageImage = '';
                    let heritageTitle = '';
                    let knowledgeContent = '';
                    let transportContent = '';
                    let tasksContent = '';
                    
                    // 根据选择的标签组合生成不同的结果
                    if (selectedTags.has('handcraft')) {
                        heritageImage = 'https://p11-doubao-search-sign.byteimg.com/ecom-shop-material/jpeg_m_310a4f65614628ac41fa3862a1c90ddc_sx_285843_www640-640~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644941&x-signature=KZKEjhCEPmrDCbfJRoSqs%2FXDBdY%3D';
                        heritageTitle = '江家瓷烧制体验';
                        knowledgeContent = `
                            <p class="mb-2">江家瓷是沙坪坝区传统制瓷工艺，有着悠久的历史和独特的艺术风格。</p>
                            <p>江家瓷以其精湛的工艺、独特的釉色和精美的纹饰而闻名，是重庆地区重要的非物质文化遗产之一。制作过程包括选料、制坯、施釉、烧制等多个环节，每个环节都需要工匠的精心操作。</p>
                        `;
                        transportContent = `
                            <p class="mb-2"><strong>公交路线：</strong>从重师出发，乘坐261路公交车到磁器口站下车，步行约10分钟即可到达江家瓷工作室。</p>
                            <p><strong>地铁路线：</strong>乘坐轨道交通1号线到磁器口站，从1号出口出站，步行约15分钟。</p>
                        `;
                        tasksContent = `
                            <ul class="list-disc pl-5 space-y-1">
                                <li>学习江家瓷的基本制作工艺</li>
                                <li>亲手制作一个简单的陶瓷作品</li>
                                <li>体验传统釉彩绘制技巧</li>
                                <li>了解陶瓷烧制过程</li>
                                <li>完成作品并拍照留念</li>
                            </ul>
                        `;
                    } else if (selectedTags.has('traditional') || selectedTags.has('history')) {
                        heritageImage = 'https://p3-doubao-search-sign.byteimg.com/labis/1e0e7579770b7afcece258517dfeed94~tplv-be4g95zd3a-image.jpeg?rk3s=542c0f93&x-expires=1780644929&x-signature=d6%2FXNB33gRL8zhSqVjGR%2Br9XLmo%3D';
                        heritageTitle = '磁器口古镇文化之旅';
                        knowledgeContent = `
                            <p class="mb-2">磁器口古镇始建于宋代，是重庆地区保存最为完好的明清建筑群之一，有着"小重庆"之称。</p>
                            <p>古镇内有众多历史文化遗迹和非物质文化遗产，如宝轮寺、翰林院、钟家院等古建筑，以及各种传统手工艺和民间艺术表演。磁器口的毛血旺、麻花等特色小吃也享誉中外。</p>
                        `;
                        transportContent = `
                            <p class="mb-2"><strong>公交路线：</strong>从重师出发，乘坐261路、808路或503路公交车到磁器口站下车。</p>
                            <p><strong>地铁路线：</strong>乘坐轨道交通1号线到磁器口站，从1号出口出站即可到达古镇入口。</p>
                        `;
                        tasksContent = `
                            <ul class="list-disc pl-5 space-y-1">
                                <li>参观磁器口古镇历史文化陈列馆</li>
                                <li>走访传统手工作坊，了解非遗工艺</li>
                                <li>体验传统小吃制作过程</li>
                                <li>观看民间艺术表演</li>
                                <li>收集古镇文创产品</li>
                            </ul>
                        `;
                    } else {
                        heritageImage = 'https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/80b77053c8e94f41916416ae9786b1e8~tplv-a9rns2rl98-image.image?rcl=2025120715350405ECFBC20101B5BB86B7&rk3s=8e244e95&rrcfp=f06b921b&x-expires=1767684966&x-signature=hz7Cvsb64kvq0nma0oFm8TF2k%2FA%3D';
                        heritageTitle = '李氏花毽体验';
                        knowledgeContent = `
                            <p class="mb-2">李氏花毽是沙坪坝区传统民间体育项目，有着百余年的历史，2011年被列入重庆市非物质文化遗产名录。</p>
                            <p>李氏花毽以其精湛的技艺、丰富的花样和深厚的文化内涵而闻名。花毽制作工艺独特，选用优质材料，经过多道工序精心制作而成。踢花毽不仅可以锻炼身体，还能欣赏到优美的动作和技巧。</p>
                        `;
                        transportContent = `
                            <p class="mb-2"><strong>公交路线：</strong>从重师出发，乘坐209路或210路公交车到沙坪坝区文化馆站下车。</p>
                            <p><strong>地铁路线：</strong>乘坐轨道交通1号线到沙坪坝站，从3号出口出站，步行约10分钟即可到达。</p>
                        `;
                        tasksContent = `
                            <ul class="list-disc pl-5 space-y-1">
                                <li>了解李氏花毽的历史渊源</li>
                                <li>学习花毽的基本踢法</li>
                                <li>体验花毽制作过程</li>
                                <li>参与花毽表演互动</li>
                                <li>拍摄花毽技巧展示</li>
                            </ul>
                        `;
                    }
                    
                    // 如果用户提供了额外信息，添加个性化建议
                    if (additionalInfo) {
                        knowledgeContent += `<p class="mt-2 text-primary font-medium">根据你的额外兴趣：${additionalInfo}，我们特别推荐你关注该非遗项目中的相关内容。</p>`;
                    }
                    
                    // 更新结果
                    heritageResult.innerHTML = `
                        <div class="w-full">
                            <img src="${heritageImage}" alt="${heritageTitle}" class="w-full h-48 object-cover rounded-lg mb-3">
                            <h4 class="text-xl font-bold text-primary">${heritageTitle}</h4>
                        </div>
                    `;
                    
                    heritageKnowledge.innerHTML = knowledgeContent;
                    heritageTransport.innerHTML = transportContent;
                    heritageTasks.innerHTML = tasksContent;
                    
                    // 显示指南内容
                    heritageGuide.classList.remove('hidden');
                    
                    // 恢复按钮状态
                    matchButton.disabled = false;
                    matchButton.innerHTML = '<i class="fa fa-search mr-2"></i>匹配非遗体验';
                }, 1500);
            });
            
            // 生成打卡模板
            shareGuideButton.addEventListener('click', function() {
                alert('打卡模板已生成，可一键分享到社交媒体');
            });
        })();

        // 页面加载动画
        window.addEventListener('load', function() {
            document.body.classList.add('loaded');
        });
    </script>
</body>
</html>
