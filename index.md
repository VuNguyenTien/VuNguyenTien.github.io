<meta name="google-signin-scope" content="profile email">
<meta name="google-signin-client_id" content="917478473326-9ktuoio4mkem8t3k2im4a3t3eb7t3df8.apps.googleusercontent.com">
<script src="https://apis.google.com/js/platform.js" async defer></script>

<div class="g-signin2" data-onsuccess="onSignIn" data-theme="dark"></div>
    <script>
      function onSignIn(googleUser) {
        // Useful data for your client-side scripts:
        var profile = googleUser.getBasicProfile();
        alert("ID: " + profile.getId()); // Don't send this directly to your server!
        alert('Full Name: ' + profile.getName());
        alert('Given Name: ' + profile.getGivenName());
        alert('Family Name: ' + profile.getFamilyName());
        alert("Image URL: " + profile.getImageUrl());
        alert("Email: " + profile.getEmail());

        // The ID token you need to pass to your backend:
        var id_token = googleUser.getAuthResponse().id_token;
        alert("ID Token: " + id_token);
      };
    </script>





<body class="single single-post postid-3555 single-format-standard custom-background mp6 customizer-styles-applied masthead-fixed singular highlander-enabled highlander-light">
<div id="page" class="hfeed site">
	
	<header id="masthead" class="site-header" role="banner">
		<div class="header-main">
			<h1 class="site-title"><a href="https://toidicodedao.com/" rel="home">Từ coder đến developer – Tôi đi code dạo</a></h1>

			<div class="search-toggle">
				<a href="#search-container" class="screen-reader-text" aria-expanded="false" aria-controls="search-container">Search</a>
			</div>

			<nav id="primary-navigation" class="site-navigation primary-navigation" role="navigation">
				<button class="menu-toggle">Primary Menu</button>
				<a class="screen-reader-text skip-link" href="#content">Skip to content</a>
				<div class="menu-menu-container"><ul id="primary-menu" class="nav-menu"><li id="menu-item-10" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-home menu-item-10"><a href="https://toidicodedao.com/">Home</a></li>
<li id="menu-item-2378" class="menu-item menu-item-type-post_type menu-item-object-post menu-item-2378"><a title="Những series/bài viết hay nhất trên blog" href="https://toidicodedao.com/2016/05/26/tong-hop-nhung-seriesbai-viet-hay-nhat-tren-blog/">Bài viết hay</a></li>
<li id="menu-item-12" class="menu-item menu-item-type-taxonomy menu-item-object-category current-post-ancestor current-menu-parent current-post-parent menu-item-has-children menu-item-12"><a title="Những kiến thức technical hay ho" href="https://toidicodedao.com/category/chuyen-coding/">Chuyện coding</a>
<ul class="sub-menu">
	<li id="menu-item-3739" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3739"><a title="Những kiến thức vô cùng cơ bản về bảo mật cho developer" target="_blank" href="https://toidicodedao.com/tag/series-bao-mat-nhap-mon/">Series Bảo mật nhập môn</a></li>
	<li id="menu-item-3756" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3756"><a title="Cùng viết tool nhận diện khuôn mặt JAV Idol với Microsoft Cognitive API" target="_blank" href="https://toidicodedao.com/tag/series-nhan-dien-idol/">Series Nhận diện Idol</a></li>
	<li id="menu-item-3742" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3742"><a title="Giới thiệu về các nguyên tắc SOLID, giúp bạn viết code sạch hơn, dễ mở rộng và bảo trì hơn" target="_blank" href="https://toidicodedao.com/tag/series-solid/">Seris SOLID</a></li>
	<li id="menu-item-3738" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3738"><a title="Những điều thú vị trong C#" target="_blank" href="https://toidicodedao.com/tag/c-hay-ho/">Series C# hay ho</a></li>
	<li id="menu-item-3740" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3740"><a title="Giới thiệu những điểm sida khó nhằn của JavaScript mà bao senior developer cũng sức đầu mẻ trán" target="_blank" href="https://toidicodedao.com/tag/javascript-sida/">Series JavaScript sida</a></li>
	<li id="menu-item-3749" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3749"><a title="Tìm hiểu về JavaScript với phong cách kiếm hiệp" target="_blank" href="https://toidicodedao.com/tag/js-truyen-ki/">Series JS Truyền Kì</a></li>
	<li id="menu-item-3741" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3741"><a title="Quay về với những thứ tinh túy, nền tảng của lập trình" target="_blank" href="https://toidicodedao.com/tag/phan-phac-qui-chan/">Series Phản Phác Qui Chân</a></li>
</ul>
</li>
<li id="menu-item-14" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-has-children menu-item-14"><a title="Những kinh nghiệm làm việc, kĩ năng mềm mà ai cũng nên biết" href="https://toidicodedao.com/category/chuyen-nghe-nghiep/">Chuyện nghề nghiệp</a>
<ul class="sub-menu">
	<li id="menu-item-3746" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3746"><a target="_blank" href="https://toidicodedao.com/2015/11/17/mat-toi-cua-nganh-cong-nghiep-it-phan-1/">Mặt tối của ngành IT</a></li>
	<li id="menu-item-3747" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3747"><a title="Kinh nghiệm học tiếng Anh, ôn thi TOEIC, IELTS" target="_blank" href="https://toidicodedao.com/2016/02/25/chuyen-hoc-tieng-anh-phan-1-toi-da-hoc-tieng-anh-nhu-the-nao/">Series Chuyện học tiếng Anh</a></li>
	<li id="menu-item-3744" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3744"><a href="https://toidicodedao.com/2015/06/04/nhung-dieu-truong-dai-hoc-khong-day-ban-phan-1/">Series Những điều Đại Học không dạy bạn</a></li>
	<li id="menu-item-3743" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3743"><a target="_blank" href="https://toidicodedao.com/2015/06/23/cach-tiep-can-1-ngon-ngucong-nghe-moi-phan-1/">Cách tiếp cận công nghệ mới</a></li>
	<li id="menu-item-3745" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3745"><a target="_blank" href="https://toidicodedao.com/2015/07/16/muon-neo-duong-tim-viec-phan-1-viet-cv-ro-rang-va-chuyen-nghiep/">Muôn nẻo đường tìm việc</a></li>
	<li id="menu-item-3748" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3748"><a title="Một số trải nghiệm thú vị của mình khi học, sinh hoạt và làm việc tại Quảng Châu, Trung Quốc" target="_blank" href="https://toidicodedao.com/tag/series-chuyen-ben-khua/">Series Chuyện bên Khựa</a></li>
</ul>
</li>
<li id="menu-item-13" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-has-children menu-item-13"><a title="Một số chuyện linh tinh, cái nhìn về ngành nghề" href="https://toidicodedao.com/category/chuyen-linh-tinh/">Chuyện linh tinh</a>
<ul class="sub-menu">
	<li id="menu-item-3750" class="menu-item menu-item-type-post_type menu-item-object-post menu-item-3750"><a title="Thay lời muốn nói – gởi tới những người thân yêu của mỗi lập trình viên" target="_blank" href="https://toidicodedao.com/2016/04/21/thay-loi-muon-noi-goi-toi-nhung-nguoi-than-yeu-cua-moi-lap-trinh-vien/">Thay lời muốn nói</a></li>
	<li id="menu-item-3751" class="menu-item menu-item-type-post_type menu-item-object-post menu-item-3751"><a title="Thực trạng học lập trình của một số thanh niên hiện nay" target="_blank" href="https://toidicodedao.com/2015/12/17/thuc-trang-hoc-lap-trinh-cua-mot-so-thanh-nien-hien-nay/">Thực trạng học lập trình của sinh viên</a></li>
	<li id="menu-item-3754" class="menu-item menu-item-type-post_type menu-item-object-post menu-item-3754"><a title="C# là ngôn ngữ tuyệt vời nhất. Java, PHP, C, C++, Ruby chỉ toàn là thứ rẻ tiền" target="_blank" href="https://toidicodedao.com/2015/07/30/c-la-ngon-ngu-tuyet-voi-nhat-java-php-c-c-ruby-chi-toan-la-thu-re-tien/">C# là ngôn ngữ tuyệt vời nhất</a></li>
</ul>
</li>
<li id="menu-item-15" class="menu-item menu-item-type-taxonomy menu-item-object-category current-post-ancestor current-menu-parent current-post-parent menu-item-has-children menu-item-15"><a title="Kiến thức cần thiết cho developer" href="https://toidicodedao.com/category/kien-thuc-can-thiet/">Kiến thức cần thiết</a>
<ul class="sub-menu">
	<li id="menu-item-3752" class="menu-item menu-item-type-post_type menu-item-object-post menu-item-3752"><a target="_blank" href="https://toidicodedao.com/2015/06/18/con-duong-phat-trien-su-nghiep-career-path-cho-developer/">Career Path cho Developer</a></li>
	<li id="menu-item-3753" class="menu-item menu-item-type-post_type menu-item-object-post menu-item-3753"><a title="Tạo động lực học tập và làm việc – Sức mạnh của thói quen" target="_blank" href="https://toidicodedao.com/2015/08/06/tao-dong-luc-hoc-tap-va-lam-viec-suc-manh-cua-thoi-quen/">Sức mạnh của thói quen</a></li>
	<li id="menu-item-3755" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3755"><a title="Review những sách hay mình đã đọc" target="_blank" href="https://toidicodedao.com/tag/review/">Review sách</a></li>
</ul>
</li>
<li id="menu-item-11" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-11"><a title="Thông tin về tác giả" href="https://toidicodedao.com/about/">About me</a></li>
</ul></div>			</nav>
		</div>

		<div id="search-container" class="search-box-wrapper hide">
			<div class="search-box">
				<form role="search" method="get" class="search-form" action="https://toidicodedao.com/">
				<label>
					<span class="screen-reader-text">Search for:</span>
					<input type="search" class="search-field" placeholder="Search …" value="" name="s">
				</label>
				<input type="submit" class="search-submit" value="Search">
			</form>			</div>
		</div>
	</header><!-- #masthead -->

	<div id="main" class="site-main">

	<div id="primary" class="content-area">
		<div id="content" class="site-content" role="main">
			
<article id="post-3555" class="post-3555 post type-post status-publish format-standard has-post-thumbnail hentry category-chuyen-coding category-kien-thuc-can-thiet tag-34758 tag-api tag-bing-api tag-code tag-idol tag-jav tag-jav-idol tag-javascript tag-js tag-microsoft tag-microsoft-cognitive-api tag-programming tag-restful tag-series-nhan-dien-idol tag-web-crawl tag-website">
	
	<div class="post-thumbnail">
	<img width="672" height="372" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=672&amp;h=372&amp;crop=1" class="attachment-post-thumbnail size-post-thumbnail wp-post-image" alt="screen-shot-2017-01-06-at-6-00-15-pm" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=672&amp;h=372&amp;crop=1 672w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=150&amp;h=83&amp;crop=1 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=300&amp;h=166&amp;crop=1 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=768&amp;h=425&amp;crop=1 768w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=1024&amp;h=567&amp;crop=1 1024w" sizes="(max-width: 672px) 100vw, 672px" data-attachment-id="3603" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-06-at-6-00-15-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg" data-orig-size="1320,938" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-06-at-6-00-15-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-6-00-15-pm.jpg?w=474">	</div>

	
	<header class="entry-header">
				<div class="entry-meta">
			<span class="cat-links"><a href="https://toidicodedao.com/category/chuyen-coding/" rel="category tag">Chuyện coding</a>, <a href="https://toidicodedao.com/category/kien-thuc-can-thiet/" rel="category tag">Kiến thức cần thiết</a></span>
		</div>
		<h1 class="entry-title">Series Nhận diện Idol: Phần 3 – Cùng đi đào dữ liệu VAV Idol</h1>
		<div class="entry-meta">
			<span class="entry-date"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/" rel="bookmark"><time class="entry-date" datetime="2017-01-17T00:06:28+00:00">17/01/2017</time></a></span> <span class="byline"><span class="author vcard"><a class="url fn n" href="https://toidicodedao.com/author/huyhoang8a5/" rel="author">Phạm Huy Hoàng</a></span></span>			<span class="comments-link"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#comments">5 Comments</a></span>
					</div><!-- .entry-meta -->
	</header><!-- .entry-header -->

		<div class="entry-content">
		<p>Sau bao ngày chờ đợi thì phần 3 của series cũng được ra mắt các bạn đọc. Lý do phần này bị mình “ngâm dấm” hơi lâu là do… JAV và 18+.</p>
<p>Do blog có nhiều trẻ em và cụ già đọc nên mình không thể thoải mái để link và hình ảnh 18+ trong bài viết được. Vì thế mình thay đổi hướng tiếp cận vấn đề. Thay vì nhận diện JAV Idol, chúng ta sẽ chuyển qua nhận diện… <strong>VAV Idol</strong>.</p>
<p>Sản phẩm cuối cùng của chúng ta sẽ có tương tự thế này, với kiến trúc đơn giản dễ hiểu hơn “Nhận diện Idol” nhiều: <a href="http://jav-idol.toidicodedao.com/vav/">http://jav-idol.toidicodedao.com/vav/</a>. Bắt đầu thôi nào!</p>
<p><span id="more-3555"></span></p>
<h3><b>Dữ liệu từ đâu ra?</b></h3>
<p>Trong các dự án machine learning và data maning, <strong>dữ liệu đầu vào vô cùng quan trọng</strong>. Thuật toán tốt đến mấy mà có quá ít dữ liệu mẫu, hoặc dữ liệu chất lượng không tốt thì cũng vứt, không thể cho kết quả tốt được. Để nhận diện được chính xác, ta phải có dữ liệu về tên idol cũng như ảnh của họ (càng nhiều càng tốt)&nbsp;để dạy cho máy.</p>
<p>Để tìm dữ liệu cho “Nhận diện idol”, mình phải lục tìm kha khá các trang JAV (xin thề là mình xem các trang này vì mục đích <strong>nghiên cứu học thuật</strong>). Sau khi đã tìm được, mình bắt đầu sử dụng <a href="https://toidicodedao.com/2015/07/28/tutorial-trich-xuat-thong-tin-tu-website-voi-html-aglitity-pack/">HTMLAgilityPack</a> để crawl dần dữ liệu. Do crawl dữ liệu nên hệ thống phải phụ thuộc vào nguồn dữ liệu của trang đấy (Đó là lý do ban đầu database của mình không có Takizawa Laura và Rina Ishihara).</p>
<p>Vì vậy, trong series này chúng ta không đi “cào” dữ liệu nữa, mà sẽ lấy trưc tiếp từ Bing Image Search (Không dùng của Google vì Bing dễ cài đặt hơn).</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png"><img class="aligncenter wp-image-3585" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=390&amp;h=321" alt="screen-shot-2017-01-05-at-11-20-15-pm" width="390" height="321" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=390&amp;h=321 390w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=780&amp;h=642 780w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=150&amp;h=123 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=300&amp;h=247 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=768&amp;h=632 768w" sizes="(max-width: 390px) 100vw, 390px"></a></p>
<h3><strong>Tìm hiểu Bing Image Search</strong></h3>
<p>Bing Image Search là một API nằm trong bộ <a href="https://toidicodedao.com/2016/07/25/microsoft-cognitive-service-api/">Microsoft Cognitive API</a>. Có thể hiểu một cách đơn giản là API này nhận vào nội dung ta muốn tìm kiếm và trả về hình ảnh liên quan.</p>
<p>Để có thể tiếp tục, các bạn hãy tạo cho mình 1 account Microsoft Cognitive Service nhé:</p>
<p>1. Vào đây để đăng ký: <a href="https://www.microsoft.com/cognitive-services/en-us/sign-up">https://www.microsoft.com/cognitive-services/en-us/sign-up</a>. Nếu có github hoặc linkedin thì dùng cho tiện. Sau khi đăng ký, nhớ vào hộp mail và active tài khoản theo link được gửi nhé.</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png"><img data-attachment-id="3584" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-05-at-11-06-28-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png" data-orig-size="2418,1062" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-05-at-11-06-28-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=428&amp;h=188" class="aligncenter wp-image-3584" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=428&amp;h=188" alt="screen-shot-2017-01-05-at-11-06-28-pm" width="428" height="188" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=428&amp;h=188 428w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=856&amp;h=376 856w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=150&amp;h=66 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=300&amp;h=132 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-06-28-pm.png?w=768&amp;h=337 768w" sizes="(max-width: 428px) 100vw, 428px"></a></p>
<p>2. Sau khi đăng nhập, bạn vào link này: <a href="https://www.microsoft.com/cognitive-services/en-us/bing-image-search-api">https://www.microsoft.com/cognitive-services/en-us/bing-image-search-api</a>. Bấm <strong>Get Started for Free</strong> -&gt; Kéo xuống bấm Subscribe để đăng kí sử dụng API. (Nếu chưa active thì bấm Send Verification rồi vào hộp mail, bấm link để active).</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png"><img data-attachment-id="3585" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-05-at-11-20-15-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png" data-orig-size="1340,1102" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-05-at-11-20-15-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=399&amp;h=328" class="aligncenter wp-image-3585" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=399&amp;h=328" alt="screen-shot-2017-01-05-at-11-20-15-pm" width="399" height="328" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=399&amp;h=328 399w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=798&amp;h=656 798w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=150&amp;h=123 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=300&amp;h=247 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-20-15-pm.png?w=768&amp;h=632 768w" sizes="(max-width: 399px) 100vw, 399px"></a></p>
<p>3. Bạn tiếp tục vào đây để kiểm tra các đăng kí của mình: <a href="https://www.microsoft.com/cognitive-services/en-us/subscriptions">https://www.microsoft.com/cognitive-services/en-us/subscriptions</a>, nếu thấy BingSearch là OK. Bấm Copy để copy Key, lưu key vào chỗ nào đó để còn sử dụng</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png"><img data-attachment-id="3586" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-05-at-11-21-52-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png" data-orig-size="1378,692" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-05-at-11-21-52-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=428&amp;h=215" class="aligncenter wp-image-3586" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=428&amp;h=215" alt="screen-shot-2017-01-05-at-11-21-52-pm" width="428" height="215" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=428&amp;h=215 428w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=856&amp;h=430 856w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=150&amp;h=75 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=300&amp;h=151 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-21-52-pm.png?w=768&amp;h=386 768w" sizes="(max-width: 428px) 100vw, 428px"></a></p>
<p>4. Đến đây là bạn có thể bắt đầu sử dụng Bing Search API rồi. Hãy bỏ 5 phút <a href="https://dev.cognitive.microsoft.com/docs/services/56b43f0ccf5ff8098cef3808/operations/571fab09dbe2d933e891028f">vào đây</a> đọc document của API này để biết cách sử dụng nhé.</p>
<p>5. Thử API: Chúng ta bật Postman lên và bắt đầu test thử nào (Xem lại hướng dẫn dùng Postman ở bài trước)., dán link sau đây và chọn method GET: <a href="https://api.cognitive.microsoft.com/bing/v5.0/images/search?q=ngọc" rel="nofollow">https://api.cognitive.microsoft.com/bing/v5.0/images/search?q=ngọc</a> trinh&amp;count=30.</p>
<p>Ta muốn tìm ảnh “Ngọc Trinh” nên dùng param q=Ngọc Trinh. Trong mục header, hãy tạo 1 header với key là&nbsp;Ocp-Apim-Subscription-Key, value là key bạn vừa copy khi nãy.</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/test.png"><img data-attachment-id="3588" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/test/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/test.png" data-orig-size="1200,868" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="test" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/test.png?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/test.png?w=428&amp;h=310" class="aligncenter wp-image-3588" src="https://toidicodedao.files.wordpress.com/2017/01/test.png?w=428&amp;h=310" alt="test" width="428" height="310" srcset="https://toidicodedao.files.wordpress.com/2017/01/test.png?w=428&amp;h=310 428w, https://toidicodedao.files.wordpress.com/2017/01/test.png?w=856&amp;h=620 856w, https://toidicodedao.files.wordpress.com/2017/01/test.png?w=150&amp;h=109 150w, https://toidicodedao.files.wordpress.com/2017/01/test.png?w=300&amp;h=217 300w, https://toidicodedao.files.wordpress.com/2017/01/test.png?w=768&amp;h=556 768w" sizes="(max-width: 428px) 100vw, 428px"></a></p>
<p>Ta nhận được kết quả JSON từ API. Hãy chú ý 2 trường <em>thumbnailUrl</em> và <em>contentUrl</em>. Thử copy kết quả từ <em>contentUrl</em> ra xem nào.</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg"><img data-attachment-id="3591" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-05-at-11-35-19-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg" data-orig-size="1116,1004" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-05-at-11-35-19-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=389&amp;h=350" class="aligncenter wp-image-3591" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=389&amp;h=350" alt="screen-shot-2017-01-05-at-11-35-19-pm" width="389" height="350" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=389&amp;h=350 389w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=778&amp;h=700 778w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=150&amp;h=135 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=300&amp;h=270 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-05-at-11-35-19-pm.jpg?w=768&amp;h=691 768w" sizes="(max-width: 389px) 100vw, 389px"></a></p>
<p>Ok, nhìn dáng ngon thế này thì đúng là <strong>Ngọc-Còn-Trinh</strong> rồi. Chúng ta bắt đầu dùng API này để kiếm hình ảnh cho các Vietnam Idol nào.</p>
<h3><strong>Bắt đầu code và lấy dữ liệu</strong></h3>
<p>Để dễ demo, mình xin dùng một danh sách gồm 12 idol xinh đẹp sau (Bạn nào không thích có thể xem code bên dưới, thay thế bằng các idol khác)</p>
<ul>
<li class="p1"><span class="s1">Ngọc Trinh</span></li>
<li class="p1"><span class="s1">Bà tưng</span></li>
<li class="p1"><span class="s1">Hường Hana</span></li>
<li class="p1"><span class="s1">Hoang Thùy Linh</span></li>
<li class="p1"><span class="s1">Elly Trần</span></li>
<li class="p1"><span class="s1">Thuỷ Top</span></li>
<li class="p1"><span class="s1">Tâm Tít</span></li>
<li class="p1"><span class="s1">Midu</span></li>
<li class="p1"><span class="s1">Miu Lê</span></li>
<li class="p1"><span class="s1">Chi Pu</span></li>
<li class="p1"><span class="s1">Khả Ngân</span></li>
<li class="p1"><span class="s1">Angela Phương Trinh</span></li>
</ul>
<p>Ta sẽ viết một chương trình nhỏ nhỏ để gọi API của Microsoft, lấy dữ liệu về và lưu dưới dạng JSON. Do lười nên mình sẽ dùng JavaScript để viết, chạy thẳng từ browser luôn, khỏi cần cài đặt gì phức tạp.</p>
<p>Đây là source code của chương trình, các bạn đọc comment để hiểu code nhé. Có 2 điều cần lưu ý:</p>
<ul>
<li>Ở dòng 21, hãy <strong>thay key bằng key của Microsoft</strong> mà các bạn đăng kí phía trên</li>
<li>Có vài đoạn mình dùng async/await để code dễ đọc hơn, đỡ phải dùng callback. Cứ tạm hiểu async/await là cách để <a href="https://toidicodedao.com/2016/07/05/javascript-promise/">gọi hàm asynchonous</a> và không cần <a href="https://toidicodedao.com/2015/02/05/callback-trong-javascript/">callback</a> nhé. Mình sẽ có bài viết giải thích kĩ hơn sau.</li>
</ul>
<p><script src="https://gist.github.com/conanak99/ddfc06f75cc5a37257df42f28b7dc969.js"></script><link rel="stylesheet" href="https://assets-cdn.github.com/assets/gist-embed-d7829e4cb0b09afb29b517c0ae667eb603d664f6a1384f29f8bb4aace3a8314f.css"></p><div id="gist43540517" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-download-js" class="file">
    

  <div itemprop="text" class="blob-wrapper data type-javascript">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-download-js-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-download-js-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c"><span class="pl-c">//</span> Danh sách tên các idol cần lấy</span></td>
      </tr>
      <tr>
        <td id="file-download-js-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-download-js-LC2" class="blob-code blob-code-inner js-file-line"><span class="pl-k">let</span> allIdols <span class="pl-k">=</span> [</td>
      </tr>
      <tr>
        <td id="file-download-js-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-download-js-LC3" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Ngọc Trinh<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-download-js-LC4" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Bà tưng<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L5" class="blob-num js-line-number" data-line-number="5"></td>
        <td id="file-download-js-LC5" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Hường Hana<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L6" class="blob-num js-line-number" data-line-number="6"></td>
        <td id="file-download-js-LC6" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Hoàng Thùy Linh<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L7" class="blob-num js-line-number" data-line-number="7"></td>
        <td id="file-download-js-LC7" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Elly Trần<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L8" class="blob-num js-line-number" data-line-number="8"></td>
        <td id="file-download-js-LC8" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Thuỷ Top<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L9" class="blob-num js-line-number" data-line-number="9"></td>
        <td id="file-download-js-LC9" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Tâm Tít<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L10" class="blob-num js-line-number" data-line-number="10"></td>
        <td id="file-download-js-LC10" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Midu<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L11" class="blob-num js-line-number" data-line-number="11"></td>
        <td id="file-download-js-LC11" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Miu Lê<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L12" class="blob-num js-line-number" data-line-number="12"></td>
        <td id="file-download-js-LC12" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Chi Pu<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L13" class="blob-num js-line-number" data-line-number="13"></td>
        <td id="file-download-js-LC13" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Khả Ngân<span class="pl-pds">"</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L14" class="blob-num js-line-number" data-line-number="14"></td>
        <td id="file-download-js-LC14" class="blob-code blob-code-inner js-file-line">    <span class="pl-s"><span class="pl-pds">"</span>Angela Phương Trinh<span class="pl-pds">"</span></span></td>
      </tr>
      <tr>
        <td id="file-download-js-L15" class="blob-num js-line-number" data-line-number="15"></td>
        <td id="file-download-js-LC15" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-download-js-L16" class="blob-num js-line-number" data-line-number="16"></td>
        <td id="file-download-js-LC16" class="blob-code blob-code-inner js-file-line">];</td>
      </tr>
      <tr>
        <td id="file-download-js-L17" class="blob-num js-line-number" data-line-number="17"></td>
        <td id="file-download-js-LC17" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-download-js-L18" class="blob-num js-line-number" data-line-number="18"></td>
        <td id="file-download-js-LC18" class="blob-code blob-code-inner js-file-line"><span class="pl-c"><span class="pl-c">//</span> Hàm gọi Bing Search API để lấy ảnh</span></td>
      </tr>
      <tr>
        <td id="file-download-js-L19" class="blob-num js-line-number" data-line-number="19"></td>
        <td id="file-download-js-LC19" class="blob-code blob-code-inner js-file-line"><span class="pl-k">async</span> <span class="pl-k">function</span> <span class="pl-en">getImage</span>(<span class="pl-smi">query</span>) {</td>
      </tr>
      <tr>
        <td id="file-download-js-L20" class="blob-num js-line-number" data-line-number="20"></td>
        <td id="file-download-js-LC20" class="blob-code blob-code-inner js-file-line">    <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">`</span>Begin getting images for <span class="pl-s1"><span class="pl-pse">${</span>query<span class="pl-pse">}</span></span><span class="pl-pds">`</span></span>);</td>
      </tr>
      <tr>
        <td id="file-download-js-L21" class="blob-num js-line-number" data-line-number="21"></td>
        <td id="file-download-js-LC21" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">var</span> key <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>******c35ad9854f28<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> Thay bằng API Key của bạn</span></td>
      </tr>
      <tr>
        <td id="file-download-js-L22" class="blob-num js-line-number" data-line-number="22"></td>
        <td id="file-download-js-LC22" class="blob-code blob-code-inner js-file-line">  </td>
      </tr>
      <tr>
        <td id="file-download-js-L23" class="blob-num js-line-number" data-line-number="23"></td>
        <td id="file-download-js-LC23" class="blob-code blob-code-inner js-file-line">    <span class="pl-c"><span class="pl-c">//</span> Gọi API, truyền key vào header, lấy kết quả trả về dạng </span></td>
      </tr>
      <tr>
        <td id="file-download-js-L24" class="blob-num js-line-number" data-line-number="24"></td>
        <td id="file-download-js-LC24" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">var</span> url <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">`</span><span class="skimlinks-unlinked">https://api.cognitive.microsoft.com/bing/v5.0/images/search?q</span>=<span class="pl-s1"><span class="pl-pse">${</span>query<span class="pl-pse">}</span></span>&amp;count=30<span class="pl-pds">`</span></span>;</td>
      </tr>
      <tr>
        <td id="file-download-js-L25" class="blob-num js-line-number" data-line-number="25"></td>
        <td id="file-download-js-LC25" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">var</span> result <span class="pl-k">=</span> <span class="pl-k">await</span> <span class="pl-en">fetch</span>(url, {</td>
      </tr>
      <tr>
        <td id="file-download-js-L26" class="blob-num js-line-number" data-line-number="26"></td>
        <td id="file-download-js-LC26" class="blob-code blob-code-inner js-file-line">        method<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>GET<span class="pl-pds">'</span></span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L27" class="blob-num js-line-number" data-line-number="27"></td>
        <td id="file-download-js-LC27" class="blob-code blob-code-inner js-file-line">        headers<span class="pl-k">:</span> {</td>
      </tr>
      <tr>
        <td id="file-download-js-L28" class="blob-num js-line-number" data-line-number="28"></td>
        <td id="file-download-js-LC28" class="blob-code blob-code-inner js-file-line">            <span class="pl-s"><span class="pl-pds">'</span>Ocp-Apim-Subscription-Key<span class="pl-pds">'</span></span><span class="pl-k">:</span> key</td>
      </tr>
      <tr>
        <td id="file-download-js-L29" class="blob-num js-line-number" data-line-number="29"></td>
        <td id="file-download-js-LC29" class="blob-code blob-code-inner js-file-line">        }</td>
      </tr>
      <tr>
        <td id="file-download-js-L30" class="blob-num js-line-number" data-line-number="30"></td>
        <td id="file-download-js-LC30" class="blob-code blob-code-inner js-file-line">    }).<span class="pl-en">then</span>(<span class="pl-smi">rs</span> <span class="pl-k">=&gt;</span> <span class="pl-smi">rs</span>.<span class="pl-en">json</span>());</td>
      </tr>
      <tr>
        <td id="file-download-js-L31" class="blob-num js-line-number" data-line-number="31"></td>
        <td id="file-download-js-LC31" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-download-js-L32" class="blob-num js-line-number" data-line-number="32"></td>
        <td id="file-download-js-LC32" class="blob-code blob-code-inner js-file-line">    <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">`</span>Finish getting images for <span class="pl-s1"><span class="pl-pse">${</span>query<span class="pl-pse">}</span></span><span class="pl-pds">`</span></span>);</td>
      </tr>
      <tr>
        <td id="file-download-js-L33" class="blob-num js-line-number" data-line-number="33"></td>
        <td id="file-download-js-LC33" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-download-js-L34" class="blob-num js-line-number" data-line-number="34"></td>
        <td id="file-download-js-LC34" class="blob-code blob-code-inner js-file-line">    <span class="pl-c"><span class="pl-c">//</span> Lọc bớt, chỉ lấy link thumbnail và link ảnh</span></td>
      </tr>
      <tr>
        <td id="file-download-js-L35" class="blob-num js-line-number" data-line-number="35"></td>
        <td id="file-download-js-LC35" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">return</span> <span class="pl-smi">result</span>.<span class="pl-c1">value</span>.<span class="pl-en">map</span>(<span class="pl-smi">vl</span> <span class="pl-k">=&gt;</span> {</td>
      </tr>
      <tr>
        <td id="file-download-js-L36" class="blob-num js-line-number" data-line-number="36"></td>
        <td id="file-download-js-LC36" class="blob-code blob-code-inner js-file-line">        <span class="pl-k">return</span> { thumbnail<span class="pl-k">:</span> <span class="pl-smi">vl</span>.<span class="pl-smi">thumbnailUrl</span>, image<span class="pl-k">:</span> <span class="pl-smi">vl</span>.<span class="pl-smi">contentUrl</span> };</td>
      </tr>
      <tr>
        <td id="file-download-js-L37" class="blob-num js-line-number" data-line-number="37"></td>
        <td id="file-download-js-LC37" class="blob-code blob-code-inner js-file-line">    });</td>
      </tr>
      <tr>
        <td id="file-download-js-L38" class="blob-num js-line-number" data-line-number="38"></td>
        <td id="file-download-js-LC38" class="blob-code blob-code-inner js-file-line">}</td>
      </tr>
      <tr>
        <td id="file-download-js-L39" class="blob-num js-line-number" data-line-number="39"></td>
        <td id="file-download-js-LC39" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-download-js-L40" class="blob-num js-line-number" data-line-number="40"></td>
        <td id="file-download-js-LC40" class="blob-code blob-code-inner js-file-line"><span class="pl-c"><span class="pl-c">//</span> Hàm tải dữ liệu về dưới dạng file .json</span></td>
      </tr>
      <tr>
        <td id="file-download-js-L41" class="blob-num js-line-number" data-line-number="41"></td>
        <td id="file-download-js-LC41" class="blob-code blob-code-inner js-file-line"><span class="pl-k">function</span> <span class="pl-en">downloadJson</span>(<span class="pl-smi">jsonObject</span>) {</td>
      </tr>
      <tr>
        <td id="file-download-js-L42" class="blob-num js-line-number" data-line-number="42"></td>
        <td id="file-download-js-LC42" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">var</span> dataStr <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>data:text/json;charset=utf-8,<span class="pl-pds">"</span></span> <span class="pl-k">+</span> <span class="pl-c1">encodeURIComponent</span>(<span class="pl-c1">JSON</span>.<span class="pl-en">stringify</span>(jsonObject));</td>
      </tr>
      <tr>
        <td id="file-download-js-L43" class="blob-num js-line-number" data-line-number="43"></td>
        <td id="file-download-js-LC43" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">var</span> dlAnchorElem <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">createElement</span>(<span class="pl-s"><span class="pl-pds">'</span>a<span class="pl-pds">'</span></span>);</td>
      </tr>
      <tr>
        <td id="file-download-js-L44" class="blob-num js-line-number" data-line-number="44"></td>
        <td id="file-download-js-LC44" class="blob-code blob-code-inner js-file-line">    <span class="pl-smi">dlAnchorElem</span>.<span class="pl-c1">setAttribute</span>(<span class="pl-s"><span class="pl-pds">"</span>href<span class="pl-pds">"</span></span>, dataStr);</td>
      </tr>
      <tr>
        <td id="file-download-js-L45" class="blob-num js-line-number" data-line-number="45"></td>
        <td id="file-download-js-LC45" class="blob-code blob-code-inner js-file-line">    <span class="pl-smi">dlAnchorElem</span>.<span class="pl-c1">setAttribute</span>(<span class="pl-s"><span class="pl-pds">"</span>download<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span><span class="skimlinks-unlinked">idols.json</span><span class="pl-pds">"</span></span>);</td>
      </tr>
      <tr>
        <td id="file-download-js-L46" class="blob-num js-line-number" data-line-number="46"></td>
        <td id="file-download-js-LC46" class="blob-code blob-code-inner js-file-line">    <span class="pl-smi">dlAnchorElem</span>.<span class="pl-c1">click</span>();</td>
      </tr>
      <tr>
        <td id="file-download-js-L47" class="blob-num js-line-number" data-line-number="47"></td>
        <td id="file-download-js-LC47" class="blob-code blob-code-inner js-file-line">};</td>
      </tr>
      <tr>
        <td id="file-download-js-L48" class="blob-num js-line-number" data-line-number="48"></td>
        <td id="file-download-js-LC48" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-download-js-L49" class="blob-num js-line-number" data-line-number="49"></td>
        <td id="file-download-js-LC49" class="blob-code blob-code-inner js-file-line"><span class="pl-c"><span class="pl-c">//</span> Bắt đầu chạy chương trình </span></td>
      </tr>
      <tr>
        <td id="file-download-js-L50" class="blob-num js-line-number" data-line-number="50"></td>
        <td id="file-download-js-LC50" class="blob-code blob-code-inner js-file-line">(<span class="pl-k">async</span>() <span class="pl-k">=&gt;</span> {</td>
      </tr>
      <tr>
        <td id="file-download-js-L51" class="blob-num js-line-number" data-line-number="51"></td>
        <td id="file-download-js-LC51" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">let</span> index <span class="pl-k">=</span> <span class="pl-c1">1</span>;</td>
      </tr>
      <tr>
        <td id="file-download-js-L52" class="blob-num js-line-number" data-line-number="52"></td>
        <td id="file-download-js-LC52" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">let</span> idolWithImage <span class="pl-k">=</span> [];</td>
      </tr>
      <tr>
        <td id="file-download-js-L53" class="blob-num js-line-number" data-line-number="53"></td>
        <td id="file-download-js-LC53" class="blob-code blob-code-inner js-file-line">  </td>
      </tr>
      <tr>
        <td id="file-download-js-L54" class="blob-num js-line-number" data-line-number="54"></td>
        <td id="file-download-js-LC54" class="blob-code blob-code-inner js-file-line">    <span class="pl-c"><span class="pl-c">//</span> Lấy ảnh của mỗi idol trong danh sách</span></td>
      </tr>
      <tr>
        <td id="file-download-js-L55" class="blob-num js-line-number" data-line-number="55"></td>
        <td id="file-download-js-LC55" class="blob-code blob-code-inner js-file-line">    <span class="pl-k">for</span> (<span class="pl-k">let</span> idol <span class="pl-k">of</span> allIdols) {</td>
      </tr>
      <tr>
        <td id="file-download-js-L56" class="blob-num js-line-number" data-line-number="56"></td>
        <td id="file-download-js-LC56" class="blob-code blob-code-inner js-file-line">        <span class="pl-k">var</span> images <span class="pl-k">=</span> <span class="pl-k">await</span> <span class="pl-en">getImage</span>(idol);</td>
      </tr>
      <tr>
        <td id="file-download-js-L57" class="blob-num js-line-number" data-line-number="57"></td>
        <td id="file-download-js-LC57" class="blob-code blob-code-inner js-file-line">        <span class="pl-smi">idolWithImage</span>.<span class="pl-c1">push</span>({</td>
      </tr>
      <tr>
        <td id="file-download-js-L58" class="blob-num js-line-number" data-line-number="58"></td>
        <td id="file-download-js-LC58" class="blob-code blob-code-inner js-file-line">            id<span class="pl-k">:</span> index<span class="pl-k">++</span>,</td>
      </tr>
      <tr>
        <td id="file-download-js-L59" class="blob-num js-line-number" data-line-number="59"></td>
        <td id="file-download-js-LC59" class="blob-code blob-code-inner js-file-line">            name<span class="pl-k">:</span> idol,</td>
      </tr>
      <tr>
        <td id="file-download-js-L60" class="blob-num js-line-number" data-line-number="60"></td>
        <td id="file-download-js-LC60" class="blob-code blob-code-inner js-file-line">            images<span class="pl-k">:</span> images</td>
      </tr>
      <tr>
        <td id="file-download-js-L61" class="blob-num js-line-number" data-line-number="61"></td>
        <td id="file-download-js-LC61" class="blob-code blob-code-inner js-file-line">        });</td>
      </tr>
      <tr>
        <td id="file-download-js-L62" class="blob-num js-line-number" data-line-number="62"></td>
        <td id="file-download-js-LC62" class="blob-code blob-code-inner js-file-line">    }</td>
      </tr>
      <tr>
        <td id="file-download-js-L63" class="blob-num js-line-number" data-line-number="63"></td>
        <td id="file-download-js-LC63" class="blob-code blob-code-inner js-file-line">    <span class="pl-en">console</span>.<span class="pl-c1">log</span>(idolWithImage);</td>
      </tr>
      <tr>
        <td id="file-download-js-L64" class="blob-num js-line-number" data-line-number="64"></td>
        <td id="file-download-js-LC64" class="blob-code blob-code-inner js-file-line">  </td>
      </tr>
      <tr>
        <td id="file-download-js-L65" class="blob-num js-line-number" data-line-number="65"></td>
        <td id="file-download-js-LC65" class="blob-code blob-code-inner js-file-line">    <span class="pl-c"><span class="pl-c">//</span> Tải dữ liệu về dưới dạng </span></td>
      </tr>
      <tr>
        <td id="file-download-js-L66" class="blob-num js-line-number" data-line-number="66"></td>
        <td id="file-download-js-LC66" class="blob-code blob-code-inner js-file-line">    <span class="pl-en">downloadJson</span>(idolWithImage);</td>
      </tr>
      <tr>
        <td id="file-download-js-L67" class="blob-num js-line-number" data-line-number="67"></td>
        <td id="file-download-js-LC67" class="blob-code blob-code-inner js-file-line">})();</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="https://gist.github.com/conanak99/ddfc06f75cc5a37257df42f28b7dc969/raw/a335cb736c72bef1d405c52e090dbaf333194f8c/download.js" style="float:right">view raw</a>
        <a href="https://gist.github.com/conanak99/ddfc06f75cc5a37257df42f28b7dc969#file-download-js">download.js</a>
        hosted with <img draggable="false" class="emoji" alt="❤" src="https://s0.wp.com/wp-content/mu-plugins/wpcom-smileys/twemoji/2/svg/2764.svg"> by <a href="https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>Để chạy chương trình, các bạn bấm Ctrl+Shift+I để mở Chrome Developer Tool, qua mục Console, dán code vào và Enter thôi nhé.</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg"><img data-attachment-id="3596" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-06-at-5-27-23-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg" data-orig-size="840,662" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-06-at-5-27-23-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=399&amp;h=315" class="aligncenter wp-image-3596" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=399&amp;h=315" alt="screen-shot-2017-01-06-at-5-27-23-pm" width="399" height="315" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=399&amp;h=315 399w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=798&amp;h=630 798w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=150&amp;h=118 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=300&amp;h=236 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-27-23-pm.jpg?w=768&amp;h=605 768w" sizes="(max-width: 399px) 100vw, 399px"></a></p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg"><img data-attachment-id="3597" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-06-at-4-11-04-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg" data-orig-size="820,547" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-06-at-4-11-04-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=419&amp;h=279" class="aligncenter wp-image-3597" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=419&amp;h=279" alt="screen-shot-2017-01-06-at-4-11-04-pm" width="419" height="279" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=419&amp;h=279 419w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=150&amp;h=100 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=300&amp;h=200 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg?w=768&amp;h=512 768w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-11-04-pm-e1483694931234.jpg 820w" sizes="(max-width: 419px) 100vw, 419px"></a></p>
<p>Kết quả của chương trình là một file có tên <strong><span class="skimlinks-unlinked">idols.json</span>&nbsp;</strong>chứa ID, tên và ảnh của link ảnh của các idol.</p>
<h3><strong>Lọc dữ liệu</strong></h3>
<p>Ta có thể làm thêm một bước lọc bằng tay để tăng độ chính xác của dữ liệu. Mình có viết 1 tool nhỏ nhỏ hỗ trợ việc này:</p>
<ol>
<li>Các bạn vào link này: <a href="http://embed.plnkr.co/kYlC10YPyyHT5FAuIZ8e/">http://embed.plnkr.co/kYlC10YPyyHT5FAuIZ8e/</a>, copy nội dung file <strong><span class="skimlinks-unlinked">idols.json</span></strong> trên máy rồi paste vào thay thế cho file <strong><span class="skimlinks-unlinked">idols.json</span></strong>&nbsp;trong này.</li>
</ol>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg"><img data-attachment-id="3598" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-06-at-5-34-07-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg" data-orig-size="1546,562" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-06-at-5-34-07-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=441&amp;h=160" class="aligncenter wp-image-3598" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=441&amp;h=160" alt="screen-shot-2017-01-06-at-5-34-07-pm" width="441" height="160" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=441&amp;h=160 441w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=880&amp;h=320 880w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=150&amp;h=55 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=300&amp;h=109 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-5-34-07-pm.jpg?w=768&amp;h=279 768w" sizes="(max-width: 441px) 100vw, 441px"></a></p>
<p>2. Kiểm tra các ảnh của idol bên phần preview. API của Microsoft cần ảnh dạng chính diện, ảnh một người. Nếu thấy tấm nào sai người, đông người hoặc không rõ mặt, bạn có thể bấm Delete để xóa (Tool chỉ hiện thumbnail, click vào ảnh để xem hình lớn).</p>
<p><a href="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg"><img data-attachment-id="3599" data-permalink="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/screen-shot-2017-01-06-at-4-45-17-pm/" data-orig-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg" data-orig-size="1894,1075" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="screen-shot-2017-01-06-at-4-45-17-pm" data-image-description="" data-medium-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=300" data-large-file="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=474&amp;h=269" class="aligncenter wp-image-3599 size-large" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=474&amp;h=269" width="474" height="269" srcset="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=474&amp;h=269 474w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=948&amp;h=538 948w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=150&amp;h=85 150w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=300&amp;h=170 300w, https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-06-at-4-45-17-pm-e1483695495560.jpg?w=768&amp;h=436 768w" sizes="(max-width: 474px) 100vw, 474px"></a></p>
<p>3. Kéo xuống dưới cùng, bấm Save Data để tải file <strong><span class="skimlinks-unlinked">filtered-idols.json</span></strong> về.</p>
<h3><strong>Kết</strong></h3>
<p>Chúc mừng các bạn đã kết thúc phần 3 khá dài hơi của series Nhận Diện Idol. Sau phần 3, chúng ta đã có <strong>dữ liệu của 12 idol với hơn 20 ảnh mỗi người</strong> để training cho máy.</p>
<p>Ờ phần sau, chúng ta sẽ tìm hiểu về cơ chế nhận diện khuôn mặt cũng như cách sử dụng API của Microsoft (Tương tự như Bing API thôi, không khó đâu).</p>
<p>Nếu có thắc mắc hay khó khăn gì, các bạn cứ thoải mái comment nhé.</p>
		<div class="wpcnt">
			<div class="wpa wpmrec" style="display: inline-block !important;">
				<span class="wpa-about">Advertisements</span>
				        <div id="crt-1699693639" style="width: 300px; height: 250px; display: none !important;"></div>
        <script type="text/javascript">
        var o = document.getElementById('crt-1699693639');
        if ("undefined"!=typeof Criteo) {
            var p = o.parentNode;
            p.style.setProperty('display', 'inline-block', 'important');
            o.style.setProperty('display', 'block', 'important');
            Criteo.DisplayAcceptableAdIfAdblocked({zoneid:388248,containerid:"crt-1699693639",collapseContainerIfNotAdblocked:true,"callifnotadblocked": function () {var o = document.getElementById('crt-1699693639'); o.style.setProperty('display','none','important');o.style.setProperty('visbility','hidden','important'); }
        });
        } else {
            o.style.setProperty('display', 'none', 'important');
            o.style.setProperty('visibility', 'hidden', 'important');
        }
        </script>
				<div class="u">
								<script type="text/javascript">
				(function(g){if("undefined"!=typeof g.__ATA){g.__ATA.initAd({sectionId:819766751, width:300, height:250});}})(window);
			</script><div id="automattic-id-2960" data-section="819766751" style="width:300px; height:250px;"><iframe width="300" height="250" style="border:none;width:300px;height:250px;" frameborder="0" scrolling="no" name="fif_slot_automattic-id-_automattic-id-2960" id="fif_slot_automattic-id-_automattic-id-2960" src="javascript:&quot;<html><body style='background:transparent;margin:0%;'></body></html>&quot;"></iframe></div>
				</div>
			</div>
		</div><div class="teads_slot"></div><div id="jp-post-flair" class="sharedaddy sd-rating-enabled sd-like-enabled sd-sharing-enabled"><div class="sd-block sd-rating"><h3 class="sd-title">Rate this:</h3><div class="pd-rating" id="pd_rating_holder_8005199_post_3555" style="display: inline-block;"><div class="rating-icons" id="pd_rate_8005199_post_3555" style="float:left;"><div class="rating-star-icon" onmouseout="PDRTJS_8005199_post_3555.rebuild();" onclick="PDRTJS_8005199_post_3555.rate(1);" onmouseover="PDRTJS_8005199_post_3555.hover(1);" id="PDRTJS_8005199_post_3555_stars_1" style="background-size: 32px 48px !important; cursor: pointer; width: 16px; height: 16px; line-height: 16px; background: url(https://polldaddy.com/images/ratings/star-yellow-sml.png) bottom left; float: left; padding: 0px; margin: 0px; margin-right: 1px;">&nbsp;</div><div class="rating-star-icon" onmouseout="PDRTJS_8005199_post_3555.rebuild();" onclick="PDRTJS_8005199_post_3555.rate(2);" onmouseover="PDRTJS_8005199_post_3555.hover(2);" id="PDRTJS_8005199_post_3555_stars_2" style="background-size: 32px 48px !important; cursor: pointer; width: 16px; height: 16px; line-height: 16px; background: url(https://polldaddy.com/images/ratings/star-yellow-sml.png) bottom left; float: left; padding: 0px; margin: 0px; margin-right: 1px;">&nbsp;</div><div class="rating-star-icon" onmouseout="PDRTJS_8005199_post_3555.rebuild();" onclick="PDRTJS_8005199_post_3555.rate(3);" onmouseover="PDRTJS_8005199_post_3555.hover(3);" id="PDRTJS_8005199_post_3555_stars_3" style="background-size: 32px 48px !important; cursor: pointer; width: 16px; height: 16px; line-height: 16px; background: url(https://polldaddy.com/images/ratings/star-yellow-sml.png) bottom left; float: left; padding: 0px; margin: 0px; margin-right: 1px;">&nbsp;</div><div class="rating-star-icon" onmouseout="PDRTJS_8005199_post_3555.rebuild();" onclick="PDRTJS_8005199_post_3555.rate(4);" onmouseover="PDRTJS_8005199_post_3555.hover(4);" id="PDRTJS_8005199_post_3555_stars_4" style="background-size: 32px 48px !important; cursor: pointer; width: 16px; height: 16px; line-height: 16px; background: url(https://polldaddy.com/images/ratings/star-yellow-sml.png) bottom left; float: left; padding: 0px; margin: 0px; margin-right: 1px;">&nbsp;</div><div class="rating-star-icon" onmouseout="PDRTJS_8005199_post_3555.rebuild();" onclick="PDRTJS_8005199_post_3555.rate(5);" onmouseover="PDRTJS_8005199_post_3555.hover(5);" id="PDRTJS_8005199_post_3555_stars_5" style="background-size: 32px 48px !important; cursor: pointer; width: 16px; height: 16px; line-height: 16px; background: url(https://polldaddy.com/images/ratings/star-yellow-sml.png) bottom left; float: left; padding: 0px; margin: 0px; margin-right: 1px;">&nbsp;</div></div><span style="float:left;">&nbsp;</span><div id="rating_info_8005199_post_3555" style="display:block;float:left;background:url(https://polldaddy.com/images/ratings/info.png) no-repeat 3px 2px;width:16px;height:16px;cursor:pointer; null " onclick="javascript:PDRTJS_8005199_post_3555.togglePopup();return false;"><span style="display:none;">i</span></div><div class="pd_popup_holder" id="pd_popup_holder_8005199_post_3555">&nbsp;</div><div class="rating-msg" id="PDRTJS_8005199_post_3555_msg" style="float:left; padding-left: 5px; text-align: left; font:normal normal /16px ; color: #;">Rate This</div><p style="padding: 0px; margin: 0px; clear: both;"></p></div></div><div class="sharedaddy sd-sharing-enabled"><div class="robots-nocontent sd-block sd-social sd-social-official sd-sharing"><div class="sd-content"><ul><li class="share-facebook"><div class="fb-share-button fb_iframe_widget" data-href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/" data-layout="button_count" fb-xfbml-state="rendered" fb-iframe-plugin-query="app_id=249643311490&amp;container_width=0&amp;href=https%3A%2F%2Ftoidicodedao.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F&amp;layout=button_count&amp;locale=en_US&amp;sdk=joey"><span style="vertical-align: bottom; width: 85px; height: 20px;"><iframe name="f1a08c5e56c5f4" width="1000px" height="1000px" frameborder="0" allowtransparency="true" allowfullscreen="true" scrolling="no" title="fb:share_button Facebook Social Plugin" src="https://www.facebook.com/v2.3/plugins/share_button.php?app_id=249643311490&amp;channel=https%3A%2F%2Fstaticxx.facebook.com%2Fconnect%2Fxd_arbiter%2Fr%2Fao6eUeuGXQq.js%3Fversion%3D42%23cb%3Df198b0f995d41c4%26domain%3Dtoidicodedao.com%26origin%3Dhttps%253A%252F%252Ftoidicodedao.com%252Ff23661d793a6e38%26relation%3Dparent.parent&amp;container_width=0&amp;href=https%3A%2F%2Ftoidicodedao.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F&amp;layout=button_count&amp;locale=en_US&amp;sdk=joey" style="border: none; visibility: visible; width: 85px; height: 20px;" class=""></iframe></span></div></li><li class="share-linkedin"><div class="linkedin_button"><span class="IN-widget" style="line-height: 1; vertical-align: baseline; display: inline-block; text-align: center;"><span style="padding: 0px !important; margin: 0px !important; text-indent: 0px !important; display: inline-block !important; vertical-align: baseline !important; font-size: 1px !important;"><span id="li_ui_li_gen_1488340413745_0"><a id="li_ui_li_gen_1488340413745_0-link" href="javascript:void(0);"><span id="li_ui_li_gen_1488340413745_0-logo">in</span><span id="li_ui_li_gen_1488340413745_0-title"><span id="li_ui_li_gen_1488340413745_0-mark"></span><span id="li_ui_li_gen_1488340413745_0-title-text">Share</span></span></a></span></span><span style="padding: 0px !important; margin: 0px !important; text-indent: 0px !important; display: inline-block !important; vertical-align: baseline !important; font-size: 1px !important;"><span id="li_ui_li_gen_1488340413760_1-container" class="IN-right"><span id="li_ui_li_gen_1488340413760_1" class="IN-right"><span id="li_ui_li_gen_1488340413760_1-inner" class="IN-right"><span id="li_ui_li_gen_1488340413760_1-content" class="IN-right">5</span></span></span></span></span></span><script type="in/share+init" data-url="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/" data-counter="right"></script></div></li><li class="share-end"></li></ul></div></div></div><div class="sharedaddy sd-block sd-like jetpack-likes-widget-wrapper jetpack-likes-widget-loaded" id="like-post-wrapper-81976675-3555-58b6446756509" data-src="//widgets.wp.com/likes/#blog_id=81976675&amp;post_id=3555&amp;origin=toidicodedao.wordpress.com&amp;obj_id=81976675-3555-58b6446756509" data-name="like-post-frame-81976675-3555-58b6446756509"><h3 class="sd-title">Like this:</h3><div class="likes-widget-placeholder post-likes-widget-placeholder" style="height: 55px; display: none;"><span class="button"><span>Like</span></span> <span class="loading">Loading...</span></div><iframe class="post-likes-widget jetpack-likes-widget" name="like-post-frame-81976675-3555-58b6446756509" height="55px" width="100%" frameborder="0" src="//widgets.wp.com/likes/#blog_id=81976675&amp;post_id=3555&amp;origin=toidicodedao.wordpress.com&amp;obj_id=81976675-3555-58b6446756509"></iframe><span class="sd-text-color"></span><a class="sd-link-color"></a></div>
<div id="jp-relatedposts" class="jp-relatedposts" style="display: block;">
	<h3 class="jp-relatedposts-headline"><em>Related</em></h3>
<div class="jp-relatedposts-items jp-relatedposts-items-visual"><div class="jp-relatedposts-post jp-relatedposts-post0 jp-relatedposts-post-thumbs" data-post-id="3447" data-post-format="false"><a class="jp-relatedposts-post-a" href="https://toidicodedao.com/2016/12/27/nhan-dien-idol-phan-2-kien-truc-cong-nghe/" title="Series Nhận diện Idol: Phần 2 - Kiến trúc tổng thể và các công nghệ sử dụng

Ở bài viết trước, mình đã giới thiệu về sự ra đời của Nhận Diện Idol. Ở phần này, mình sẽ tập trung về khía cạnh techincal như kiến trúc tổng thể và công nghệ sử dụng trong ứng dụng nhé. Toàn bộ series Nhận diện Idol: Phần 1 -…" rel="nofollow" data-origin="3555" data-position="0"><img class="jp-relatedposts-post-img" src="https://toidicodedao.files.wordpress.com/2016/12/architecture.jpg?w=350&amp;h=200&amp;crop=1" width="350" alt="Series Nhận diện Idol: Phần 2 - Kiến trúc tổng thể và các công nghệ sử dụng"></a><h4 class="jp-relatedposts-post-title"><a class="jp-relatedposts-post-a" href="https://toidicodedao.com/2016/12/27/nhan-dien-idol-phan-2-kien-truc-cong-nghe/" title="Series Nhận diện Idol: Phần 2 - Kiến trúc tổng thể và các công nghệ sử dụng

Ở bài viết trước, mình đã giới thiệu về sự ra đời của Nhận Diện Idol. Ở phần này, mình sẽ tập trung về khía cạnh techincal như kiến trúc tổng thể và công nghệ sử dụng trong ứng dụng nhé. Toàn bộ series Nhận diện Idol: Phần 1 -…" rel="nofollow" data-origin="3555" data-position="0">Series Nhận diện Idol: Phần 2 - Kiến trúc tổng thể và các công nghệ sử dụng</a></h4><p class="jp-relatedposts-post-excerpt">Ở bài viết trước, mình đã giới thiệu về sự ra đời của Nhận Diện Idol. Ở phần này, mình sẽ tập trung về khía cạnh techincal như kiến trúc tổng thể và công nghệ sử dụng trong ứng dụng nhé. Toàn bộ series Nhận diện Idol: Phần 1 -…</p><p class="jp-relatedposts-post-context">In "Chuyện coding"</p></div><div class="jp-relatedposts-post jp-relatedposts-post1 jp-relatedposts-post-thumbs" data-post-id="3615" data-post-format="false"><a class="jp-relatedposts-post-a" href="https://toidicodedao.com/2017/02/14/nhan-dien-idol-phan-4-2-microsoft-face-api-training/" title="Series Nhận diện Idol: Phần 4.2 - Sử dụng Microsoft Face API để training hệ thống

Sau phần 4.2, hẳn các bạn cũng đã hiểu cơ chế hoạt động của một hệ thống nhận diện khuôn mặt. Trong phần này, chúng ta sẽ sử dụng dữ liêu khuôn mặt đã có của 12 VAV Idol để huấn luyện cho máy (Được ngắm gái xinh chắc nó…" rel="nofollow" data-origin="3555" data-position="1"><img class="jp-relatedposts-post-img" src="https://toidicodedao.files.wordpress.com/2017/01/screen-shot-2017-01-08-at-2-11-51-am.jpg?w=350&amp;h=200&amp;crop=1" width="350" alt="Series Nhận diện Idol: Phần 4.2 - Sử dụng Microsoft Face API để training hệ thống"></a><h4 class="jp-relatedposts-post-title"><a class="jp-relatedposts-post-a" href="https://toidicodedao.com/2017/02/14/nhan-dien-idol-phan-4-2-microsoft-face-api-training/" title="Series Nhận diện Idol: Phần 4.2 - Sử dụng Microsoft Face API để training hệ thống

Sau phần 4.2, hẳn các bạn cũng đã hiểu cơ chế hoạt động của một hệ thống nhận diện khuôn mặt. Trong phần này, chúng ta sẽ sử dụng dữ liêu khuôn mặt đã có của 12 VAV Idol để huấn luyện cho máy (Được ngắm gái xinh chắc nó…" rel="nofollow" data-origin="3555" data-position="1">Series Nhận diện Idol: Phần 4.2 - Sử dụng Microsoft Face API để training hệ thống</a></h4><p class="jp-relatedposts-post-excerpt">Sau phần 4.2, hẳn các bạn cũng đã hiểu cơ chế hoạt động của một hệ thống nhận diện khuôn mặt. Trong phần này, chúng ta sẽ sử dụng dữ liêu khuôn mặt đã có của 12 VAV Idol để huấn luyện cho máy (Được ngắm gái xinh chắc nó…</p><p class="jp-relatedposts-post-context">In "Chuyện coding"</p></div><div class="jp-relatedposts-post jp-relatedposts-post2 jp-relatedposts-post-thumbs" data-post-id="3638" data-post-format="false"><a class="jp-relatedposts-post-a" href="https://toidicodedao.com/2017/02/28/series-nhan-dien-idol-phan-5-do-chinh-xac-thuat-toan/" title="Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán

Note - Fanpage và account Facebook mình đang bị 1 số thành phần phá hoại tìm cách report nên mình deactive tạm vài hôm thôi nhé. Mọi việc liên quan tới mua sách vẫn diễn ra bình thường, các bạn cứ liên hệ fanpage của nhà xuất bản hoặc gửi…" rel="nofollow" data-origin="3555" data-position="2"><img class="jp-relatedposts-post-img" src="https://toidicodedao.files.wordpress.com/2017/01/maxresdefault.jpg?w=350&amp;h=200&amp;crop=1" width="350" alt="Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán"></a><h4 class="jp-relatedposts-post-title"><a class="jp-relatedposts-post-a" href="https://toidicodedao.com/2017/02/28/series-nhan-dien-idol-phan-5-do-chinh-xac-thuat-toan/" title="Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán

Note - Fanpage và account Facebook mình đang bị 1 số thành phần phá hoại tìm cách report nên mình deactive tạm vài hôm thôi nhé. Mọi việc liên quan tới mua sách vẫn diễn ra bình thường, các bạn cứ liên hệ fanpage của nhà xuất bản hoặc gửi…" rel="nofollow" data-origin="3555" data-position="2">Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán</a></h4><p class="jp-relatedposts-post-excerpt">Note - Fanpage và account Facebook mình đang bị 1 số thành phần phá hoại tìm cách report nên mình deactive tạm vài hôm thôi nhé. Mọi việc liên quan tới mua sách vẫn diễn ra bình thường, các bạn cứ liên hệ fanpage của nhà xuất bản hoặc gửi…</p><p class="jp-relatedposts-post-context">In "Chuyện coding"</p></div></div></div></div>	</div><!-- .entry-content -->
	
	<footer class="entry-meta"><span class="tag-links"><a href="https://toidicodedao.com/tag/18/" rel="tag">18+</a><a href="https://toidicodedao.com/tag/api/" rel="tag">API</a><a href="https://toidicodedao.com/tag/bing-api/" rel="tag">bing api</a><a href="https://toidicodedao.com/tag/code/" rel="tag">code</a><a href="https://toidicodedao.com/tag/idol/" rel="tag">idol</a><a href="https://toidicodedao.com/tag/jav/" rel="tag">jav</a><a href="https://toidicodedao.com/tag/jav-idol/" rel="tag">jav idol</a><a href="https://toidicodedao.com/tag/javascript/" rel="tag">javascript</a><a href="https://toidicodedao.com/tag/js/" rel="tag">js</a><a href="https://toidicodedao.com/tag/microsoft/" rel="tag">microsoft</a><a href="https://toidicodedao.com/tag/microsoft-cognitive-api/" rel="tag">microsoft cognitive api</a><a href="https://toidicodedao.com/tag/programming/" rel="tag">programming</a><a href="https://toidicodedao.com/tag/restful/" rel="tag">restful</a><a href="https://toidicodedao.com/tag/series-nhan-dien-idol/" rel="tag">series nhận diện idol</a><a href="https://toidicodedao.com/tag/web-crawl/" rel="tag">web crawl</a><a href="https://toidicodedao.com/tag/website/" rel="tag">website</a></span></footer></article><!-- #post-## -->
	<nav class="navigation post-navigation" role="navigation">
		<h1 class="screen-reader-text">Post navigation</h1>
		<div class="nav-links">
			<a href="https://toidicodedao.com/2017/01/12/lam-gi-khi-khong-code/" rel="prev"><span class="meta-nav">Previous Post</span>Lập trình viên lúc không code thì… làm gì?</a><a href="https://toidicodedao.com/2017/01/19/code-pet-project/" rel="next"><span class="meta-nav">Next Post</span>Rảnh rỗi không biết code gì, sao không làm pet project?</a>		</div><!-- .nav-links -->
	</nav><!-- .navigation -->
	
<div id="comments" class="comments-area">

	
	<h2 class="comments-title">
		5 thoughts on “Series Nhận diện Idol: Phần 3 – Cùng đi đào dữ liệu VAV Idol”	</h2>

	
	<ol class="comment-list">
				<li id="comment-5044" class="comment byuser comment-author-hoangnn93 even thread-even depth-1 highlander-comment">
			<article id="div-comment-5044" class="comment-body">
				<footer class="comment-meta">
					<div class="comment-author vcard">
						<img alt="" src="https://0.gravatar.com/avatar/01fbb9415ce23ee879c1bc8c24aa1ec6?s=34&amp;d=https%3A%2F%2F0.gravatar.com%2Favatar%2Fad516503a11cd5ca435acc9bb6523536%3Fs%3D34&amp;r=G" class="avatar avatar-34 grav-hashed grav-hijack" height="34" width="34" id="grav-01fbb9415ce23ee879c1bc8c24aa1ec6-0">						<b class="fn"><a href="http://codeaholicguy.wordpress.com" rel="external nofollow" class="url">codeaholicguy</a></b> <span class="says">says:</span>					</div><!-- .comment-author -->

					<div class="comment-metadata">
						<a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#comment-5044">
							<time datetime="2017-01-17T01:00:48+00:00">
								17/01/2017 at 1:00 am							</time>
						</a>
											</div><!-- .comment-metadata -->

									</footer><!-- .comment-meta -->

				<div class="comment-content">
					<p>đã dùng async await rồi thì không cần dùng promise (.then) nữa đâu, ah hihi</p>
<p id="comment-like-5044" data-liked="comment-not-liked" class="comment-likes comment-not-liked"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?like_comment=5044&amp;_wpnonce=f7956660fa" class="comment-like-link needs-login" rel="nofollow" data-blog="81976675"><span>Like</span></a><span id="comment-like-count-5044" class="comment-like-feedback">Like</span></p>
				</div><!-- .comment-content -->

				<div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?replytocom=5044#respond" onclick="return addComment.moveForm( &quot;div-comment-5044&quot;, &quot;5044&quot;, &quot;respond&quot;, &quot;3555&quot; )" aria-label="Reply to codeaholicguy">Reply</a></div>			</article><!-- .comment-body -->
</li><!-- #comment-## -->
		<li id="comment-5048" class="comment odd alt thread-odd thread-alt depth-1 parent highlander-comment">
			<article id="div-comment-5048" class="comment-body">
				<footer class="comment-meta">
					<div class="comment-author vcard">
						<img alt="" src="https://1.gravatar.com/avatar/711427523360c0ffc6846f6d4386101c?s=34&amp;d=https%3A%2F%2F1.gravatar.com%2Favatar%2Fad516503a11cd5ca435acc9bb6523536%3Fs%3D34&amp;r=G" class="avatar avatar-34 grav-hashed grav-hijack" height="34" width="34" id="grav-711427523360c0ffc6846f6d4386101c-0">						<b class="fn">mrlun</b> <span class="says">says:</span>					</div><!-- .comment-author -->

					<div class="comment-metadata">
						<a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#comment-5048">
							<time datetime="2017-01-18T09:23:20+00:00">
								18/01/2017 at 9:23 am							</time>
						</a>
											</div><!-- .comment-metadata -->

									</footer><!-- .comment-meta -->

				<div class="comment-content">
					<p>Chào Hoàng, mình muốn hỏi làm thế nào để crawl dữ liệu trong biến javascript. Nghĩa là khi load trang sử dụng trình duyêt, trong console ta gõ tên biến chứa thông tin, khi view source code thì ko có tên biến này. Vậy khi viết tool làm thế nào để mình có thể đọc giá trị của các biến javascript đó. Cảm ơn Hoàng.</p>
<p id="comment-like-5048" data-liked="comment-not-liked" class="comment-likes comment-not-liked"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?like_comment=5048&amp;_wpnonce=2ca8085bc7" class="comment-like-link needs-login" rel="nofollow" data-blog="81976675"><span>Like</span></a><span id="comment-like-count-5048" class="comment-like-feedback">Like</span></p>
				</div><!-- .comment-content -->

				<div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?replytocom=5048#respond" onclick="return addComment.moveForm( &quot;div-comment-5048&quot;, &quot;5048&quot;, &quot;respond&quot;, &quot;3555&quot; )" aria-label="Reply to mrlun">Reply</a></div>			</article><!-- .comment-body -->
<ol class="children">
		<li id="comment-5049" class="comment byuser comment-author-huyhoang8a5 bypostauthor even depth-2 highlander-comment">
			<article id="div-comment-5049" class="comment-body">
				<footer class="comment-meta">
					<div class="comment-author vcard">
						<img alt="" src="https://1.gravatar.com/avatar/de0cdb393b4fcc100d471591994a5e0b?s=34&amp;d=https%3A%2F%2F1.gravatar.com%2Favatar%2Fad516503a11cd5ca435acc9bb6523536%3Fs%3D34&amp;r=G" class="avatar avatar-34 grav-hashed grav-hijack" height="34" width="34" id="grav-de0cdb393b4fcc100d471591994a5e0b-0">						<b class="fn"><a href="https://toidicodedao.wordpress.com" rel="external nofollow" class="url">Phạm Huy Hoàng</a></b> <span class="says">says:</span>					</div><!-- .comment-author -->

					<div class="comment-metadata">
						<a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#comment-5049">
							<time datetime="2017-01-18T09:45:16+00:00">
								18/01/2017 at 9:45 am							</time>
						</a>
											</div><!-- .comment-metadata -->

									</footer><!-- .comment-meta -->

				<div class="comment-content">
					<p>Cái này mình chịu, trước giờ crawl người ta vẫn thường crawl html thôi, bạn thử đổi hướng tiếp cận nhé ;).</p>
<p id="comment-like-5049" data-liked="comment-not-liked" class="comment-likes comment-not-liked"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?like_comment=5049&amp;_wpnonce=49fbaefc1f" class="comment-like-link needs-login" rel="nofollow" data-blog="81976675"><span>Like</span></a><span id="comment-like-count-5049" class="comment-like-feedback">Liked by <a href="#" class="view-likers" data-like-count="1">1 person</a></span></p>
				</div><!-- .comment-content -->

				<div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?replytocom=5049#respond" onclick="return addComment.moveForm( &quot;div-comment-5049&quot;, &quot;5049&quot;, &quot;respond&quot;, &quot;3555&quot; )" aria-label="Reply to Phạm Huy Hoàng">Reply</a></div>			</article><!-- .comment-body -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li id="comment-5109" class="comment odd alt thread-even depth-1 parent highlander-comment">
			<article id="div-comment-5109" class="comment-body">
				<footer class="comment-meta">
					<div class="comment-author vcard">
						<img alt="" src="https://2.gravatar.com/avatar/2c5d9b226d5f454beee1b57c439787f6?s=34&amp;d=https%3A%2F%2F2.gravatar.com%2Favatar%2Fad516503a11cd5ca435acc9bb6523536%3Fs%3D34&amp;r=G" class="avatar avatar-34 grav-hashed grav-hijack" height="34" width="34" id="grav-2c5d9b226d5f454beee1b57c439787f6-0">						<b class="fn"><a href="http://DucQuoc.wordpress.com" rel="external nofollow" class="url">DucQuoc.wordpress.com</a></b> <span class="says">says:</span>					</div><!-- .comment-author -->

					<div class="comment-metadata">
						<a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#comment-5109">
							<time datetime="2017-01-29T14:02:00+00:00">
								29/01/2017 at 2:02 pm							</time>
						</a>
											</div><!-- .comment-metadata -->

									</footer><!-- .comment-meta -->

				<div class="comment-content">
					<p>Trang demo của bạn ko chạy tốt lắm, chẳng hạn Link “Chi pu” này ko nhận diện được: </p>
<p><a href="http://img.f9.giaitri.vnecdn.net/2017/01/25/Chi-Pu-8-1485332821_660x0.jpg"><img src="https://i1.wp.com/img.f9.giaitri.vnecdn.net/2017/01/25/Chi-Pu-8-1485332821_660x0.jpg" style="max-width:100%;"></a></p>
<p>Còn link này nữa: Hoàng Thùy Linh được nhận thành Angela Phương Trinh</p>
<p><a href="http://img.f10.giaitri.vnecdn.net/2017/01/23/hoang-thuy-linh-1485152258_660x0.jpg"><img src="https://i1.wp.com/img.f10.giaitri.vnecdn.net/2017/01/23/hoang-thuy-linh-1485152258_660x0.jpg" style="max-width:100%;"></a></p>
<p>Chẳng lẽ phải “train” thêm để AI thông minh hơn?</p>
<p id="comment-like-5109" data-liked="comment-not-liked" class="comment-likes comment-not-liked"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?like_comment=5109&amp;_wpnonce=3703b7b305" class="comment-like-link needs-login" rel="nofollow" data-blog="81976675"><span>Like</span></a><span id="comment-like-count-5109" class="comment-like-feedback">Like</span></p>
				</div><!-- .comment-content -->

				<div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?replytocom=5109#respond" onclick="return addComment.moveForm( &quot;div-comment-5109&quot;, &quot;5109&quot;, &quot;respond&quot;, &quot;3555&quot; )" aria-label="Reply to DucQuoc.wordpress.com">Reply</a></div>			</article><!-- .comment-body -->
<ol class="children">
		<li id="comment-5110" class="comment byuser comment-author-huyhoang8a5 bypostauthor even depth-2 highlander-comment">
			<article id="div-comment-5110" class="comment-body">
				<footer class="comment-meta">
					<div class="comment-author vcard">
						<img alt="" src="https://1.gravatar.com/avatar/de0cdb393b4fcc100d471591994a5e0b?s=34&amp;d=https%3A%2F%2F1.gravatar.com%2Favatar%2Fad516503a11cd5ca435acc9bb6523536%3Fs%3D34&amp;r=G" class="avatar avatar-34 grav-hashed grav-hijack" height="34" width="34" id="grav-de0cdb393b4fcc100d471591994a5e0b-1">						<b class="fn"><a href="https://toidicodedao.wordpress.com" rel="external nofollow" class="url">Phạm Huy Hoàng</a></b> <span class="says">says:</span>					</div><!-- .comment-author -->

					<div class="comment-metadata">
						<a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#comment-5110">
							<time datetime="2017-01-29T14:54:37+00:00">
								29/01/2017 at 2:54 pm							</time>
						</a>
											</div><!-- .comment-metadata -->

									</footer><!-- .comment-meta -->

				<div class="comment-content">
					<p>Um, chờ tới phần 5 sẽ rõ bạn nhé ;).</p>
<p id="comment-like-5110" data-liked="comment-not-liked" class="comment-likes comment-not-liked"><a href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?like_comment=5110&amp;_wpnonce=05a1582cbe" class="comment-like-link needs-login" rel="nofollow" data-blog="81976675"><span>Like</span></a><span id="comment-like-count-5110" class="comment-like-feedback">Like</span></p>
				</div><!-- .comment-content -->

				<div class="reply"><a rel="nofollow" class="comment-reply-link" href="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/?replytocom=5110#respond" onclick="return addComment.moveForm( &quot;div-comment-5110&quot;, &quot;5110&quot;, &quot;respond&quot;, &quot;3555&quot; )" aria-label="Reply to Phạm Huy Hoàng">Reply</a></div>			</article><!-- .comment-body -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
	</ol><!-- .comment-list -->

	
	
	
					<div id="respond" class="comment-respond js">
			<h3 id="reply-title" class="comment-reply-title">Leave a Reply <small><a rel="nofollow" id="cancel-comment-reply-link" href="/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/#respond" style="display:none;">Cancel reply</a></small></h3>				<form action="https://toidicodedao.com/wp-comments-post.php" method="post" id="commentform" class="comment-form" novalidate="">
					<input type="hidden" id="highlander_comment_nonce" name="highlander_comment_nonce" value="a596325632"><input type="hidden" name="_wp_http_referer" value="/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/">
<input type="hidden" name="hc_post_as" id="hc_post_as" value="guest">

<div class="comment-form-field comment-textarea">
	
	<div id="comment-form-comment"><textarea tabindex="-1" style="position: absolute; top: -999px; left: 0px; right: auto; bottom: auto; border: 0px; padding: 0px; box-sizing: content-box; word-wrap: break-word; overflow: hidden; transition: none; height: 0px !important; min-height: 0px !important; font-family: Arial, Helvetica, Tahoma, Verdana, sans-serif; font-size: 14px; font-weight: 400; font-style: normal; letter-spacing: 0px; text-transform: none; text-decoration: none; word-spacing: 0px; text-indent: 0px; line-height: 21px; width: 451.771px;" class="autosizejs "></textarea><textarea id="comment" name="comment" title="Enter your comment here..." placeholder="Enter your comment here..." style="height: 40px; overflow: hidden; word-wrap: break-word; resize: none;"></textarea></div>
</div>

<div id="comment-form-identity" style="display: none;">

	<div id="comment-form-nascar">
		<p>Fill in your details below or click an icon to log in:</p>
		<ul>
			<li class="selected" style="display:none;">
				<a href="#comment-form-guest" id="postas-guest" title="Guest">
					<span></span>
				</a>
			</li>
			<li>
				<a href="#comment-form-load-service:WordPress.com" id="postas-wordpress" title="WordPress.com">
					<span></span>
				</a>
			</li>
			<li>
				<a href="#comment-form-load-service:Twitter" id="postas-twitter" title="Twitter">
					<span></span>
				</a>
			</li>
			<li>
				<a href="#comment-form-load-service:Facebook" id="postas-facebook" title="Facebook">
					<span></span>
				</a>
			</li>
			<li>
		</li></ul>
	</div>

	<div id="comment-form-guest" class="comment-form-service selected">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
<a href="https://gravatar.com/site/signup/" target="_blank">				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25" alt="Gravatar" width="25" class="no-grav">
</a>			</div>

				<div class="comment-form-fields">
				<div class="comment-form-field comment-form-email">
					<label for="email">Email <span class="required">(required)</span> <span class="nopublish">(Address never made public)</span></label>
					<div class="comment-form-input"><input id="email" name="email" type="email" value=""></div>
				</div>
				<div class="comment-form-field comment-form-author">
					<label for="author">Name <span class="required">(required)</span></label>
					<div class="comment-form-input"><input id="author" name="author" type="text" value=""></div>
				</div>
				<div class="comment-form-field comment-form-url">
					<label for="url">Website</label>
					<div class="comment-form-input"><input id="url" name="url" type="url" value=""></div>
				</div>
			</div>
	
		</div>
	</div>

	<div id="comment-form-wordpress" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25" alt="WordPress.com Logo" width="25" class="no-grav">
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="wp_avatar" id="wordpress-avatar" class="comment-meta-wordpress" value="">
				<input type="hidden" name="wp_user_id" id="wordpress-user_id" class="comment-meta-wordpress" value="">
				<input type="hidden" name="wp_access_token" id="wordpress-access_token" class="comment-meta-wordpress" value="">
				<p class="comment-form-posting-as pa-wordpress"><strong></strong> You are commenting using your <span class="skimlinks-unlinked">WordPress.com</span> account. <span class="comment-form-log-out">(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'wordpress' );">Log&nbsp;Out</a>&nbsp;/&nbsp;<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)</span></p>
			</div>
	
		</div>
	</div>

	<div id="comment-form-twitter" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25" alt="Twitter picture" width="25" class="no-grav">
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="twitter_avatar" id="twitter-avatar" class="comment-meta-twitter" value="">
				<input type="hidden" name="twitter_user_id" id="twitter-user_id" class="comment-meta-twitter" value="">
				<input type="hidden" name="twitter_access_token" id="twitter-access_token" class="comment-meta-twitter" value="">
				<p class="comment-form-posting-as pa-twitter"><strong></strong> You are commenting using your Twitter account. <span class="comment-form-log-out">(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'twitter' );">Log&nbsp;Out</a>&nbsp;/&nbsp;<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)</span></p>
			</div>
	
		</div>
	</div>

	<div id="comment-form-facebook" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25" alt="Facebook photo" width="25" class="no-grav">
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="fb_avatar" id="facebook-avatar" class="comment-meta-facebook" value="">
				<input type="hidden" name="fb_user_id" id="facebook-user_id" class="comment-meta-facebook" value="">
				<input type="hidden" name="fb_access_token" id="facebook-access_token" class="comment-meta-facebook" value="">
				<p class="comment-form-posting-as pa-facebook"><strong></strong> You are commenting using your Facebook account. <span class="comment-form-log-out">(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'facebook' );">Log&nbsp;Out</a>&nbsp;/&nbsp;<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)</span></p>
			</div>
	
		</div>
	</div>

	<div id="comment-form-googleplus" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25" alt="Google+ photo" width="25" class="no-grav">
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="googleplus_avatar" id="googleplus-avatar" class="comment-meta-googleplus" value="">
				<input type="hidden" name="googleplus_user_id" id="googleplus-user_id" class="comment-meta-googleplus" value="">
				<input type="hidden" name="googleplus_access_token" id="googleplus-access_token" class="comment-meta-googleplus" value="">
				<p class="comment-form-posting-as pa-googleplus"><strong></strong> You are commenting using your Google+ account. <span class="comment-form-log-out">(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'googleplus' );">Log&nbsp;Out</a>&nbsp;/&nbsp;<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)</span></p>
			</div>
	
		</div>
	</div>


	<div id="comment-form-load-service" class="comment-form-service">
		<div class="comment-form-posting-as-cancel"><a href="javascript:HighlanderComments.cancelExternalWindow();">Cancel</a></div>
		<p>Connecting to %s</p>
	</div>

</div>

<script type="text/javascript">
var highlander_expando_javascript = function(){
	var input = document.createElement( 'input' ),
	    comment = jQuery( '#comment' );

	if ( 'placeholder' in input ) {
		comment.attr( 'placeholder', jQuery( '.comment-textarea label' ).remove().text() );
	}

	// Expando Mode: start small, then auto-resize on first click + text length
	jQuery( '#comment-form-identity' ).hide();
	jQuery( '#comment-form-subscribe' ).hide();
	jQuery( '#commentform .form-submit' ).hide();

	comment.css( { 'height':'10px' } ).one( 'focus', function() {
		var timer = setInterval( HighlanderComments.resizeCallback, 10 )
		jQuery( this ).animate( { 'height': HighlanderComments.initialHeight } ).delay( 100 ).queue( function(n) { clearInterval( timer ); HighlanderComments.resizeCallback(); n(); } );
		jQuery( '#comment-form-identity' ).slideDown();
		jQuery( '#comment-form-subscribe' ).slideDown();
		jQuery( '#commentform .form-submit' ).slideDown();
	});
}
jQuery(document).ready( highlander_expando_javascript );
</script>

<div id="comment-form-subscribe" style="display: none;">
	<p class="comment-subscription-form"><input type="checkbox" name="subscribe" id="subscribe" value="subscribe" style="width: auto;"> <label class="subscribe-label" id="subscribe-label" for="subscribe" style="display: inline;">Notify me of new comments via email.</label></p><p class="post-subscription-form"><input type="checkbox" name="subscribe_blog" id="subscribe_blog" value="subscribe" style="width: auto;"> <label class="subscribe-label" id="subscribe-blog-label" for="subscribe_blog" style="display: inline;">Notify me of new posts via email.</label></p></div>




<p class="form-submit" style="display: none;"><input name="submit" type="submit" id="comment-submit" class="submit" value="Post Comment"> <input type="hidden" name="comment_post_ID" value="3555" id="comment_post_ID">
<input type="hidden" name="comment_parent" id="comment_parent" value="0">
</p><p style="display: none;"><input type="hidden" id="akismet_comment_nonce" name="akismet_comment_nonce" value="69988cfb78"></p>
<input type="hidden" name="genseq" value="1488340071">
<p style="display: none;"></p>				<input type="hidden" id="ak_js" name="ak_js" value="1488340412778"></form>
					</div><!-- #respond -->
		<div style="clear: both"></div>
</div><!-- #comments -->
		</div><!-- #content -->
	</div><!-- #primary -->

<div id="content-sidebar" class="content-sidebar widget-area" role="complementary">
	<aside id="search-5" class="widget widget_search"><form role="search" method="get" class="search-form" action="https://toidicodedao.com/">
				<label>
					<span class="screen-reader-text">Search for:</span>
					<input type="search" class="search-field" placeholder="Search …" value="" name="s">
				</label>
				<input type="submit" class="search-submit" value="Search">
			</form></aside><aside id="text-24" class="widget widget_text"><h1 class="widget-title">Sách do tôi viết</h1>			<div class="textwidget"><a target="_blank" href="http://security.toidicodedao.com/"><img style="width:40%;" src="https://toidicodedao.files.wordpress.com/2016/12/3dbook.png">
<p style="width:55%;display:inline-block;"><b>[Free Ebooks]</b> Bảo mật nhập môn - Bảo mật cơ bản cho developer</p>
</a>
<br><br><br>
<a target="_blank" href="https://goo.gl/forms/Xo1TSU2csnwwz5Sf2"><img style="width:40%;margin-top:-90px;" src="https://lh4.googleusercontent.com/XpLc2VqxYIAqmplMveYAW20LMdAv_uSmLfVvBuqtumiQCG1nOn65TVMyPgEKALH2gN6n2sG5gQ=w414">
<p style="width:55%;display:inline-block;"><b>[Sắp ra mắt]</b> Code dạo ký sự - Lập trình viên đâu phải chỉ biết code.<br><br><b>ORDER NGAY để được giảm 30% giá bìa (Số lượng có hạn)</b></p>
</a></div>
		</aside><aside id="top-posts-3" class="widget widget_top-posts"><h1 class="widget-title">Top Posts &amp; Pages</h1><ul class="widgets-list-layout no-grav">
					<li>
												<a href="https://toidicodedao.com/2017/02/28/series-nhan-dien-idol-phan-5-do-chinh-xac-thuat-toan/" title="Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán" class="bump-view" data-bump-view="tp">
							<img src="https://i1.wp.com/toidicodedao.files.wordpress.com/2017/01/maxresdefault.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2017/02/28/series-nhan-dien-idol-phan-5-do-chinh-xac-thuat-toan/" class="bump-view" data-bump-view="tp">
								Series Nhận diện Idol: Phần 5 - Kiểm tra độ chính xác của thuật toán							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2015/07/30/c-la-ngon-ngu-tuyet-voi-nhat-java-php-c-c-ruby-chi-toan-la-thu-re-tien/" title="C# là ngôn ngữ tuyệt vời nhất. Java, PHP, C, C++, Ruby chỉ toàn là thứ rẻ tiền" class="bump-view" data-bump-view="tp">
							<img src="https://i1.wp.com/toidicodedao.files.wordpress.com/2015/07/img.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="C# là ngôn ngữ tuyệt vời nhất. Java, PHP, C, C++, Ruby chỉ toàn là thứ rẻ tiền" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2015/07/30/c-la-ngon-ngu-tuyet-voi-nhat-java-php-c-c-ruby-chi-toan-la-thu-re-tien/" class="bump-view" data-bump-view="tp">
								C# là ngôn ngữ tuyệt vời nhất. Java, PHP, C, C++, Ruby chỉ toàn là thứ rẻ tiền							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2016/07/13/sai-lam-khi-hoc-lap-trinh/" title="Hai sai lầm lớn nhất trong quá trình học lập trình" class="bump-view" data-bump-view="tp">
							<img src="https://i1.wp.com/toidicodedao.files.wordpress.com/2016/04/nino_pc.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Hai sai lầm lớn nhất trong quá trình học lập trình" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2016/07/13/sai-lam-khi-hoc-lap-trinh/" class="bump-view" data-bump-view="tp">
								Hai sai lầm lớn nhất trong quá trình học lập trình							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2017/02/23/optimize-code-va-cuoc-song/" title="Series Chuyện Code Chuyện Đời - Từ tối ưu code cho đến optimize cuộc sống" class="bump-view" data-bump-view="tp">
							<img src="https://i0.wp.com/toidicodedao.files.wordpress.com/2017/02/ky1w7eac5em-maarten-van-den-heuvel1.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Series Chuyện Code Chuyện Đời - Từ tối ưu code cho đến optimize cuộc sống" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2017/02/23/optimize-code-va-cuoc-song/" class="bump-view" data-bump-view="tp">
								Series Chuyện Code Chuyện Đời - Từ tối ưu code cho đến optimize cuộc sống							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2015/11/03/dependency-injection-va-inversion-of-control-phan-1-dinh-nghia/" title="Dependency Injection và Inversion of Control - Phần 1: Định nghĩa" class="bump-view" data-bump-view="tp">
							<img src="https://i0.wp.com/toidicodedao.files.wordpress.com/2015/09/ioc-and-mapper-in-c-1-638.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Dependency Injection và Inversion of Control - Phần 1: Định nghĩa" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2015/11/03/dependency-injection-va-inversion-of-control-phan-1-dinh-nghia/" class="bump-view" data-bump-view="tp">
								Dependency Injection và Inversion of Control - Phần 1: Định nghĩa							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2015/03/24/solid-la-gi-ap-dung-cac-nguyen-ly-solid-de-tro-thanh-lap-trinh-vien-code-cung/" title="SOLID là gì - Áp dụng các nguyên lý SOLID để trở thành lập trình viên code &quot;cứng&quot;" class="bump-view" data-bump-view="tp">
							<img src="https://i0.wp.com/toidicodedao.files.wordpress.com/2015/02/keepcalm.png?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="SOLID là gì - Áp dụng các nguyên lý SOLID để trở thành lập trình viên code &quot;cứng&quot;" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2015/03/24/solid-la-gi-ap-dung-cac-nguyen-ly-solid-de-tro-thanh-lap-trinh-vien-code-cung/" class="bump-view" data-bump-view="tp">
								SOLID là gì - Áp dụng các nguyên lý SOLID để trở thành lập trình viên code "cứng"							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2015/06/18/con-duong-phat-trien-su-nghiep-career-path-cho-developer/" title="Con đường phát triển sự nghiệp (Career path) cho developer" class="bump-view" data-bump-view="tp">
							<img src="https://i0.wp.com/toidicodedao.files.wordpress.com/2015/06/img.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Con đường phát triển sự nghiệp (Career path) cho developer" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2015/06/18/con-duong-phat-trien-su-nghiep-career-path-cho-developer/" class="bump-view" data-bump-view="tp">
								Con đường phát triển sự nghiệp (Career path) cho developer							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2016/05/26/tong-hop-nhung-seriesbai-viet-hay-nhat-tren-blog/" title="Tổng hợp những series/bài viết hay nhất trên blog" class="bump-view" data-bump-view="tp">
							<img src="https://i1.wp.com/toidicodedao.files.wordpress.com/2016/05/12230712-best-of-the-best-rubber-stamp-stock-vector-winner.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Tổng hợp những series/bài viết hay nhất trên blog" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2016/05/26/tong-hop-nhung-seriesbai-viet-hay-nhat-tren-blog/" class="bump-view" data-bump-view="tp">
								Tổng hợp những series/bài viết hay nhất trên blog							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2016/01/12/tutorial-viet-ung-dung-di-dong-mot-cach-de-dang-voi-ionic-framework/" title="[Tutorial] Viết ứng dụng di động một cách dễ dàng với Ionic Framework" class="bump-view" data-bump-view="tp">
							<img src="https://i1.wp.com/toidicodedao.files.wordpress.com/2015/12/headerionic1.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="[Tutorial] Viết ứng dụng di động một cách dễ dàng với Ionic Framework" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2016/01/12/tutorial-viet-ung-dung-di-dong-mot-cach-de-dang-voi-ionic-framework/" class="bump-view" data-bump-view="tp">
								[Tutorial] Viết ứng dụng di động một cách dễ dàng với Ionic Framework							</a>
						</div>
											</li>
									<li>
												<a href="https://toidicodedao.com/2015/08/06/tao-dong-luc-hoc-tap-va-lam-viec-suc-manh-cua-thoi-quen/" title="Tạo động lực học tập và làm việc - Sức mạnh của thói quen" class="bump-view" data-bump-view="tp">
							<img src="https://i0.wp.com/toidicodedao.files.wordpress.com/2015/07/motivation.jpg?resize=40%2C40&amp;ssl=1" class="widgets-list-layout-blavatar" alt="Tạo động lực học tập và làm việc - Sức mạnh của thói quen" data-pin-nopin="true">
						</a>
						<div class="widgets-list-layout-links">
							<a href="https://toidicodedao.com/2015/08/06/tao-dong-luc-hoc-tap-va-lam-viec-suc-manh-cua-thoi-quen/" class="bump-view" data-bump-view="tp">
								Tạo động lực học tập và làm việc - Sức mạnh của thói quen							</a>
						</div>
											</li>
				</ul>
</aside><aside id="facebook-likebox-3" class="widget widget_facebook_likebox"><h1 class="widget-title"><a href="https://www.facebook.com/toidicodedao/">Like ngay để không bỏ lỡ những bài viết hay nhé!</a></h1>		<div id="fb-root" class=" fb_reset"><div style="position: absolute; top: -10000px; height: 0px; width: 0px;"><div><iframe name="fb_xdm_frame_https" frameborder="0" allowtransparency="true" allowfullscreen="true" scrolling="no" id="fb_xdm_frame_https" aria-hidden="true" title="Facebook Cross Domain Communication Frame" tabindex="-1" src="https://staticxx.facebook.com/connect/xd_arbiter/r/ao6eUeuGXQq.js?version=42#channel=f23661d793a6e38&amp;origin=https%3A%2F%2Ftoidicodedao.com" style="border: none;"></iframe></div></div><div style="position: absolute; top: -10000px; height: 0px; width: 0px;"><div></div></div></div>
		<div class="fb-page fb_iframe_widget" data-href="https://www.facebook.com/toidicodedao/" data-width="500" data-height="350" data-hide-cover="false" data-show-facepile="true" data-show-posts="true" fb-xfbml-state="rendered" fb-iframe-plugin-query="app_id=249643311490&amp;container_width=306&amp;height=350&amp;hide_cover=false&amp;href=https%3A%2F%2Fwww.facebook.com%2Ftoidicodedao%2F&amp;locale=en_US&amp;sdk=joey&amp;show_facepile=true&amp;show_posts=true&amp;width=500"><span style="vertical-align: bottom; width: 306px; height: 0px;"><iframe name="f36320d3bfe22a8" width="500px" height="350px" frameborder="0" allowtransparency="true" allowfullscreen="true" scrolling="no" title="fb:page Facebook Social Plugin" src="https://www.facebook.com/v2.3/plugins/page.php?app_id=249643311490&amp;channel=https%3A%2F%2Fstaticxx.facebook.com%2Fconnect%2Fxd_arbiter%2Fr%2Fao6eUeuGXQq.js%3Fversion%3D42%23cb%3Df15dc8626ee8e78%26domain%3Dtoidicodedao.com%26origin%3Dhttps%253A%252F%252Ftoidicodedao.com%252Ff23661d793a6e38%26relation%3Dparent.parent&amp;container_width=306&amp;height=350&amp;hide_cover=false&amp;href=https%3A%2F%2Fwww.facebook.com%2Ftoidicodedao%2F&amp;locale=en_US&amp;sdk=joey&amp;show_facepile=true&amp;show_posts=true&amp;width=500" style="border: none; visibility: visible; width: 306px; height: 0px;" class=""></iframe></span></div>
		<script>(function(d, s, id) { var js, fjs = d.getElementsByTagName(s)[0]; if (d.getElementById(id)) return; js = d.createElement(s); js.id = id; js.src = '//connect.facebook.net/en_US/sdk.js#xfbml=1&appId=249643311490&version=v2.3'; fjs.parentNode.insertBefore(js, fjs); }(document, 'script', 'facebook-jssdk'));</script>
		</aside><aside id="text-20" class="widget widget_text"><h1 class="widget-title">About me</h1>			<div class="textwidget"><img width="150px" src="https://toidicodedao.files.wordpress.com/2016/08/av.jpg">
<h5>Tôi là Phạm Huy Hoàng, một developer. Thuở còn là sinh viên, tôi từng có những thắc mắc, trăn trở về technical, về con đường nghề nghiệp, nhưng không có ai giải đáp.
<br>
Blog này là nơi tôi chia sẻ những kiến thức, kinh nghiệm mà mình đạt được trong quá trình làm việc và trải nghiệm. Mong rằng nó sẽ giải đáp phần nào những khúc mắc, trăn trở cho những bạn sinh viên như tôi ngày xưa.<br><a href="https://toidicodedao.com/about/">Đọc thêm về tôi và blog này</a></h5>
</div>
		</aside><aside id="text-22" class="widget widget_text"><h1 class="widget-title">Chat with Toidicodedao bot</h1>			<div class="textwidget"><a href="https://m.me/toidicodedao"><img src="https://toidicodedao.files.wordpress.com/2016/07/send-button.png"></a></div>
		</aside><aside id="wp_tag_cloud-7" class="widget wp_widget_tag_cloud"><h1 class="widget-title">Tags</h1><div style="overflow:hidden"><a href="https://toidicodedao.com/tag/blog/" class="tag-link-273 tag-link-position-1" title="17 topics" style="font-size: 10.933333333333pt;">blog</a>
<a href="https://toidicodedao.com/tag/bao-mat/" class="tag-link-1134293 tag-link-position-2" title="13 topics" style="font-size: 9.4666666666667pt;">bảo mật</a>
<a href="https://toidicodedao.com/tag/c/" class="tag-link-2426 tag-link-position-3" title="42 topics" style="font-size: 15.866666666667pt;">c#</a>
<a href="https://toidicodedao.com/tag/c-net/" class="tag-link-49277 tag-link-position-4" title="27 topics" style="font-size: 13.466666666667pt;">c#.net</a>
<a href="https://toidicodedao.com/tag/c-hay-ho/" class="tag-link-319006524 tag-link-position-5" title="25 topics" style="font-size: 12.933333333333pt;">c# hay ho</a>
<a href="https://toidicodedao.com/tag/chia-se/" class="tag-link-1183836 tag-link-position-6" title="14 topics" style="font-size: 9.8666666666667pt;">chia sẻ</a>
<a href="https://toidicodedao.com/tag/code/" class="tag-link-656 tag-link-position-7" title="96 topics" style="font-size: 20.666666666667pt;">code</a>
<a href="https://toidicodedao.com/tag/coder/" class="tag-link-10095 tag-link-position-8" title="14 topics" style="font-size: 9.8666666666667pt;">coder</a>
<a href="https://toidicodedao.com/tag/coding/" class="tag-link-332 tag-link-position-9" title="26 topics" style="font-size: 13.2pt;">coding</a>
<a href="https://toidicodedao.com/tag/cong-nghe/" class="tag-link-109747 tag-link-position-10" title="11 topics" style="font-size: 8.5333333333333pt;">công nghệ</a>
<a href="https://toidicodedao.com/tag/dependency-injection/" class="tag-link-1372119 tag-link-position-11" title="11 topics" style="font-size: 8.5333333333333pt;">dependency injection</a>
<a href="https://toidicodedao.com/tag/developer/" class="tag-link-14911 tag-link-position-12" title="71 topics" style="font-size: 18.933333333333pt;">developer</a>
<a href="https://toidicodedao.com/tag/di/" class="tag-link-130881 tag-link-position-13" title="10 topics" style="font-size: 8pt;">di</a>
<a href="https://toidicodedao.com/tag/facebook/" class="tag-link-81819 tag-link-position-14" title="17 topics" style="font-size: 10.933333333333pt;">facebook</a>
<a href="https://toidicodedao.com/tag/framework/" class="tag-link-7136 tag-link-position-15" title="18 topics" style="font-size: 11.2pt;">framework</a>
<a href="https://toidicodedao.com/tag/front-end/" class="tag-link-278857 tag-link-position-16" title="14 topics" style="font-size: 9.8666666666667pt;">front-end</a>
<a href="https://toidicodedao.com/tag/front-end-developer/" class="tag-link-18478355 tag-link-position-17" title="12 topics" style="font-size: 8.9333333333333pt;">front-end developer</a>
<a href="https://toidicodedao.com/tag/hack/" class="tag-link-16981 tag-link-position-18" title="13 topics" style="font-size: 9.4666666666667pt;">hack</a>
<a href="https://toidicodedao.com/tag/hacker/" class="tag-link-6828 tag-link-position-19" title="14 topics" style="font-size: 9.8666666666667pt;">hacker</a>
<a href="https://toidicodedao.com/tag/html/" class="tag-link-647 tag-link-position-20" title="10 topics" style="font-size: 8pt;">html</a>
<a href="https://toidicodedao.com/tag/interface/" class="tag-link-6133 tag-link-position-21" title="10 topics" style="font-size: 8pt;">interface</a>
<a href="https://toidicodedao.com/tag/ioc/" class="tag-link-43229 tag-link-position-22" title="11 topics" style="font-size: 8.5333333333333pt;">ioc</a>
<a href="https://toidicodedao.com/tag/java/" class="tag-link-1017 tag-link-position-23" title="23 topics" style="font-size: 12.533333333333pt;">java</a>
<a href="https://toidicodedao.com/tag/javascript/" class="tag-link-457 tag-link-position-24" title="36 topics" style="font-size: 15.066666666667pt;">javascript</a>
<a href="https://toidicodedao.com/tag/js/" class="tag-link-21291 tag-link-position-25" title="21 topics" style="font-size: 12pt;">js</a>
<a href="https://toidicodedao.com/tag/kinh-nghiem/" class="tag-link-191470 tag-link-position-26" title="28 topics" style="font-size: 13.6pt;">kinh nghiệm</a>
<a href="https://toidicodedao.com/tag/library/" class="tag-link-2624 tag-link-position-27" title="10 topics" style="font-size: 8pt;">library</a>
<a href="https://toidicodedao.com/tag/lap-trinh/" class="tag-link-405083 tag-link-position-28" title="122 topics" style="font-size: 22pt;">lập trình</a>
<a href="https://toidicodedao.com/tag/lap-trinh-vien/" class="tag-link-11782263 tag-link-position-29" title="42 topics" style="font-size: 15.866666666667pt;">lập trình viên</a>
<a href="https://toidicodedao.com/tag/microsoft/" class="tag-link-637 tag-link-position-30" title="13 topics" style="font-size: 9.4666666666667pt;">microsoft</a>
<a href="https://toidicodedao.com/tag/mvc/" class="tag-link-36699 tag-link-position-31" title="10 topics" style="font-size: 8pt;">mvc</a>
<a href="https://toidicodedao.com/tag/nghe-nghiep/" class="tag-link-4113377 tag-link-position-32" title="15 topics" style="font-size: 10.133333333333pt;">nghề nghiệp</a>
<a href="https://toidicodedao.com/tag/nodejs/" class="tag-link-31896918 tag-link-position-33" title="11 topics" style="font-size: 8.5333333333333pt;">Nodejs</a>
<a href="https://toidicodedao.com/tag/password/" class="tag-link-37471 tag-link-position-34" title="10 topics" style="font-size: 8pt;">password</a>
<a href="https://toidicodedao.com/tag/phong-van/" class="tag-link-3001212 tag-link-position-35" title="13 topics" style="font-size: 9.4666666666667pt;">phỏng vấn</a>
<a href="https://toidicodedao.com/tag/program/" class="tag-link-9574 tag-link-position-36" title="35 topics" style="font-size: 14.933333333333pt;">program</a>
<a href="https://toidicodedao.com/tag/programmer/" class="tag-link-37549 tag-link-position-37" title="38 topics" style="font-size: 15.333333333333pt;">programmer</a>
<a href="https://toidicodedao.com/tag/programming/" class="tag-link-196 tag-link-position-38" title="59 topics" style="font-size: 17.866666666667pt;">programming</a>
<a href="https://toidicodedao.com/tag/project/" class="tag-link-1019 tag-link-position-39" title="10 topics" style="font-size: 8pt;">project</a>
<a href="https://toidicodedao.com/tag/review/" class="tag-link-1745 tag-link-position-40" title="14 topics" style="font-size: 9.8666666666667pt;">review</a>
<a href="https://toidicodedao.com/tag/review-sach/" class="tag-link-21456865 tag-link-position-41" title="14 topics" style="font-size: 9.8666666666667pt;">review sách</a>
<a href="https://toidicodedao.com/tag/security/" class="tag-link-801 tag-link-position-42" title="12 topics" style="font-size: 8.9333333333333pt;">security</a>
<a href="https://toidicodedao.com/tag/senior/" class="tag-link-6585 tag-link-position-43" title="10 topics" style="font-size: 8pt;">senior</a>
<a href="https://toidicodedao.com/tag/series/" class="tag-link-2347 tag-link-position-44" title="42 topics" style="font-size: 15.866666666667pt;">series</a>
<a href="https://toidicodedao.com/tag/solid/" class="tag-link-107226 tag-link-position-45" title="11 topics" style="font-size: 8.5333333333333pt;">solid</a>
<a href="https://toidicodedao.com/tag/sach/" class="tag-link-60746 tag-link-position-46" title="23 topics" style="font-size: 12.533333333333pt;">sách</a>
<a href="https://toidicodedao.com/tag/technical/" class="tag-link-624 tag-link-position-47" title="14 topics" style="font-size: 9.8666666666667pt;">technical</a>
<a href="https://toidicodedao.com/tag/thu-vien/" class="tag-link-614174 tag-link-position-48" title="13 topics" style="font-size: 9.4666666666667pt;">thư viện</a>
<a href="https://toidicodedao.com/tag/web/" class="tag-link-151 tag-link-position-49" title="13 topics" style="font-size: 9.4666666666667pt;">web</a>
<a href="https://toidicodedao.com/tag/dai-hoc/" class="tag-link-11213773 tag-link-position-50" title="15 topics" style="font-size: 10.133333333333pt;">đại học</a></div></aside></div><!-- #content-sidebar -->
<div id="secondary">
			<h2 class="site-description">Lập trình viên giỏi không phải chỉ biết code</h2>
	
	
		<div id="primary-sidebar" class="primary-sidebar widget-area" role="complementary">
		<aside id="blog_subscription-5" class="widget widget_blog_subscription"><h1 class="widget-title"><label for="subscribe-field">Theo dõi blog</label></h1>
				<form action="https://subscribe.wordpress.com" method="post" accept-charset="utf-8" id="subscribe-blog">
											<p>Nhập email để nhận thông báo về những bài viết hay mỗi tuần của blog nhé.</p>
<p>Join 1,357 other followers</p>
						<p><input type="text" name="email" style="width: 95%; padding: 1px 2px" placeholder="Enter your email address" value="" id="subscribe-field"></p>
					
					<p>
						<input type="hidden" name="action" value="subscribe">
						<input type="hidden" name="blog_id" value="81976675">
						<input type="hidden" name="source" value="https://toidicodedao.com/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/">
						<input type="hidden" name="sub-type" value="widget">
						<input type="hidden" name="redirect_fragment" value="blog_subscription-5">
						<input type="hidden" id="_wpnonce" name="_wpnonce" value="f241d04f78">						<input type="submit" value="Theo dõi">
					</p>
				</form>
			
</aside><aside id="text-18" class="widget widget_text">			<div class="textwidget"><a target="_blank" href="https://toidicodedao.com/?random"><img src="https://toidicodedao.files.wordpress.com/2016/05/button-3.png">
</a></div>
		</aside><aside id="nav_menu-7" class="widget widget_nav_menu"><h1 class="widget-title">Social Links</h1><div class="menu-social-link-menu-container"><ul id="menu-social-link-menu" class="menu"><li id="menu-item-796" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-796"><a href="http://conanak99.github.io/">Personal Page</a></li>
<li id="menu-item-38" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-38"><a href="http://vn.linkedin.com/in/huyhoangpham92">LinkedIn</a></li>
<li id="menu-item-36" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-36"><a href="https://github.com/conanak99">Github</a></li>
<li id="menu-item-1342" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1342"><a target="_blank" href="https://www.facebook.com/toidicodedao/">Facebook (Fan Page)</a></li>
<li id="menu-item-35" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-35"><a title="Facebook" href="https://www.facebook.com/huyhoang.pham.106">Facebook (Personal Page)</a></li>
</ul></div></aside><aside id="text-15" class="widget widget_text"><h1 class="widget-title">Online users</h1>			<div class="textwidget"><a target="_blank" href="http://whos.amung.us/stats/1ahu94645vpr/">
    <img src="https://whos.amung.us/cwidget/1ahu94645vpr/ffffff030001.png" width="81" height="29" border="0" title="Click to see how many people are online">
</a></div>
		</aside><aside id="blog-stats-5" class="widget widget_blog-stats"><h1 class="widget-title">Blog Stats</h1>		<ul>
			<li>1,597,135 lượt xem</li>
		</ul>
		</aside><aside id="text-13" class="widget widget_text"><h1 class="widget-title">Liên kết</h1>			<div class="textwidget"><a href="https://codeaholicguy.com/">Codeaholicguy</a><br>
<a href="http://azurevn.net/">AzureVN.net</a><br>
<a href="https://gramy.vn/">GramyVN</a><br>
<a href="http://vhnam.github.io/">Võ Hoài Nam Blog</a><br>
<a href="http://niviki.com/">
Niviki.com
</a><br>
<a href="https://jusfunny.wordpress.com">Jusfunny - Better Developer</a>
</div>
		</aside><aside id="archives-8" class="widget widget_archive"><h1 class="widget-title">Lưu trữ</h1>		<ul>
			<li><a href="https://toidicodedao.com/2017/02/">February 2017</a>&nbsp;(7)</li>
	<li><a href="https://toidicodedao.com/2017/01/">January 2017</a>&nbsp;(6)</li>
	<li><a href="https://toidicodedao.com/2016/12/">December 2016</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2016/11/">November 2016</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2016/10/">October 2016</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2016/09/">September 2016</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2016/08/">August 2016</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2016/07/">July 2016</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2016/06/">June 2016</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2016/05/">May 2016</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2016/04/">April 2016</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2016/03/">March 2016</a>&nbsp;(10)</li>
	<li><a href="https://toidicodedao.com/2016/02/">February 2016</a>&nbsp;(6)</li>
	<li><a href="https://toidicodedao.com/2016/01/">January 2016</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2015/12/">December 2015</a>&nbsp;(10)</li>
	<li><a href="https://toidicodedao.com/2015/11/">November 2015</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2015/10/">October 2015</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2015/09/">September 2015</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2015/08/">August 2015</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2015/07/">July 2015</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2015/06/">June 2015</a>&nbsp;(9)</li>
	<li><a href="https://toidicodedao.com/2015/05/">May 2015</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2015/04/">April 2015</a>&nbsp;(7)</li>
	<li><a href="https://toidicodedao.com/2015/03/">March 2015</a>&nbsp;(8)</li>
	<li><a href="https://toidicodedao.com/2015/02/">February 2015</a>&nbsp;(4)</li>
	<li><a href="https://toidicodedao.com/2015/01/">January 2015</a>&nbsp;(6)</li>
	<li><a href="https://toidicodedao.com/2014/12/">December 2014</a>&nbsp;(1)</li>
		</ul>
		</aside>	</div><!-- #primary-sidebar -->
	</div><!-- #secondary -->

		</div><!-- #main -->

		<footer id="colophon" class="site-footer" role="contentinfo">

			
			<div class="site-info">
								<a href="https://wordpress.com/?ref=footer_blog">Blog at WordPress.com.</a>
			</div><!-- .site-info -->
		</footer><!-- #colophon -->
	</div><!-- #page -->

	<!--  -->
<script type="text/javascript" src="//0.gravatar.com/js/gprofiles.js?ver=201709y"></script>
<script type="text/javascript">
/* <![CDATA[ */
var WPGroHo = {"my_hash":""};
/* ]]> */
</script>
<script type="text/javascript" src="https://s1.wp.com/wp-content/mu-plugins/gravatar-hovercards/wpgroho.js?m=1380573781h"></script>

	<script>
		//initialize and attach hovercards to all gravatars
		jQuery( document ).ready( function( $ ) {

			if (typeof Gravatar === "undefined"){
				return;
			}

			if ( typeof Gravatar.init !== "function" ) {
				return;
			}			

			Gravatar.profile_cb = function( hash, id ) {
				WPGroHo.syncProfileData( hash, id );
			};
			Gravatar.my_hash = WPGroHo.my_hash;
			Gravatar.init( 'body', '#wp-admin-bar-my-account' );
		});
	</script>

		<div style="display:none">
	<div class="grofile-hash-map-01fbb9415ce23ee879c1bc8c24aa1ec6">
	</div>
	<div class="grofile-hash-map-711427523360c0ffc6846f6d4386101c">
	</div>
	<div class="grofile-hash-map-de0cdb393b4fcc100d471591994a5e0b">
	</div>
	<div class="grofile-hash-map-2c5d9b226d5f454beee1b57c439787f6">
	</div>
	</div>
<script type="text/javascript">
/* <![CDATA[ */
var HighlanderComments = {"loggingInText":"Logging In\u2026","submittingText":"Posting Comment\u2026","postCommentText":"Post Comment","connectingToText":"Connecting to %s","commentingAsText":"%1$s: You are commenting using your %2$s account.","logoutText":"Log Out","loginText":"Log In","connectURL":"https:\/\/toidicodedao.wordpress.com\/public.api\/connect\/?action=request","logoutURL":"https:\/\/toidicodedao.wordpress.com\/wp-login.php?action=logout&_wpnonce=cd0a966e80","homeURL":"https:\/\/toidicodedao.com\/","postID":"3555","gravDefault":"mystery","enterACommentError":"Please enter a comment","enterEmailError":"Please enter your email address here","invalidEmailError":"Invalid email address","enterAuthorError":"Please enter your name here","gravatarFromEmail":"This picture will show whenever you leave a comment. Click to customize it.","logInToExternalAccount":"Log in to use details from one of these accounts.","change":"Change","changeAccount":"Change Account","comment_registration":"","userIsLoggedIn":"","isJetpack":"0","text_direction":"ltr"};
/* ]]> */
</script>
<script type="text/javascript" src="https://s2.wp.com/_static/??/wp-content/js/jquery/jquery.autoresize.js,/wp-content/mu-plugins/highlander-comments/script.js?m=1479964158j"></script>
			<script type="text/javascript">
			try {
				window._ttf = window._ttf || [];
				_ttf.push({
					pid          : 25030
					,lang        : "en"
				 	,format      : "inread"
					,slot        : ".teads_slot"
					,slotMode    : "in"
					,minSlot     : 1
					,css         : "margin: 10px auto; max-width: 550px;"
				});
				(function (d) {
				        var js, s = d.getElementsByTagName('script')[0];
				        js = d.createElement('script');
				        js.async = true;
				        js.src = '//cdn.teads.tv/media/format.js';
				        s.parentNode.insertBefore(js, s);
				})(window.document);
			} catch(e) {}
			</script>
	<div id="carousel-reblog-box">
		<form action="#" name="carousel-reblog">
			<textarea id="carousel-reblog-content" name="carousel-reblog-content" placeholder="Add your thoughts here... (optional)"></textarea>
			<label for="carousel-reblog-to-blog-id" id="carousel-reblog-lblogid">Post to</label>
			<select name="carousel-reblog-to-blog-id" id="carousel-reblog-to-blog-id">
						</select>

			<div class="submit">
				<span class="canceltext"><a href="#" class="cancel">Cancel</a></span>
				<input type="submit" name="carousel-reblog-submit" class="button" id="carousel-reblog-submit" value="Reblog Post">
				<input type="hidden" id="carousel-reblog-blog-id" value="81976675">
				<input type="hidden" id="carousel-reblog-blog-url" value="https://toidicodedao.com">
				<input type="hidden" id="carousel-reblog-blog-title" value="Từ coder đến developer - Tôi đi code dạo">
				<input type="hidden" id="carousel-reblog-post-url" value="">
				<input type="hidden" id="carousel-reblog-post-title" value="">
			</div>

			<input type="hidden" id="_wpnonce" name="_wpnonce" value="949c1f8eb5"><input type="hidden" name="_wp_http_referer" value="/2017/01/17/series-nhan-dien-idol-phan-3-thu-thap-du-lieu/">		</form>

		<div class="arrow"></div>
	</div>
<script type="text/javascript" charset="UTF-8" id="polldaddyRatings"><!--//--><![CDATA[//><!--
PDRTJS_settings_8005199_post_3555={"id":8005199,"unique_id":"wp-post-3555","title":"Series%20Nh%E1%BA%ADn%20di%E1%BB%87n%20Idol%3A%20Ph%E1%BA%A7n%203%20%26%238211%3B%20C%C3%B9ng%20%C4%91i%20%C4%91%C3%A0o%20d%E1%BB%AF%20li%E1%BB%87u%20VAV%20Idol","permalink":"https:\/\/toidicodedao.com\/2017\/01\/17\/series-nhan-dien-idol-phan-3-thu-thap-du-lieu\/","item_id":"_post_3555"}; if ( typeof PDRTJS_RATING !== 'undefined' ){if ( typeof PDRTJS_8005199_post_3555 == 'undefined' ){PDRTJS_8005199_post_3555 = new PDRTJS_RATING( PDRTJS_settings_8005199_post_3555 );}}
//--><!]]></script><script type="text/javascript" charset="UTF-8" src="https://polldaddy.com/js/rating/rating.js"></script>
	<script type="text/javascript">
		window.WPCOM_sharing_counts = {"https:\/\/toidicodedao.com\/2017\/01\/17\/series-nhan-dien-idol-phan-3-thu-thap-du-lieu\/":3555};
	</script>
		<script type="text/javascript">
			var windowOpen;
		jQuery(document).on( 'ready post-load', function(){
			jQuery( 'a.share-facebook' ).on( 'click', function() {
				if ( 'undefined' !== typeof windowOpen ){ // If there's another sharing window open, close it.
					windowOpen.close();
				}
				windowOpen = window.open( jQuery(this).attr( 'href' ), 'wpcomfacebook', 'menubar=1,resizable=1,width=600,height=400' );
				return false;
			});
		});
		</script>
					<div id="fb-root"></div>
			<script>(function(d, s, id) { var js, fjs = d.getElementsByTagName(s)[0]; if (d.getElementById(id)) return; js = d.createElement(s); js.id = id; js.src = '//connect.facebook.net/en_US/sdk.js#xfbml=1&appId=249643311490&version=v2.3'; fjs.parentNode.insertBefore(js, fjs); }(document, 'script', 'facebook-jssdk'));</script>
			<script>
			jQuery( document.body ).on( 'post-load', function() {
				if ( 'undefined' !== typeof FB ) {
					FB.XFBML.parse();
				}
			} );
			</script>
			<script type="text/javascript">
			jQuery( document ).ready( function() {
			    jQuery.getScript( '//platform.linkedin.com/in.js?async=true', function success() {
			        IN.init();
			    });
			});
			jQuery( document.body ).on( 'post-load', function() {
				if ( typeof IN != 'undefined' )
					IN.parse();
			});
			</script><script type="text/javascript" src="https://s1.wp.com/wp-content/mu-plugins/akismet-3.0/_inc/form.js?m=1404442431h"></script>
<link rel="stylesheet" id="all-css-0-3" href="https://s1.wp.com/wp-content/mu-plugins/carousel/jetpack-carousel.css?m=1481571546h" type="text/css" media="all">
<!--[if lte IE 8]>
<link rel='stylesheet' id='jetpack-carousel-ie8fix-css'  href='https://s1.wp.com/wp-content/mu-plugins/carousel/jetpack-carousel-ie8fix.css?m=1412618825h&#038;ver=20121024' type='text/css' media='all' />
<![endif]-->
<link rel="stylesheet" id="all-css-2-3" href="https://s2.wp.com/wp-content/mu-plugins/widgets/facebook-likebox/style.css?m=1436472654h" type="text/css" media="all">
<script type="text/javascript">
/* <![CDATA[ */
var comment_like_text = {"loading":"Loading..."};
/* ]]> */
</script>
<script type="text/javascript">
/* <![CDATA[ */
var actionbardata = {"siteID":"81976675","siteName":"T\u1eeb coder \u0111\u1ebfn developer - T\u00f4i \u0111i code d\u1ea1o","siteURL":"https:\/\/toidicodedao.com","icon":"<img alt='' src='https:\/\/secure.gravatar.com\/blavatar\/54084bfa40206518fb9e01fb53c7ccd9?s=50&d=https%3A%2F%2Fs1.wp.com%2Fi%2Flogo%2Fwpcom-gray-white.png' class='avatar avatar-50' height='50' width='50' \/>","canManageOptions":"","canCustomizeSite":"","isFollowing":"","themeSlug":"pub\/twentyfourteen","signupURL":"https:\/\/wordpress.com\/start\/","loginURL":"https:\/\/toidicodedao.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Ftoidicodedao.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F","themeURL":"https:\/\/wordpress.com\/themes\/twentyfourteen\/","xhrURL":"https:\/\/toidicodedao.com\/wp-admin\/admin-ajax.php","nonce":"1062457049","isSingular":"1","isFolded":"","isLoggedIn":"","isMobile":"","subscribeNonce":"<input type=\"hidden\" id=\"_wpnonce\" name=\"_wpnonce\" value=\"f241d04f78\" \/>","referer":"https:\/\/toidicodedao.com\/2017\/01\/17\/series-nhan-dien-idol-phan-3-thu-thap-du-lieu\/","canFollow":"1","statusMessage":"","customizeLink":"https:\/\/toidicodedao.wordpress.com\/wp-admin\/customize.php?url=https%3A%2F%2Ftoidicodedao.wordpress.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F","postID":"3555","shortlink":"http:\/\/wp.me\/p5xXSr-Vl","canEditPost":"","editLink":"https:\/\/wordpress.com\/post\/toidicodedao.com\/3555","statsLink":"https:\/\/wordpress.com\/stats\/post\/3555\/toidicodedao.com","i18n":{"view":"View site","follow":"Follow","following":"Following","edit":"Edit","login":"Log in","signup":"Sign up","customize":"Customize","report":"Report this content","themeInfo":"Get theme: Twenty Fourteen","shortlink":"Copy shortlink","copied":"Copied","followedText":"New posts from this site will now appear in your <a href=\"https:\/\/wordpress.com\/\">Reader<\/a>","foldBar":"Collapse this bar","unfoldBar":"Expand this bar","editSubs":"Manage subscriptions","viewReader":"View site in the Reader","subscribe":"Sign me up","enterEmail":"Enter your email address","followers":"Join 1,357 other followers","alreadyUser":"Already have a WordPress.com account? <a href=\"https:\/\/toidicodedao.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Ftoidicodedao.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F\">Log in now.<\/a>","stats":"Stats"}};
/* ]]> */
</script>
<script type="text/javascript">
/* <![CDATA[ */
var jetpackCarouselStrings = {"widths":[370,700,1000,1200,1400,2000],"is_logged_in":"","lang":"en","ajaxurl":"https:\/\/toidicodedao.com\/wp-admin\/admin-ajax.php","nonce":"9d7324244b","display_exif":"1","display_geo":"1","single_image_gallery":"1","single_image_gallery_media_file":"","background_color":"black","comment":"Comment","post_comment":"Post Comment","write_comment":"Write a Comment...","loading_comments":"Loading Comments...","download_original":"View full size <span class=\"photo-size\">{0}<span class=\"photo-size-times\">\u00d7<\/span>{1}<\/span>","no_comment_text":"Please be sure to submit some text with your comment.","no_comment_email":"Please provide an email address to comment.","no_comment_author":"Please provide your name to comment.","comment_post_error":"Sorry, but there was an error posting your comment. Please try again later.","comment_approved":"Your comment was approved.","comment_unapproved":"Your comment is in moderation.","camera":"Camera","aperture":"Aperture","shutter_speed":"Shutter Speed","focal_length":"Focal Length","comment_registration":"0","require_name_email":"1","login_url":"https:\/\/toidicodedao.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Ftoidicodedao.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F","blog_id":"81976675","local_comments_commenting_as":"<fieldset><label for=\"email\">Email (Required)<\/label> <input type=\"text\" name=\"email\" class=\"jp-carousel-comment-form-field jp-carousel-comment-form-text-field\" id=\"jp-carousel-comment-form-email-field\" \/><\/fieldset><fieldset><label for=\"author\">Name (Required)<\/label> <input type=\"text\" name=\"author\" class=\"jp-carousel-comment-form-field jp-carousel-comment-form-text-field\" id=\"jp-carousel-comment-form-author-field\" \/><\/fieldset><fieldset><label for=\"url\">Website<\/label> <input type=\"text\" name=\"url\" class=\"jp-carousel-comment-form-field jp-carousel-comment-form-text-field\" id=\"jp-carousel-comment-form-url-field\" \/><\/fieldset>","reblog":"Reblog","reblogged":"Reblogged","reblog_add_thoughts":"Add your thoughts here... (optional)","reblogging":"Reblogging...","post_reblog":"Post Reblog","stats_query_args":"blog=81976675&v=wpcom&tz=7&user_id=0&subd=toidicodedao","is_public":"1","reblog_enabled":""};
/* ]]> */
</script>
<script type="text/javascript">
/* <![CDATA[ */
var sharing_js_options = {"lang":"en","counts":"1"};
/* ]]> */
</script>
<script type="text/javascript" src="https://s0.wp.com/_static/??-eJyVkF1OxDAMhC9EaiFaxAviLGnqbp3NH3aypbcnBbp00aoST7Ym840dw5yUiSFjyGAFBryQwfTRWHmA3ZMvKrlyoiDg6IwC7wULTjoMDvnAbKL3VVLfkF3pHmSmhP+BboQNpGBcGW4NjMktjafwNz1P6Ks1lR7yXIVljIUzYljpsQSTKQY52EkPNVX1msFryci1U/GCzLSucNWOEr5mrAnX7t5XJP1uv9dtvTgvP6XZu+5dUHMsgg4s5qTNWW3CAZOiZDU6TQwyaaZw2mqF3vzrY/vSdW37/NTZT3/f1Gk="></script><div id="actionbar" class="actnbr-pub-twentyfourteen actnbr-has-follow actnbr-hidden"><ul><li class="actnbr-btn actnbr-hidden"> 			    	<a class="actnbr-action actnbr-actn-follow" href=""><svg class="gridicon gridicon__follow" height="24px" width="24px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M23 16v2h-3v3h-2v-3h-3v-2h3v-3h2v3h3zM20 2v9h-4v3h-3v4H4c-1.1 0-2-.9-2-2V2h18zM8 13v-1H4v1h4zm3-3H4v1h7v-1zm0-2H4v1h7V8zm7-4H4v2h14V4z"></path></g></svg><span>Follow</span></a> 			    	<div class="actnbr-popover tip tip-top-left actnbr-notice"> 			    		<div class="tip-arrow"></div> 			    		<div class="tip-inner actnbr-follow-bubble"></div> 			    	</div> 			    </li><li class="actnbr-ellipsis actnbr-hidden"> 			  <svg class="gridicon gridicon__ellipsis" height="24" width="24" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><circle cx="5" cy="12" r="2"></circle><circle cx="19" cy="12" r="2"></circle><circle cx="12" cy="12" r="2"></circle></g></svg> 			  <div class="actnbr-popover tip tip-top-left actnbr-more"> 			  	<div class="tip-arrow"></div> 			  	<div class="tip-inner"> 				  <ul> 				    <li class="actnbr-sitename actnbr-hidden"><a href="https://toidicodedao.com"><img alt="" src="https://secure.gravatar.com/blavatar/54084bfa40206518fb9e01fb53c7ccd9?s=50&amp;d=https%3A%2F%2Fs1.wp.com%2Fi%2Flogo%2Fwpcom-gray-white.png" class="avatar avatar-50" height="50" width="50"> Từ coder đến developer - Tôi đi code dạo</a></li> 				   	<li class="actnbr-folded-customize actnbr-hidden"><a href="https://toidicodedao.wordpress.com/wp-admin/customize.php?url=https%3A%2F%2Ftoidicodedao.wordpress.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F"><svg class="gridicon gridicon__customize" height="20px" width="20px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M2 6c0-1.505.78-3.08 2-4 0 .845.69 2 2 2 1.657 0 3 1.343 3 3 0 .386-.08.752-.212 1.09.74.594 1.476 1.19 2.19 1.81L8.9 11.98c-.62-.716-1.214-1.454-1.807-2.192C6.753 9.92 6.387 10 6 10c-2.21 0-4-1.79-4-4zm12.152 6.848l1.34-1.34c.607.304 1.283.492 2.008.492 2.485 0 4.5-2.015 4.5-4.5 0-.725-.188-1.4-.493-2.007L18 9l-2-2 3.507-3.507C18.9 3.188 18.225 3 17.5 3 15.015 3 13 5.015 13 7.5c0 .725.188 1.4.493 2.007L3 20l2 2 6.848-6.848c1.885 1.928 3.874 3.753 5.977 5.45l1.425 1.148 1.5-1.5-1.15-1.425c-1.695-2.103-3.52-4.092-5.448-5.977z" data-reactid=".2.1.1:0.1b.0"></path></g></svg><span>Customize<span></span></span></a></li> 				    <li class="actnbr-folded-follow actnbr-hidden"><a class="actnbr-action actnbr-actn-follow" href=""><svg class="gridicon gridicon__follow" height="24px" width="24px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M23 16v2h-3v3h-2v-3h-3v-2h3v-3h2v3h3zM20 2v9h-4v3h-3v4H4c-1.1 0-2-.9-2-2V2h18zM8 13v-1H4v1h4zm3-3H4v1h7v-1zm0-2H4v1h7V8zm7-4H4v2h14V4z"></path></g></svg><span>Follow</span></a></li> 						<li class="actnbr-signup actnbr-hidden"><a href="https://wordpress.com/start/">Sign up</a></li> 				    <li class="actnbr-login actnbr-hidden"><a href="https://toidicodedao.wordpress.com/wp-login.php?redirect_to=https%3A%2F%2Ftoidicodedao.com%2F2017%2F01%2F17%2Fseries-nhan-dien-idol-phan-3-thu-thap-du-lieu%2F">Log in</a></li> 				     				    <li class="actnbr-shortlink actnbr-hidden"><a href="http://wp.me/p5xXSr-Vl">Copy shortlink</a></li> 				    <li class="flb-report actnbr-hidden"><a href="http://en.wordpress.com/abuse/">Report this content</a></li> 				     				     				    <li class="actnbr-subs actnbr-hidden"><a href="https://subscribe.wordpress.com/">Manage subscriptions</a></li> 				    <li class="actnbr-fold actnbr-hidden"><a href="">Collapse this bar</a></li> 			      </ul> 			    </div> 		      </div> 		    </li> 	      </ul></div>
<script type="text/javascript">
// <![CDATA[
(function() {
try{
  if ( window.external &&'msIsSiteMode' in window.external) {
    if (window.external.msIsSiteMode()) {
      var jl = document.createElement('script');
      jl.type='text/javascript';
      jl.async=true;
      jl.src='/wp-content/plugins/ie-sitemode/custom-jumplist.php';
      var s = document.getElementsByTagName('script')[0];
      s.parentNode.insertBefore(jl, s);
    }
  }
}catch(e){}
})();
// ]]>
</script>	<script type="text/javascript">
	var skimlinks_pub_id = "725X584219"
	var skimlinks_sitename = "toidicodedao.wordpress.com";
	</script>
	<script type="text/javascript" defer="" src="https://s.skimresources.com/js/725X1342.skimlinks.js"></script>		<iframe src="https://widgets.wp.com/likes/master.html?ver=20170206#ver=20170206" scrolling="no" id="likes-master" name="likes-master" style="display:none;"></iframe>
		<div id="likes-other-gravatars"><div class="likes-text"><span>%d</span> bloggers like this:</div><ul class="wpl-avatars sd-like-gravatars"></ul></div>
		<script>
			var _comscore = _comscore || [];
			_comscore.push({
				c1: "2",
				c2: "7518284"
			});
			(function() {
				var s = document.createElement("script"),
					el = document.getElementsByTagName("script")[0];
				s.defer = true;
				s.src = (document.location.protocol == "https:" ? "https://sb" : "http://b") + ".scorecardresearch.com/beacon.js";
				el.parentNode.insertBefore(s, el);
			})();
		</script>
		<noscript>
			&lt;p class="robots-nocontent"&gt;&lt;img src="https://sb.scorecardresearch.com/p?c1=2&amp;c2=7518284&amp;c3=&amp;c4=&amp;c5=&amp;c6=&amp;c15=&amp;cv=2.0&amp;cj=1" alt="" style="display:none;" width="1" height="1" /&gt;&lt;/p&gt;
		</noscript><script src="//stats.wp.com/w.js?56" type="text/javascript" async="" defer=""></script>
<script type="text/javascript">
_tkq = window._tkq || [];
_stq = window._stq || [];
_tkq.push(['storeContext', {'blog_id':'81976675','blog_tz':'7','user_lang':'en','blog_lang':'en','user_id':'0'}]);
_stq.push(['view', {'blog':'81976675','v':'wpcom','tz':'7','user_id':'0','post':'3555','subd':'toidicodedao'}]);
_stq.push(['extra', {'crypt':'UE5tW3cvZGQ/JUs1UEpqTEJUUE5JaFo0OVtmenYtJnY5WnxkNjJtLlZURGQvOTgrbVouTmJ8RjRpR0tENFh3VHU/N2NWVlE9RGRkYXFiLkpHZTlpWnNUN1hqeS80M0RhZ2lKY05OcVVbeDktXWpqNkl1emROQUJCW0hWXVNKW2VXLC9jd2lfY1szcXc9alZRT1Y1UTRMZGc0eWtVVFRWWzlFWXNKK3RUbDFBcDVpLVkmcklvZXFqdk1zbmFWVFJCa25URVg4Vl00TnBPanFSeSZxfGlnTUZ5cVpMZW1WMXBzMVMrLyVKXTguQ3wlRnU1bGVPV2lWSC0vdVozWlluLVhjN3AwVlA3R3RGZFN1JlpOemZTUzk='}]);
_stq.push([ 'clickTrackerInit', '81976675', '3555' ]);
	</script>
<noscript>&lt;img src="https://pixel.wp.com/b.gif?v=noscript" style="height:0px;width:0px;overflow:hidden" alt="" /&gt;</noscript>
<script>
if ( 'object' === typeof wpcom_mobile_user_agent_info ) {

	wpcom_mobile_user_agent_info.init();
	var mobileStatsQueryString = "";
	
	if( false !== wpcom_mobile_user_agent_info.matchedPlatformName )
		mobileStatsQueryString += "&x_" + 'mobile_platforms' + '=' + wpcom_mobile_user_agent_info.matchedPlatformName;
	
	if( false !== wpcom_mobile_user_agent_info.matchedUserAgentName )
		mobileStatsQueryString += "&x_" + 'mobile_devices' + '=' + wpcom_mobile_user_agent_info.matchedUserAgentName;
	
	if( wpcom_mobile_user_agent_info.isIPad() )
		mobileStatsQueryString += "&x_" + 'ipad_views' + '=' + 'views';

	if( "" != mobileStatsQueryString ) {
		new Image().src = document.location.protocol + '//pixel.wp.com/g.gif?v=wpcom-no-pv' + mobileStatsQueryString + '&baba=' + Math.random();
	}
	
}
</script>
<div class="comment-likes-overlay" style="display: none;"></div><img src="https://pixel.wp.com/g.gif?blog=81976675&amp;v=wpcom&amp;tz=7&amp;user_id=0&amp;post=3555&amp;subd=toidicodedao&amp;host=toidicodedao.com&amp;ref=https%3A%2F%2Ftoidicodedao.com%2Ftag%2Fseries-nhan-dien-idol%2F&amp;rand=0.7107308930880698" alt=":)" id="wpstats"><iframe height="0" width="0" name="automattic-passback-receiver" src="//s.pubmine.com/passback.html#https://toidicodedao.com" style="position: absolute; left: -1000px; top: -1000px; border: 0px solid; width: 0px; height: 0px;"></iframe><iframe scrolling="no" frameborder="0" src="https://sync.teads.tv/iframe?pid=25030&amp;userId=dc96bdf3-58a3-4910-8841-ec75c0813284&amp;1488340413925" style="margin: 0px; padding: 0px; width: 0px; height: 0px; border: 0px; overflow: hidden; display: none;"></iframe><div class="corom-element" style="position: absolute; top: 0px; left: 0px; right: 0px; height: 0px; margin: 0px; text-align: left; z-index: 2147483647; pointer-events: none; border: none;"></div></body>
