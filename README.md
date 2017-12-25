# Th-c-H-nh-Web
14/12/2017

Ctrt+g : group nhóm 

Chuột phải smart object rùi quăng qua 

Tạo 1 pattem

Sau khi tô xong, nhấn Ctrl + A hoặc vào Selection > Select all để chọn tất cả. Vào menu Edit > Define pattern. Trong cửa sổ mới hiện ra, đặt tên cho pattern vừa tạo.

Cắt hinh
M rùi edit -> copy merged

Thêm hinh
 chọn Image -> Image Size hoặc dùng tổ hợp phím tắt Ctrl + Alt + I.
 
Copy hình và lấy size hình
M rùi Ctrl + Shift + C

Thay đổi kích thước hình
M rùi Ctrl + Alt + C

Tắt mở đường thước rule
Ctrl + :

Tắt mở ổ vuông 
Ctrl + “

Đổi màu background
G

Tham khảo code bootstrap
http://getbootstrap.com/2.3.2/ 

Khung sườn

<div class="hero-unit">
			<div class="container">
				<div class="navbar">//chuyển khung nằm ngang
					<div class="navbar-inner">
						<nav class="pull-right ">
							<ul class="nav">
								<li class="active"><a href="#">Home</a></li>
								<li><a href="#">About Us</a></li>
								<li><a href="#">Services</a></li>
								<li><a href="#">Blog</a></li>
								<li><a href="#">Contact Us</a></li>
							</ul>
						</nav>
					</div>
				</div>	
			</div>
		</div>
		
		
		
15/12/2017


Code

Chỉnh font chữ cho những hinh

@font-face

{

	font-family:'Museo';
	src: url('bootstrap/js/exljbris - Museo-700.otf') format('truetype');
}

h1,h2,h3,h4,h5,h6
{

	font-family:'Museo', Rockwell,Serif;
}


a

{

	color:#fb2f3a;// màu chữ
}

a:hover, a:focus

{

	color:#eb2f39;	
	
	text-decoration:none;   
	
	border-bottom:1px solid;
	
}


Button

.btn

{

        -webkit-border-radius:3px;
	
	-moz-border-radius:3px;
	
	border-radius:3px;   //kích thước
	
	background:#9a9c9f; // màu nền
	
	font-size:12px; cở chữ
	
	font-weight:bold; chữ đậm
	
	color:#fff; màu chữ
	
	text-shadow:none; // bóng chữ
	
	box-shadow:inset 0 1px 0 rgba(255,255,255,0.2); bóng khung
	
	border:1px solid rgba(0,0,0,0.2); khung giữa bao ngoài chữ
	
}

.btn:hover, .btn:focus

{

	background:#8e9093; // nền xám
	
	color:#fff; chữ trăng
	
	border:1px solid rgba(0,0,0,0.2);khung giữa
	
	margin-top:30px;

}

.heading

{

	margin-bottom:20px;	// h4
	
}

Navbar

.hero-unit khung đầu

{

	padding:0px; 	
	
	background: #222  url(bootstrap/img/hero-unit.jpg) no-repeat 50% top ; chèn hình
	//#222  những khoảng trắng 2 bên sẽ được tô đen
	
	border-radius:0;
	
	margin-bottom:0;// khoảng cách dưới 0
	
} 
 
.navbar-inner // khung 

{

	//(padding : 40px 0; khung cách đầu web 1 khoảng)
	
	background:transparent; //trong suốt
	
	border:none; // ko hộp
	
	box-shadow:none;//ko có bóng
	
}

.navbar

{
	margin-top: 30px;//cách top 1 khoảng

	border-bottom:1px solid rgba(255,255,255,0.2) tạo đường kẻ ngang màu xám
	
}

.navbar .brand // dipped

{

	text-indent:-9999px;
	
	width:127px; //độ dài
	
	height:50px;//chiều cao
	
	background:url(bootstrap/img/bracd.png) no-repeat; đường dẫn hình ko lập 
	
}

.navbar .nav

 {
 
	padding:0; canh chỉnh vị trí
	
	margin:0;
	
}

.navbar .nav > li > a // đinh dạng kiểu chử Home About Us ....

{

	font-weight:bold;//chữ đậm
	
	font-size:14px;// cở chữ
	
	text-shadow:none;// chữ ko có bóng
	
	color:#ffff; màu chữ màu trắng
	
	padding:3px 10px ; /khung cho chữ 
	
}

.navbar .nav > li > a:focus, .navbar .nav > li > a:hover

{

	color:rgba(255,255,255,0.7);// trỏ chuột sẽ chuyển màu màu xám
	
}

.navbar .nav > .active > a, .navbar .nav > .active > a:hover, .navbar .nav > .active > a:focus

{

	box-shadow:none; //khung ko có bóng
	
	background:rgba(0,0,0,0.7);//đổ màu nút Home khung màu đen
	
}

Hero-unit-inner

.hero-unit-inner h1

{	

	margin-top:50px;//khoảng cách trên

	margin-bottom:20px; //khoảng cách dưới
	
	font-size:48px;//cở chữ
	
	color:#fff;	//màu chữ
	
	text-shadow: 0 1px 0 //tạo bong  rgba(0,0,0,0.3) hiển thị độ bóng ;
	
}

.hero-unit-inner h4

{

	color:#cccccc;	chữ màu xám
	
	text-shadow: 0 1px 0 rgba(0,0,0,0.3); tạo bóng cho chữ
	
	margin-bottom:20px;// khoảng cách dưới
	
}

.hero-unit-inner  a

{

	margin-left:10px ;  // khoảng cách giữa 2 chữ
	
	color : #fff;	//màu chữ sám
	
	border-bottom:1px solid #ddd;  độ lớn cho đường viền dưới và màu cho chữ LearnMore
	
}

.hero-unit-inner img

{

	margin-top:30px;	khoảng cách từ botton tới hình
	
}

.hero-unit-inner .btn-primary

{

	background:#fb2f3a; màu nút
	
	border:none; đường viền 0
	
	box-shadow:0 2px 1px rgba(0,0,0,0.3); bóng
	
	font-size:16px; cở chữ
	
	font-weight:bold; kiểu đậm
	
	text-shadow:none; bóng chữ
	
}

18/12/2017

Process

#process
{

	background:#eeeeee;// màu nền xám
	border-bottom:#dddddd;//đường viền dưới xám nhạt
	border-top: 1px solid #fff;
	box-shadow:0 -3px 5px rgba(0,0,0,0.3);
	position:relative;r
	z-index:10; tạo đường bóng dưới nền
	padding : 60px 0; // chỉnh khoảng không trên và dưới , trái phải ko tăng

}

.h-line
{

	max-height:5px; độ dài tối đa
	background: url(bootstrap/img/line.jpg) repeat-x; hình nền
	-webkit-border-radius:3px; 
	-moz-border-radius:3px;   
	border-radius:3px;       tạo đường tròn phía đầu đường thẳng
	position:relative;
	top:50px;
	z-index:-1;
}
.process-icon
{

	margin-bottom:15px;// mở rộng khoảng không của icon
	display:inline-block;  //hiển thị 1 khối
	width:100px; // chiều rộng
	height:101px;	//chiều cao
	background:transparent url(bootstrap/img/process.png); hình nền
	background-position: left top; vị trí hình  đầu
	
}
.process-icon.idesign
{

	background-position:-100px top; // vi trí hình 2 
}
.process-icon.idevelop
{

	background-position:-200px top; // vi trí hình 3
}
.process-icon.ilaunch
{

	background-position:-300px top; // vi trí hình 4
}
Portfolio

#portfolio
{

	padding: 60px 0;	 // khoảng cách trên dưới
}
.title
{

	margin-bottom:0; // canh chỉnh dưới
}
.category
{

	font-size:12px;  cở chữ 12
	color:#999999; màu chữ	
}

Partners


19/12/2017


#partners
{

	padding:60px 0; kích cở 	
	border-bottom:1px solid #ddd; tạo đường viền phía dưới Partner
}

Widgets

#widgets

{

	padding: 50px 0 60px 0;  // kích thước của widget
	border-bottom:1px solid #ddd;  đường viền				
}
.testimonials blockquote

{

	overflow:hidden;	//text bị tràng sẽ bị dấu đi
}
.testimonials blockquote p

{

	font-family: Grergia , Serif; // định dạnh kiêu chữ trong P
	font-style:italic; chữ in nghiêng
}
.testimonials blockquote cite

{

	color:#333; màu cho chữ trong cite
}
.blog-lists
{

	list-style:none;
	padding:0;
	margin:0;
}
.blog-lists li, .tweet-lists li

{

	border-bottom:1px solid #ddd; // đường viền
	padding: 20px 0;
}
.blog-lists li :first-child, .tweet-lists li :first-child
{

	padding-top:0;
}
.blog-lists li :last-child, .tweet-lists li :last-child

{

	border-bottom:0;
}
.blog-lists h5
{
	
	padding:0;
	margin:0;
}
.blog-lists h5 a 
{

	color:#333;// màu đen
}
.blog-lists h5 a:hover
{

	color:#444;
}
.tweet-lists
{

	list-style:none;
	padding:0;
	margin:0;
}
.tweet-lists li img
{

	margin-right:20px; canh chỉnh hình cách bên phải 20px
}

Footer

Footer
{

	padding:60px 0;
}
.table
{	

	display: table;canh chỉnh giữa trang
	
	margin: 0 auto;
}
.footer-links li
{

	float:left;
	margin-right: 40px;
}
.footer-links li a
{

	color:#666666;
	font-size:12px;
}	
.footer-links
{

	list-style: none; 
  	display: inline-block; chuyển chữ sang giữa
}
} 
social
#social
{

	clear : both;	
	margin-bottom:40px;
}
.twitter
{

	background:#568ccc;
	margin-left:5px;	
}
.twitter:hover , .twitter:focus
{

	background:#4f91bf;	
}
.facebook
{

	background:#2272a9;	
}
.facebook:hover , .facebook:focus
{

	background:#20699c;	
}
.social-spirte
{

	width:16px;
	height:16px; 
	display: inline-block;
	background:transparent url(bootstrap/img/thumbnail/Social-sprite.png) no-repeat; // gắn hình nền
	background-position:left top; vị trí hình	
}
.social-spirte.facebook
{

	background-position:-16px top;	hình 2
}

21/12/2017

Code a Responsive Website Using HTML5 and CSS3
Khung sườn

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title> HTML5/CSS3 Responsive Theme</title>
	
	<link rel="stylesheet" type="text/css" href="style.css">
	<<meta name="viewport" content="width=device-width , initial-scale=1.0">
</head>

<body class="body">
		
	<header  class="mainheader">
		<img src="img/logo.gif">
		
		<nav>
			<ul>
			<li class="active"><a href="#">Home</a></li>	
			<li><a href="#">About</a></li>	
			<li><a href="#">Portfolio</a></li>	
			<li><a href="#">Contact</a></li>	
			</ul>
			
		</nav>

	</header><!-- /header -->	
	<div class="mainContent">
		<div class="content">
			<article class="topcontent">
				<header>
					<h2><a href="#" title="Fist port"> Fist port</a></h2>
				</header>
				<footer>
					<p class="port-info">This port is written by Christan</p>	
				</footer>
				<content>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
				</content>
			</article>
		</div>
	</div>
	<aside class="top-sidebar">
		<article>
			<h2>Top sidebar</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
		</article>
	</aside>

	<aside class="middle-sidebar">
		<article>
			<h2>Middle sidebar</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
		</article>
	</aside>

	<aside class="bottom-sidebar">
		<article>
			<h2>Bottom sidebar</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
		</article>
	</aside>

	<footer class="mainFooter">
		<p>Copyright &copy ; <a href="#" title="1stwebdesigner"> </a>1stwebdesigner.com</p>
		
	</footer>
</body>

</html>

Style
Body
{

	background-image:url('img/bg.png'); //hình nền
	color:#000305; màu nền
	font-size:87.5% ;/* Base font size 14px*/ cở chữ
	font-family: Asenal,'Lucida San Unicode'; kiểu chữ
	line-height: 1.5;
	text-align:left;  canh lề trái
}
.body
{
	
	margin:0 auto;  canh chỉnh
	width:70%;	độ dài
	clear:both; trái phải của web ko đc float
	
}
a
{

	text-decoration:none;
}
a:link,a:visited

{

	color:#CF5C3F; // chữ first và second thành màu đỏ
	
}
a:hover,a:active

{

	background-color:#CF5C3F;  nền đỏ
	color:#fff; chữ trắng khi trỏ chuột vào
	
}
.mainheader img canh chỉnh hình

{

	width:30%; độ dài 		
	height:auto;
	margin:2% 0; khoảng cách trên dưới
	
}
.mainheader nav khung

{

	background-color:#666; màu khung
	height:40px;	 độ cao khung
 	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px;   2 đầu khung
	
}
.mainheader nav ul 

{

	list-style:none; bỏ dấu chấm
	margin:0 auto; canh chỉnh
	
}
.mainheader nav ul li trong khung

{

	float: left; hiển thị bên trái 
	display: inline; 
	
}
.mainheader nav a:link, .mainheader nav a:visited

{

	color:#fff; chữ màu trắng
	display:inline-block;  hiển thị bên trong khung
	padding: 10px 25px; khoảng cách mỗi chữ 
	height: 20px; độ cao
	
}
.mainheader nav a:hover, .mainheader nav a:active,.mainheader nav .active a:link chữ home, .mainheader nav .active a:visited

{

	background-color:#CF5C3F;
	text-shadow:none;
	
}
.mainheader nav ul li a tạo viền khung cong 4 góc

{

	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	
}
.mainContent

{

	line-height:25px;độ cao của chữ
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	
}
.content

{

	width:70%;  độ dài 
	float:left;
	
}
.topcontent khung chữ

{

	background-color:#fff; màu nền 
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	padding: 3% 5%; khoảng cách khung
	margin-top:2% canh chỉnh khung
	
}
.bottomcontent

{

	background-color:#fff;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	
}
.top-sidebar

{

	width:21%;
	float:left; 
	background-color:#fff; nền trắng
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	margin: 1% 0 2% 3%; cách lề top 1  dưới 2 trái 3 phải 0
	padding: 2% 3%;  tăng khoảng không trên dưới 2 trái phải 3%
	
}
.port-info

{

	font-size:85%; cở chữ
	color:#999; màu chữ 
	font-style:italic; in nghiêng
	
}
.middle-sidebar

{

	width:21%;
	float:left;
	background-color:#fff;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	margin-left:3%;
	margin-bottom:2%;
	padding: 2% 3%;
	
}

.bottom-sidebar

{

	width:21%;
	float:left;
	background-color:#fff;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	margin-left:3%;
	margin-bottom:2%; 
	padding: 2% 3%;
	
}
.mainFooter

{

	width:100%;
	height:40px;
	float:left;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	background-color:#666;
	margin-top:2% 0; 
	
}
.mainFooter p

{

	width:92%;
	margin:1% auto; canh chỉnh
	color:#fff; màu chữ
	
}

Canh chỉnh khi thu nhỏ

@media only screen and (min-width: 150px) and (max-width: 600px)  

{

	.body   canh giữa 
	{
	width:90%;
	font-size:95%;
	}
	.mainheader img canh hình
	{
		width:100%; độ lớn full
	}
	.mainheader nav
	{
		height:160px; khung của các nút Home .... cao
	}
	.mainheader nav ul
	{
		padding-left:0;  khoảng không bên trái 0;
	}
	.mainheader nav ul li
	{
		width: 100%;	 độ rộng 100%
		text-align:center; canh chỉnh chữ ở giữa hàng dọc
	}
	.mainheader nav a:link, .mainheader nav a:visited nền chữ home ...
	{
	
		padding:10px 25px;	 thêm khoảng không 2 trên dưới và 2 bên trái phải
		height:20px; 
		display:block; phủ đầy khung theo tững hàng
	}

	.content
	{
		width:100%;
		float:left;
		margin-top:2%; canh chỉnh chữ cách khung chọn
	}
	.port-info
	{
		display:none; ẩn dòng chữ trong port-info
	}
	.topcontent
	{
		background-color:#fff;
		-webkit-border-radius:5px;
		-moz-border-radius:5px;
		border-radius:5px; 
		padding: 3% 5%;
		margin-top:2%;
		margin-bottom:4%;
	}
	.bottomcontent
	{
		margin-top:3%;
	}
	.top-sidebar,.middle-sidebar,.bottom-sidebar
	{
		width:94%;
		margin: 1% 0 2% 0%;
		padding: 2% 3%;
		
	}

}
23/12/2017

Design an Agency Landing Page in Photoshop

Step 1: Setting up the Document
_ Bắt đầu bằng cách tạo một tài liệu 1400px x 1820px trong Photoshop.
_ Công cụ Ruler là rất hữu ích cho hướng dẫn này đảm bảo rằng các thước đo và hướng dẫn được bật.
•	Rulers: Ctrl + R
•	Guides: Ctrl + ;
_Một điều quan trọng cần lưu ý khi sử dụng Ruler Tool là Info(Information) Panel(f8).
_Tổng chiều rộng của trang này sẽ là 960px. Vì vậy, hãy tạo guide đầu tiên bằng cách View – New Guide, đặt giá trị là 220px.
_Tạo guide  khác nhưng bây giờ thay đổi giá trị thành 1180px, điều này sẽ làm tổng cộng 960px ở giữa web
Step 2: Working on the Header:
_ Tiêu đề của chúng ta sẽ chứa: a logo, call to action, navigation, search.

Step 2.1: 
_Sữ dụng Rectangle Tool(U) with a fill color of #4d9543, create a dài 1400px  by cao 10px shape and place it on the very top of the canvas.

Step 2.2:
_ Đây là một biểu trưng cá nhân mà tôi sẽ sử dụng trong hướng dẫn này. Đối với văn bản Burnstudio,  sử dụng Myriad Pro 30pt, màu # 4d9543 và # 4a4a4a. Bạn có thể tạo thương hiệu riêng bằng cách sử dụng các cài đặt phông chữ này.

_Một khi bạn đã hoàn thành nó, đặt logo 40px dưới hình dạng màu xanh lá cây.
  W : crtl+c crtl+v  
  
Step 2.3:
_Mặt khác chúng ta hãy thêm  call to action. sử dụng Font là Kozuka Gothic Pro, 24pt. Nếu bạn không có phông chữ này cố gắng sử dụng Helvetica Thin / Light. Màu sắc sẽ là # 333333 và # 4d9543.

Bây giờ, thêm số của bạn và Gọi cho chúng tôi bây giờ văn bản bằng cách sử dụng Công cụ Văn bản (T).

Tôi cũng thêm 1px # c8c8c8 dòng rắn 20px từ phía bên phải của văn bản. Bạn muốn căn chỉnh nó với logo.

Step 2.4
_ Tiếp theo, chúng ta sẽ tạo ra  navigation. Chọn công cụ Rectangle   (U) và set the Radius là 30px. Bây giờ, tạo một shape 960px x 50px với màu điền # 4d9543. Đặt nó dưới logo 40px.
 

Step 2.5:
_Apply these Blending Options: for 	
 
 
 
Step 2.6:

_Đầu tiên, bạn cần phải thêm the home icon, followed by the links.Font sử dụng là Helvetica Light, 15pt. Using Text Tool(T) add the following links. Lưu ý rằng mỗi liên kết có khoảng cách 30px từ thanh chia, vì vậy hãy đo nó bằng Công cụ Ruler (I).


Step 2.7:
 
Step 2.8:
_Tạo the search bar , tạo a 225px by 30px shape using Rounded Rectangle Tool(U) màu tô màu # 4b9241, đặt nó ở bên trái 55px , Add the (search) text using Text Tool(T), font is Helvetica 14pt, Sau đó, đặt hình  Biểu tượng Search 20px ở bên trái.
Step 2.9:

 
   
 
Step 3: Working on Slider

Step 3.1

_The slider part  cao 300px và nằm dưới điều hướng 40px, vì vậy hãy tiếp tục và đo nó bằng Công cụ Ruler (I).

Step 3.2:
_Chọn công cụ Rectangle tròn (U) và tạo hình dạng giống như thể hiện trong hình bên dưới. Tạo một hình dạng 550px x 250px và tùy chỉnh góc dưới bên phải giống như trong ảnh chụp màn hình dưới đây bằng cách sử dụng Công cụ Hướng (A).

Step 3.3:
_Sử dụng công cụ Ellipse Tool (U) tạo hình dạng 160px x 160px. Đổ màu cho màu này không quan trọng bởi vì chúng tôi sẽ che mặt một hình ảnh ở trên nó sau. Đặt hình dạng này ở giữa góc dưới cùng bên phải.
 
Step 3.4:
_Tạo một hình dạng khác bằng cách sử dụng cùng một công cụ. Đảm bảo màu tô là # 000000 và thay đổi độ mờ xuống 80%. Với mục đích trình bày tôi đã làm cho nó một màu xanh lá cây để bạn có thể nhìn thấy hình dạng sẽ trông như thế nào. Kích thước hình là 575px x 88px.

Step 3.5:
_Chúng ta sẽ thêm the slider controls. Sử dụng công cụ Ellipse Tool (U) tạo 3  hình dạng  13 x 13px màu trạng thái bình thường sẽ là 	 và   active là # 4e9643. Đặt nó như thể hiện trong ảnh chụp màn hình dưới đây.
 
 
Step 3.6:

_Tiếp theo là nút trước đó và tiếp theo. Tôi tạo ra này bằng cách sử dụng Công cụ Bút chì (B). Màu trạng thái bình thường sẽ là # 4f4c4d và cho màu hoạt động cùng màu xanh lá cây. Đặt cái này như thể hiện trong hình bên dưới.

Step 3.7:

_Bây giờ chúng ta có tất cả các hình dạng với nhau, hãy điền nó với văn bản và thêm một hình ảnh. Tất cả bạn cần làm là tạo một lớp mới phía trên hình dạng và đặt hình ảnh của bạn ở đó, sau đó nhấp chuột phải và nhấp vào Tạo
Clipping Mask. Làm tương tự trên hình elip. Tôi sẽ để nó cho bạn những gì bạn sử dụng hình ảnh

Step 3.8:
_Tiếp theo chúng ta hãy thêm văn bản. Đối với tiêu đề tiêu đề tôi đã sử dụng cùng một phông chữ như phần gọi hành động, sau đó đối với đoạn tôi sử dụng Helvetica 13pt, # 555555 và để đọc thêm tôi đã thực hiện Italic và sử dụng cùng một màu xanh lá cây và thêm một mũi tên bằng cách sử dụng Công cụ Bút chì ( B) bên cạnh nó.
Step 4: Working on Services Area

Step 4.1:
_The service area sẽ cao hơn 240px và ở dưới thanh trượt 40px, vì vậy hãy tiếp tục và đo nó với Ruler Tool(I).

Step 4.2:
_Sử dụng công cụ Rectangle Rounded (U) với màu điền # f9f9f9 tạo một hình dạng như thể hiện trong ảnh chụp màn hình dưới đây.  

 
Step 4.3:
_Chúng tôi sẽ chia hình dạng thành hai để chúng tôi có thể sắp xếp đúng các khối dịch vụ của chúng tôi. 960/2 là 480px, vì vậy hãy tiếp tục và đo nó bằng Công cụ Ruler (I).

_Thêm văn bản và biểu tượng sau đây như hình bên dưới. Lưu ý rằng kích thước và màu sắc của văn bản đều giống nhau nên hãy sao chép một số phần tử như chúng tôi đã làm trước đây. Ngoài ra khoảng cách từ hình trái và trên là 30px.
Step 4.4:

_Thêm bóng vào phần dưới cùng là rất đơn giản. Tất cả những gì bạn cần làm là sao chép hình dạng cơ bản và làm cho màu điền # 000000, đặt nó dưới lớp hình dạng ban đầu. Tiếp theo, vào Filter - Blur - Gaussian Blur đến 7.0, tạo một mặt nạ trên layer và chải lên phần mà chúng ta không nee

Step 5: Working on Media Section
This part will be divided into 3 sections Video, Twitter & Facebook.

Step 5.1:
_Chúng ta sẽ làm việc đầu tiên trên phần Video. Video sẽ chiếm 305px theo 220px và cùng khoảng cách từ trên. Đi tiếp và đo nó bằng công cụ Ruler (I).

Step 5.2:
_Sữ dụng ông cụ Rectangle Hình tròn (U) tạo một hình dạng 300px x 150px như thể hiện trong hình chụp dưới cùng với màu xanh lục giống nhau.
 

Step 5.3:

Tiếp theo chúng ta hãy tạo một nút phát. Sử dụng công cụ Ellipse Tool (U) tạo một hình dạng 45px x 45px với màu điền # f5f5f5.
ta cũng đã thêm một biểu tượng phát tôi đã tạo bằng Pencil Tool(B) có cùng màu xanh lá cây.

Step 5.4:
Thêm một số văn bản với cùng một phông chữ, kích thước sẽ là 18pt và 14pt. Cuối cùng, thêm biểu tượng không khí macbook và đặt nó như thể hiện trong ảnh chụp màn hình bên dưới.

Step 5.5:
Bây giờ hãy thiết kế nguồn cấp dữ liệu Twitter. Chọn công cụ Rectangle tròn (U) thay đổi Radius đến 20px. Tạo một hình dạng 105px có chiều rộng, chiều cao không quan trọng. Bây giờ hãy điều chỉnh hình dạng bằng công cụ Pen Tool (P) và Direct Selection Tool (A) và tạo một hình dạng như hình bên dưới.

Step 5.6:
Trên bảng điều chế lớp, làm cho màu điền hình thành 0% và áp dụng nét bên trong 1px solid # c8c8c8.

Step 5.7:
Bây giờ chúng ta hãy thêm văn bản và biểu tượng Twitter. Đặt nó như thể hiện trong hình dưới đây. Kích thước phông chữ là 18pt, đoạn 13pt và màu liên kết và màu giờ là # 6767c9, # 999999.

Step 5.8:
Đối với widget Facebook không có gì đặc biệt tôi chỉ chụp một màn hình trong trang widget.

Step 6: Working on Links, Blog, Location Section

Step 6.1:
_The footer  sẽ là 100px theo khoảng cách 320px và cách mặt tiền 50px, do đó hãy tiếp tục và đo nó bằng Công cụ Ruler (I). Sau đó, Điền toàn bộ không gian bằng Công cụ Hình Chữ nhật (U) với màu # 333333.
 
Step 6.2:
_Hãy tạo một mẫu chấm để áp dụng trong hình dạng. Tạo một tài liệu trong suốt 5px x 5px và tạo một dấu chấm ở phần dưới cùng bên trái của khung vẽ như thể hiện trong ảnh chụp màn hình dưới đây. Vào Edit - Define Pattern và áp dụng vào hình dạng với độ mờ 30%.

Step 6.3:
_Bây giờ chúng ta hãy làm việc trên các phần liên kết, tổng chiều rộng cho việc này sẽ là 225px. Tôi đã sử dụng cùng kiểu phông chữ và kích thước, các liên kết có khoảng cách 25px từ mỗi khác. _Khoảng cách của tiêu đề từ phía trên là 50px và 30px dưới đây. Ngoài ra, tôi tạo một mũi tên bằng cách sử dụng Pencil Tool(U)) và thêm nó bên cạnh các liên kết.

Step 6.4:
_Tạo một hình dạng 225px x 29px với màu điền # 000000, hạ thấp màu tô xuống 20%. Đặt nó như thể hiện trong ảnh chụp màn hình dưới đây.

Step 6.5:
_Bây giờ chúng ta hãy tiếp tục vào phần blog. Sử dụng công cụ Rectangle Rounded (U) tạo một hình dạng 292px x 58px như thể hiện trong hình bên dưới. Điền màu sắc sẽ là #ffffff và giảm opacity xuống 10%. Khoảng cách từ phần liên kết là 77px.

Step 6.6:
_Thêm biểu tượng và điền nó với văn bản bằng công cụ Text Tool (T). Đối với màu ngày #cccccc và cho liên kết là #ffffff.

Step 6.7:
_Đối với vị trí chỉ sao chép tiêu đề và thay đổi văn bản thành (Vị trí của chúng tôi). Thêm biểu tượng Bản đồ. Tôi đã tùy chỉnh bản đồ để hiển thị vị trí chính xác của tôi vì vậy hãy thoải mái tùy chỉnh bản đồ của bạn. Đối với màu văn bản sẽ là #cccccc và cho dòng # 484848

Step 7: Working on Footer

phần này rất đơn giản chỉ cần lấy một số Icons mẫu và desaturate nó bằng cách vào Image - Điều chỉnh - Desaturate hoặc bằng cách nhấn Ctrl + Shift + U. Phần này sẽ mất 145px chiều cao, do đó các biểu tượng phù hợp và chắc chắn nó là trung tâm. Điều cuối cùng là thêm 1px # c8c8c8 bên dưới và chúng tôi đã hoàn tất.

Step 7.1:
Kích thước văn bản 12pt, màu sắc đoạn # 666666, khoảng cách từ trên 30px, khoảng cách từ văn bản 15px.

Step 7.2:
Kích thước văn bản 12pt, màu liên kết # 666666, 2px # c8c8c8 đường viền dưới cùng

Step 7.3:
Đối với nút quay lại đầu trang. Tôi tạo nó bằng công cụ Ellipse Tool (U), 30px x 30px. Tôi áp dụng đột qu 1 trong 1px #bdbdbd và tạo một mũi tên đối mặt với đầu bằng  Pencil Tool(B).

25/12/2017

Convert the Agency PSD into HTML
Chúng ta sẽ viết mã này từ đầu và cuối cùng bạn sẽ có một bố cục cơ quan tuyệt vời và đầy đủ chức năng.

Tài nguyên bạn sẽ cần Mã Website này:

PSD Tải về
SlidesJS
Công cụ CSS: Đặt lại CSS

Step 1: Preparation for the PSD to HTML Tutorial

Chúng ta đều biết rằng trong việc chuyển đổi PSD sang HTML / CSS, chúng ta cần phải đi qua lại trong Photoshop (hoặc công cụ chỉnh sửa hình ảnh khác) để đo kích thước, khoảng cách và màu sắc. Vì vậy hãy đảm bảo bạn mở tệp PSD trong Adobe Photoshop.

Tất nhiên bạn sẽ cần trình soạn thảo mã yêu thích và các công cụ gỡ lỗi. Tôi đã sử dụng Intype làm trình soạn thảo văn bản của tôi và để gỡ lỗi các công cụ tôi khuyên bạn nên Web Developer Toolbar và Firebug.

Điều quan trọng là phải kiểm tra mã bằng cách sử dụng các trình duyệt khác nhau theo từng bước để chúng tôi có thể theo dõi mã của chúng tôi. Tôi đã sử dụng các kiểu CSS3 trong hướng dẫn này, mà nên hoạt động trong Chrome và Firefox. Đối với IE6 tin tưởng tôi, nó vẫn có vẻ tốt.
Step 2: Getting Files Ready
 
Bạn sẽ cần phải tạo một thư mục thư mục và bên trong của nó, bạn nên có / thư mục hình ảnh cho hình ảnh và thư mục js cho JavaScript. Tôi đã đặt tệp CSS vào thư mục gốc bao gồm tệp HTML. Ngoài ra chúng ta cần phải xuất khẩu các hình ảnh sẽ được sử dụng trong tập tin PSD. Ví dụ Biểu tượng, bạn sẽ cần phải chọn lớp từ bảng điều khiển lớp, sao chép và dán nó vào một tài liệu khác và CTRL + ALT + SHIFT + S để tiết kiệm cho web và thiết bị, loại tệp tin thích hợp cho biểu trưng nên là .png. Nhưng nếu bạn cảm thấy mệt mỏi khi làm việc này, bạn chỉ có thể tải xuống các tệp và sử dụng các hình ảnh tôi đã xuất.

Step 3: Simple Starter Layout

Để xây dựng bố cục HTML của chúng tôi, trước tiên chúng ta nên phân tích thiết kế của chúng tôi bằng cách nhìn vào bố cục của Photoshop và xác định các phần độc đáo.

Background:

 nền là màu trắng.
Header:

 Lưu ý rằng trong phần này tiêu đề có một đường màu xanh lá cây ở trên cùng bao gồm toàn bộ màn hình, do đó, để làm điều này, chúng ta cần phải quấn header với một container khác.
The header contains logo, call to action, navigation and search.
Slides:
 the slider sẽ sử dụng SlideJS.
Service:
this section chứa 2 cột web design and vector design.
Media
this section chứa 3 cột for video, Twitter, and Facebook.

Notice the above section slides, services, and media are positioned in the center, vậy chúng tôi sẽ gói chúng với div và đặt tên cho  container.
 

Widget :
this section  được chia thành 3 columns for links, blog, and location .Ngoài ra bạn sẽ nhận thấy nó được bao phủ bởi một mẫu màu xám chấm bao gồm toàn bộ màn hình.
 
Client: 
In this section bạn sẽ thấy có một đường viền màu xám rắn ở dưới cùng bao gồm toàn bộ màn hình và a list of clients logo.
 
Footer:

the footer được chia 2 columns  for copyright, footer links trở về đầu top arrow
 
 
code
<!doctype HTML>
	<html lang="en">
	<head>
	  <meta charset="utf-8">
	  <title>Burnstudio</title>
	  <link rel="stylesheet" href="style.css">
	</head>
<body>
<div id="header-wrap" >
		<header>
			
		</header>
	</div> <!-- end header-wrap -->
	<div id="container">
		<div id=siders>
			
		</div><!-- end siders -->
		<div id="service">
			
		</div><!-- end service -->
		<div id="media">
			
		</div><!-- end media -->
	</div><!-- end container -->
	</div>
	<div id="widget-wrap">
		<div id="widget">
			
		</div><!-- end widget -->
	</div><!-- end widget-wrap -->
	<div id="client-wrap">
		<div id="client">
			
		</div><!-- end client -->

	</div><!-- end client-wrap -->

	<footer>
				
	</footer><!-- end footer --></body>
</html>

Lưu ý rằng việc đặt tên các div trong mỗi phần dựa trên việc đặt tên chúng tôi đã làm trước đó khi chúng tôi phân tích bố cục PSD. Lưu ý rằng bố cục này có chiều rộng cố định là 960px. Tôi biết sẽ tốt hơn nếu sử dụng khung công tác CSS cho dự án này. Nhưng như tôi đã nói, chúng tôi sẽ làm điều đó từ đầu.
Step 4: Working on Header Section
Tập trung nhiều hơn vào the header section ,chúng ta sẽ đánh dấu các phần tử HTML có thể được tìm thấy trong phần này.
code
<div id="header-wrap" >

		<header>
			<h1> <a href="index.html" title="burnstudio">Burnstudio</a></h1>	
				<div id="call">
					<h3>(120) 345 6789</h3>
					<h4 class="gree">Call us <strong>now</strong> </h4>
				</div><!-- end call -->
			<nav class="group">
				<ul>
					<li class="home"><a href="#">Home</a></li>
					<li><a href="#">Service</a></li>
					<li><a href="#">About us</a></li>
					<li><a href="#">Testimonials</a></li>

					<li class="last">
						<div> <!--tạo thanh search và nút search-->
							<input type="text" name="search" placeholder="search"/>
							<input type="submit" name="search" value="go" class="search" />
						</div>
					</li>
				</ul>
			</nav>	
		</header>
	</div> <!-- end header-wrap -->


Trong HTML ở trên tôi chỉ theo những gì tôi thấy trong Photoshop. Đầu tiên là Logo, vì logo có thể click được Tôi thêm <a> tag bên trong h2. Tiếp theo là the the call number trong một div với một id của cuộc gọi. Cuối cùng tôi tạo ra một danh sách <ul> có chứa liên kết và tìm kiếm.
 Bây giờ hãy thêm CSS như sau: Tất cả CSS cần được thêm vào tệp style.css. Ngoài ra, hãy chắc chắn rằng bạn chỉ cần sao chép các thiết lập lại CSS mà tôi cung cấp trong các nguồn lực và đặt nó trong file style.css
	
Reset

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0; canh chinh 0
	padding: 0; khoảng cách 0
	border: 0; đường viền 0
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}

/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section 

{

	display: block; // hiển thị thành 1 khối
}
Body

{

	line-height: 1; //thiết lập chiều cao giữa các dòng.
}
ol, ul 

{

	list-style: none;  //thiết lập kiểu cho một danh sách không
}
blockquote, q 
{
	quotes: none; // Không hiển thị các loại dấu bao ngoài khi nhúng một trích dẫn.
}
blockquote:before, blockquote:after,
q:before, q:after 

{

	content: ''; //để chèn nội dung được tạo.
	content: none; //không chèn
}
table 
{

	border-collapse: collapse; Khoảng trống giữa các đường viền (border) của table bị loại bỏ, chỉ còn đường viền duy nhất.
	border-spacing: 0; //xác định khoảng cách đường viền của cách cột lân cân
}
/* END RESET */
Font style:
Body
{

	background: #fff; nền trắng
	font-family: Helvetica, Arial, sans-serif; kiểu chữ
	font-size: 13px; cở chữ
}
/* FONT STYLES*/
h3
{

	font-size: 24px; cở chữ
	font-family: Helvetica, Arial, sans-serif; kiểu chử
	color: #333333; màu chữ
	margin-bottom: 25px; canh lề dưới
}
h4
{

	margin-bottom: 25px;
	font-size: 18px;
	font-family: Helvetica, Arial, sans-serif;
}
H1
{

	font-size: 14px;
	font-family: Helvetica, Arial, sans-serif;
}
P
{

	font-size: 13px;
	color: #555555;
	line-height: 18px; khoảng cách chữ
}
a, a:link, a:visited //định dạng khi trước và sau khi click
{

	text-decoration: none; Định dạng văn bản bình thường, đây là dạng mặc định.
	outline: none;
}
.green
{

	color: #509743;
}
.white
{

	color: #fff;
}
Strong
{

	font-weight: bold;
}
/* END FONTS STYLES */
Header
/* HEADER */
#header-wrap
{

	border-top: 10px solid #4d9543; tạo đường viền trên xanh
	padding-top: 40px; khoảng cách top 30
}
Header
{
	
	width: 960px; độ rộng 
	margin: 0 auto; canh chỉnh
	padding: 0; khoảng cách
}
header h2 a
{

	display: block; hiển thị 1 khối 
	text-indent: -999999px;
	background: url(images/logo.png) no-repeat; đường link
	width: 214px; đọ rộng
	height: 77px; độ cao hình
	float: left;
	margin-bottom: 40px; khoảng cách từ hình tới khung xanh
}
#call
{

	float: right; vị trí bên phải
	border-right: 1px solid #c8c8c8; tạo đường viền phải
	padding-right: 25px; khoảng cách cách viền
	margin-top: 20px; 
}
#call h3
{

	margin: 0; canh chỉnh
}
#call h4
{

	text-align: right; chữ bên phải
	margin: 0; canh chỉnh
}
Nav
{

	clear: both; ko cần float trái hay phải
	// độ cao và chiều rộng cũa khung
	width: 960px; 
	height: 50px;
	// tạo khung tròn 2 đầu
	-moz-border-radius: 30px;
	-webkit-border-radius: 30px;
	background-color: #3b7c33; /* Fallback */ màu nền xanh
	border-radius: 30px; độ bo 2 đầu
	
               màu từ nhạt tới đậm cho tất cả các trình duyệt

	/* Safari 4+, Chrome 1-9 */
	background-image: -webkit-gradient(linear, 0% 0%, 0% 100%, from(#5fae53), to(#3b7c33));
	/* Safari 5.1+, Mobile Safari, Chrome 10+ */
	background-image: -webkit-linear-gradient(top, #5fae53, #3b7c33);
	/* Firefox 3.6+ */
	background-image: -moz-linear-gradient(top, #5fae53, #3b7c33);
	/* IE 10+ */
	background-image: -ms-linear-gradient(top, #5fae53, #3b7c33);
	/* Opera 11.10+ */
	background-image: -o-linear-gradient(top, #5fae53, #3b7c33);
	border: 1px solid #336c2b;
}
nav ul li 
{

	float: left; vị trí bên trái
	border-right: 1px solid #336c2b; đường viền phải 
	border-left: 1px solid #78c368; đường viền trái
}
nav ul li.home chuyển chữ Home thành hình
{

	border-left: none; ẩn đường viền  trái của chữ Home
	text-indent: -9999px; khoảng cách chữ home thục vào đầu dòng
	background: url(images/home.png) no-repeat 50% 50%;
}
nav ul li.last vùng search
{

	border-left: none; ẩn đường viền trái
	border-right: none; ẩn đường viền phải
	float: right; vị trí phải 
	margin-right: 20px; khoảng cách bên phải cách 20
}
nav ul li a
{

	display: block; hiển thị hình
	padding: 0 30px; khoảng cách trên dưới 0 trái phải cách nhau 30
	height: 50px;  cao của hình home
	line-height: 50px; khoang cách của chữ
	font-size: 15px; cở chữ
	color: #fff; mau chữ
	text-shadow: 0 1px 0 #387031; bóng
}
nav ul li a:hover khi trỏ chuột vào chữ
{

	background: #5fae53; màu nền sẽ là màu xanh nhạt
}
nav ul li.home a:hover
{	

	// tạo hiệu ứng vòng bo bên trái khi trỏ chuột vào 
	-webkit-border-top-left-radius: 30px;
	-webkit-border-bottom-left-radius: 30px;
	border-top-left-radius: 30px;
	border-bottom-left-radius: 30px;
	// hình nền khỉ trỏ chuột vào
	background: #5fae53 url(images/home.png) no-repeat 50% 50%;
}
nav ul li div input[type=text]
{	
	
	tạo khung bo trò 2 đầu nhỏ cho text
	-webkit-border-radius: 20px;
	-moz-border-radius: 20px;
	background: #4b9241;
	
	border-left: none;
	border-right: none;
	border-bottom: 1px solid #5ead52;
	border-top: 1px solid #346d2c;

	color: #fff; chữ trắng
	//tạo bóng và khoảng cách của chữ
	text-shadow: 0 1px 0 #387031;
	padding: 5px 0 5px 20px;
	width: 200px;
}
nav ul li div input[type=text]:focus
{

	outline: none;
}
/* TO STYLE PLACE HOLDER */
Tạo search chữ trắng
::-webkit-input-placeholder
 {
 
   color: #fff;
}
:-moz-placeholder 
{

   color: #fff;
}
nav ul li div input[type=submit]
{

	background: url(images/search.png) no-repeat 50% 50%; hình canh chỉnh hình
	border: none; ẩn viền
	text-indent: -999999px;
	margin-left: 15px; canh chinh trái
	height: 50px;độ cao
	width: 16px; độ rộng
}
/* END HEADER */
Giải thích Header
Trong phần đầu CSS styled header-wrap với một đường viền màu xanh lá cây 10px, vì 1 div mặc định được tạo a block display width of the screen

#header-wrap
{

	border-top: 10px solid #4d9543;
	padding-top: 40px;
}


Sau đó, tôi trung tâm tiêu đề với lề: 0 tự động. Tiếp theo, tôi tạo mẫu Logo với chiều rộng và chiều rộng cố định. Tôi cũng thả nó sang bên trái.
Header
{

	width: 960px;
	margin: 0 auto;
	padding: 0;
}
header h1 a
{

	display: block;
	text-indent: -999999px;
	background: url(img/logo.png) no-repeat;
	width: 214px;
	height: 77px;
	float: left;
	margin-bottom: 40px;
}
Đối với the Call  thả nó vào đúng và áp dụng một đường viền màu xám 1px cũng cách đệm 25px từ bên phải. Lưu ý rằng để có được giá trị này bạn cần phải quay trở lại Photoshop và sử dụng Công cụ Ruler (I) để đo khoảng cách. Vì tôi đã tạo kiểu h3 và h4 với biên dưới cùng 25px trong định dạng văn bản cơ sở của chúng tôi, chúng tôi cần phải đặt lại nó và thay đổi nó thành 0.
#call{

	float: right;
	border-right: 1px solid #c8c8c8;
	padding-right: 25px;
	margin-top: 20px;
}
#call h3{

	margin: 0;
}
#call h4{

	text-align: right;
	margin: 0;
}
Tiếp theo, tôi tạo the navigation  với chiều rộng, chiều cao và gradient cố định, tôi đã áp dụng một cách rõ ràng để xóa các biểu tượng nổi trên và gọi.
nav{

	clear: both; 
	
	width: 960px;
	height: 50px;
	
	-moz-border-radius: 30px;
	-webkit-border-radius: 30px;
	
	background-color: #3b7c33; /* Fallback */	
	border-radius: 30px;
	/* Safari 4+, Chrome 1-9 */
	background-image: -webkit-gradient(linear, 0% 0%, 0% 100%, from(#5fae53), to(#3b7c33));
	/* Safari 5.1+, Mobile Safari, Chrome 10+ */
	background-image: -webkit-linear-gradient(top, #5fae53, #3b7c33);
	/* Firefox 3.6+ */
	background-image: -moz-linear-gradient(top, #5fae53, #3b7c33);
	/* IE 10+ */
	background-image: -ms-linear-gradient(top, #5fae53, #3b7c33);
	/* Opera 11.10+ */
	background-image: -o-linear-gradient(top, #5fae53, #3b7c33);
	
	border: 1px solid #336c2b;
}
Tất cả các li được thả nổi bên trái trừ phần tử li cuối cùng, cũng có một đường viền trái và phải, ngoại trừ ngôi nhà không có đường viền trái và đường cuối cùng không có đường viền phải.
nav ul li
{

	float: left; 
	border-right: 1px solid #336c2b;
	border-left: 1px solid #78c368;
}
nav ul li
{

	float: left; 
	border-right: 1px solid #336c2b;
	border-left: 1px solid #78c368;
}
nav ul li.home
{

	border-left: none;
	text-indent: -9999px;
	background: url(img/home.png) no-repeat 50% 50%;
}
nav ul li.last
{

	border-left: none;
	border-right: none;
	float: right;
	margin-right: 20px;
}
Tất cả các pad pad 30px theo kiểu từ trái sang phải 0 cho trên cùng và dưới cùng, chiều cao là 50, bóng chéo, chiều cao 50 để làm cho nó thẳng đứng theo chiều dọc. Đối với lớp học nhà tôi đẩy ra các văn bản và thay thế nó với các biểu tượng nhà.
nav ul li a
{

	display: block; 
	padding: 0 30px;
	height: 50px;
	line-height: 50px;
	font-size: 15px;
	color: #fff;
	text-shadow: 0 1px 0 #387031;
}
Kể từ khi góc được làm tròn, chúng ta cần phải chỉ định một phong cách hover khác cho nút home đó là những gì tôi làm dưới đây: hover.
nav ul li a:hover
{

	background: #5fae53;
}
nav ul li.home a:hover
{

	-webkit-border-top-left-radius: 30px;
	-webkit-border-bottom-left-radius: 30px;
	border-top-left-radius: 30px;
	border-bottom-left-radius: 30px;
	
	background: #5fae53 url(img/home.png) no-repeat 50% 50%;
}
Cuối cùng, tôi tạo kiểu đầu vào tìm kiếm có bán kính tròn, nền xanh lá cây, đường viền đen trên đường viền trên cùng và dưới đáy. Ngoài ra để nhắm mục tiêu thuộc tính thuộc tính tham khảo CSS mà tôi nhận xét để phong cách giữ chỗ này là một phần của tài sản css3.
nav ul li div input[type=text]
{

	-webkit-border-radius: 20px;
	-moz-border-radius: 20px;
	background: #4b9241;
	border-left: none;
	border-right: none;
	border-bottom: 1px solid #5ead52;
	border-top: 1px solid #346d2c;
	color: #fff; 
	text-shadow: 0 1px 0 #387031;
	padding: 5px 0 5px 20px;
	width: 200px;
}
nav ul li div input[type=text]:focus
{

	outline: none;
}
::-webkit-input-placeholder
 {
 
   color: #fff;
}
:-moz-placeholder 
{

   color: #fff;
}
nav ul li div input[type=submit]
{

	background: url(img/search.png) no-repeat 50% 50%;
	border: none;
	text-indent: -999999px;
	margin-left: 15px;
	height: 50px;
	width: 16px;
}
Trước khi xem trước các phiên bản thấp hơn của IE, đảm bảo sao chép và dán mã dưới đây vào phần tiêu đề của tệp HTML của chúng tôi. Điều này sẽ cho phép các phần tử HTML5 hoạt động trong các trình duyệt IE cũ hơn.
Step 5: Working on Slider Section
Now let’s add the content inside the slides element, here’s the HTML:
Code


<div id="container">
		<div id=slides>
			<div class="slides_container">
				<div>
					<img src="img/slide1.png" alt="slide1" />
					<div class="slide-right">
						<h1 class="slide-heading">Artthatworks 1 dolor sit amet, consectetur adipiscing elit.</h1>
						Vestibulum a diam lorem. Fusce viverra commodo rhoncus. Nam ipsum magna, faucibus non semper et, vestibulum quis arcu. Nulla in tellus eu nunc cursus scelerisque ac nec nibh.
						<a href="#" class="readmore">Read more</a>
					</div><!-- end side-right -->
				</div>
				<div>
					<img src="img/slide1.png" alt="slide1" />
					<div class="slide-right">
						<h1 class="slide-heading">Artthatworks 2 dolor sit amet, consectetur adipiscing elit.</h1>
						Vestibulum a diam lorem. Fusce viverra commodo rhoncus. Nam ipsum magna, faucibus non semper et, vestibulum quis arcu. Nulla in tellus eu nunc cursus scelerisque ac nec nibh.
						<a href="#" class="readmore">Read more</a>
					</div><!-- end side-right -->
				</div>
				<div>
					<img src="img/slide1.png" alt="slide1" />
					<div class="slide-right">
						<h1 class="slide-heading">Artthatworks 3 dolor sit amet, consectetur adipiscing elit.</h1>
						Vestibulum a diam lorem. Fusce viverra commodo rhoncus. Nam ipsum magna, faucibus non semper et, vestibulum quis arcu. Nulla in tellus eu nunc cursus scelerisque ac nec nibh.
						<a href="#" class="readmore">Read more</a>
					</div><!-- end side-right -->
				</div>						
			</div><!-- end slides_container -->
		</div><!-- end siders -->
Trong đánh dấu HTML ở trên tôi đã thêm một lớp slides_container sẽ giữ các phần tử trang trình bày của chúng tôi được bao bọc bởi một div có chứa một hình ảnh, một lớp div của trang trình bày bên phải chứa tiêu đề trang trình bày, thông tin, và liên kết nhiều hơn.

Tôi cũng đã thêm một class slide-heading , thông tin the read more readmore. Điều này sẽ hữu ích vì chúng ta sẽ lặp lại mã HTML 3 lần và chúng sẽ có cùng kiểu nếu chúng ta thêm CSS sau.
Now let’s style all the element, here’s the CSS.
#container
{
	width: 960px; độ rộng của phần slides
	margin: 0 auto;
}
/* SLIDES */
#slides
{

	position: relative; vị trí tuyệt đối
	margin-top: 40px; cách top 40
}
.slides_container
{

	height: 315px;
}
.slide-right
{

	position: absolute; định vị theo thành phần bên ngoài
	top: 0;
	left: 385px; cách trái
}
.slide-heading
{

	background: url(images/slide-heading.png) no-repeat; hình
	width: 494px; độ rộng 
	height: 68px;chiều cao
	color: #fff; chữ trắng
	font-size: 24px; cở chữ
	khoảng cách chữ trên và trái
	padding-top: 20px;
	padding-left: 80px;
	canh chỉnh trên dưới
	margin-top: 35px;
	margin-bottom: 30px;
}
.slide-right .info
{

	width: 395px; độ rộng
	margin-bottom: 20px; canh dưới
	margin-left: 155px; canh trái
}
.slide-right .readmore
{

	margin-left: 155px; canh trái
}
.readmore
{

	font-style: italic; kiểu in nghiêng
	text-decoration: none; trang tri rổng
	color: #509743; màu
	padding-left: 15px; thêm khoảng cách trái
	background: url(images/more.png) no-repeat 0 50%; hình
}
.readmore:hover
{

	color: #c8c8c8; màu chữ khi trỏ chuột vào
}
.pagination
{

	position: absolute;
	bottom: 25px;
	left: 25px;
	z-index: 99;
}
ul.pagination li
{

	float: left; nằm bên trái
	margin-right: 10px; canh phải 10px
	background: url(images/pagination.png) no-repeat; hình
	background-position: top; 
	width: 14px; độ rộng của hình
	height: 15px; độ cao của hình
}
ul.pagination li.current
{

	background-position: bottom; vị trí bi xanh
}
ul.pagination li a
{

	display: block; hiển thị theo khối
	text-indent: -999999px; ẩn chữ
}
a.next
{

	position: absolute;
	right: 25px; cách phải
	bottom: 30px; cách dưới
	display: block; hiển thị 
	width: 7px; độ rộng
	height: 13px; độ cao
	background: transparent url(images/prev-next.png) no-repeat; hình
	background-position: top right; hình phải
	text-indent: -9999px;
}
a.prev
{

	position: absolute;
	right: 50px;
	bottom: 30px;
	display: block;
	width: 7px;
	height: 13px;
	background: transparent url(images/prev-next.png) no-repeat;
	background-position: top left; hình trái
	text-indent: -9999px;
}
a.next:hover
{

	background-position: bottom right; hình phải
}
a.prev:hover
{

	background-position: bottom left; hình trái
}
/* END SLIDES*/

Trong CSS ở trên kể từ khi các trang trình bày, dịch vụ và phương tiện được gói với div bộ chứa, chúng tôi sẽ tạo kiểu này trước để làm cho chúng căn giữa. Tiếp theo, vị trí của slide được thiết lập để tương đối để làm cho nó thành phần cha mẹ.
Điều này hữu ích để chúng ta có thể định vị các phần tử bên trong prev, Next và Pagination hoàn toàn được tự động tạo ra bởi JavaScript. Đối với các slides_container tôi đã cho nó một chiều cao cố định 315px đó bằng chiều cao của hình ảnh trượt.
Đối với phần trượt bên phải chứa tiêu đề, thông tin và chi tiết, tất cả các vị trí hoàn toàn, 0 trên đầu, và đẩy nó 385px từ trái.


Đối với phần đầu chiếu, tôi cho nó một chiều rộng và chiều cao cố định bằng hình nền, và cho nó một padding để làm cho văn bản căn chỉnh đúng, cũng là một lề để cung cấp cho một không gian và align nó một cách chính xác.


Đối với. Thông tin tôi đã cho nó một chiều rộng cố định với lề để sắp xếp nó. Đối với .readmore đầu tiên tôi đã cho nó một phong cách margin riêng biệt vì chỉ có thanh trượt readmore có này và tất cả các liên kết readmore trong cách bố trí không có lề từ trái. Tiếp theo là kiểu dáng readmore có màu xanh lục với mũi tên trên nền và một con trỏ màu xám.


Đối với các nút phân trang, trước và tiếp theo đây là tự động tạo ra bởi JavaScript để kiểu này trước tiên chúng ta cần xác định thẻ là gì hoặc thuộc tính lớp html được áp dụng.


Để thực hiện việc này, bạn cần phải sử dụng công cụ Firebug nếu bạn đang sử dụng Firefox, nếu bạn đang sử dụng Chrome chỉ cần nhấp chuột phải vào phần tử và nhấp vào Kiểm tra phần tử hộp thoại sẽ xuất hiện và bạn có thể thấy có yếu tố nào đang được sử dụng.


Bây giờ bạn đã biết phần tử, chúng ta sẽ nhắm mục tiêu nó trong CSS. Đối với các Ghinits tôi đặt nó hoàn toàn, đặt nó 25px từ dưới cùng và trái, tôi cũng áp dụng z-index 99px - điều này sẽ làm cho pagination ngay trên đầu trên các yếu tố khác.


Nếu chúng tôi sẽ không áp dụng thông báo này vì nó không thể nhấp được vì hình ảnh nằm trên đầu trang của bộ phận pagination. Sau đó, tôi di chuyển các phần tử li phân trang sang trái, cho nó một lề phải 10px, thêm một hình nền với chiều rộng cố định và chiều cao.

Tôi đặt nền theo mặc định lên trên cùng vì hình trạng thái bình thường nằm ở trên, cho trạng thái hiện tại hoặc trạng thái hoạt động, chúng ta sẽ đảo ngược vị trí từ trên xuống dưới và cuối cùng hiển thị nó như một phần tử cấp khối và giấu văn bản.


Đối với .next và .prev khá nhiều giống như chúng ta đã làm trong pagination nhưng lần này nó được đặt bên phải.


Chú ý the prev-next.png ở bên trái hình này chứa hình ảnh của nút prev và phía bên phải hình này chứa hình ảnh của nút tiếp theo.


Tôi đã định vị  the .next image to top right, .prev positioned to top-left, and for the hover just change the top to bottom..


Bây giờ, hãy thêm tập lệnh jQuery được yêu cầu vào tiêu đề. Sao chép tệp tin slides.min.jquery.js từ thư mục nguồn / và dán nó vào thư mục / js của chúng tôi.


<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js"></script>
 <script src="js/slides.min.jquery.js"></script>


Finally, we need to add the JavaScript code that will allow the slider to work on our layout. You should add this script just before the . Here’s the JavaScript.

<script>
$(function(){$('#slides').slides({preload: true,generateNextPrev: true,});});
</script>


<script>
$(function(){$('#slides').slides({preload: true,generateNextPrev: true,});});
</script>
 
