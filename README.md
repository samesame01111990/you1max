<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
  <meta charset='UTF-8'/>
  <meta content='width=device-width, initial-scale=1' name='viewport'/>
  <meta content='IE=edge' http-equiv='X-UA-Compatible'/>

  <meta content='#b7c1ca' name='theme-color'/>
  <link expr:href='data:blog.canonicalUrl' rel='canonical'/>

  <!-- SEO -->
  <title><data:blog.title/></title>
  <meta expr:content='data:blog.metaDescription' expr:default='&quot;Mô tả mặc định cho blog&quot;' name='description'/>
  <meta content='index, follow' name='robots'/>

  <!-- Open Graph -->
  <meta content='website' property='og:type'/>
  <meta expr:content='data:blog.title' property='og:title'/>
  <meta expr:content='data:blog.metaDescription' expr:default='&quot;Mô tả mặc định cho blog&quot;' property='og:description'/>
  <meta expr:content='data:blog.url' property='og:url'/>
  <meta content='https://blogger.googleusercontent.com/img/a/AVvXsEgeYXCRRax_ktrDuYyUcfZaE-nc_UEs7dI7CUc89W5YLsMtuagJ7X6LafS4D-Iv5TOj3XPk3AVWcwIWB2AjlT00QKYpxMy5rvfGssoQ1DmeKj5HqBev0hu0_s9V-LkGffRB2RXwbXsZc92wvNMstNs_EEUU4c7PJxYWYil0Z1NzUUTv-mjPmU6o-DZ0nbM=s16000' expr:default='&quot;https://blogger.googleusercontent.com/img/a/AVvXsEjDhtjI4KydhMVrPgtqEUJM2jVg24E7JaFDrm9C24gacUb4KMV02tXfwsMrl9kNCQplRyKuG6SXwC5bgtnXgIFaOeN6IFusx1lu5h_Csi06aLAFkBc5KwYVJ0fpFLvU3ph3Adtw0xoyte6JpKp4KDlGcU14w668zXvmnpqEDe-LhDmaXIqRfjn5U7Au3Is=s16000&quot;' property='og:image'/>
  <meta expr:content='data:blog.locale' property='og:locale'/>
  <meta expr:content='data:blog.title' property='og:site_name'/>

  <!-- Twitter Card -->
  <meta content='summary_large_image' name='twitter:card'/>
  <meta expr:content='data:blog.title' name='twitter:title'/>
  <meta expr:content='data:blog.metaDescription' expr:default='&quot;Mô tả mặc định cho blog&quot;' name='twitter:description'/>
  <meta expr:content='data:blog.url' name='twitter:url'/>
  <meta content='https://blogger.googleusercontent.com/img/a/AVvXsEgeYXCRRax_ktrDuYyUcfZaE-nc_UEs7dI7CUc89W5YLsMtuagJ7X6LafS4D-Iv5TOj3XPk3AVWcwIWB2AjlT00QKYpxMy5rvfGssoQ1DmeKj5HqBev0hu0_s9V-LkGffRB2RXwbXsZc92wvNMstNs_EEUU4c7PJxYWYil0Z1NzUUTv-mjPmU6o-DZ0nbM=s16000' expr:default='&quot;https://blogger.googleusercontent.com/img/a/AVvXsEjDhtjI4KydhMVrPgtqEUJM2jVg24E7JaFDrm9C24gacUb4KMV02tXfwsMrl9kNCQplRyKuG6SXwC5bgtnXgIFaOeN6IFusx1lu5h_Csi06aLAFkBc5KwYVJ0fpFLvU3ph3Adtw0xoyte6JpKp4KDlGcU14w668zXvmnpqEDe-LhDmaXIqRfjn5U7Au3Is=s16000&quot;' name='twitter:image'/>
  <meta content='Hình ảnh đại diện cho blog chia sẻ khóa học' name='twitter:image:alt'/>

  <!-- Schema: Website -->
  <script type='application/ld+json'>
  {
    &quot;@context&quot;: &quot;https://schema.org&quot;,  
    &quot;@type&quot;: &quot;WebSite&quot;,
    &quot;name&quot;: &quot;<data:blog.title/>&quot;,
    &quot;description&quot;: &quot;<data:blog.metaDescription/>&quot;,
    &quot;url&quot;: &quot;<data:blog.url/>&quot;,
    &quot;potentialAction&quot;: {
      &quot;@type&quot;: &quot;SearchAction&quot;,
      &quot;target&quot;: &quot;<data:blog.url/>?q={search_term_string}&quot;,
      &quot;query-input&quot;: &quot;required name=search_term_string&quot;
    }
  }
  </script>

  <!-- CSS cho màu nền động -->
  <style>
    /* Màu nền cho .content */
    .content {
      flex-grow: 1;
      padding: 0 5px;
      overflow-y: auto;
      overflow-x: hidden;
      display: flex;
      flex-direction: column;
      width: 100%;
    }
    /* Màu nền cho trang chủ */
    <b:if cond='data:view.isHomepage'>
      .content {
        background-color: #fff;
      }
    </b:if>
    /* Màu nền cho trang bài đăng */
    <b:if cond='data:view.isPost'>
      .content {
        background-color: #b7c1ca;
      }
    </b:if>
  </style>

  <!-- CSS chính -->
  <b:skin><![CDATA[
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      overflow-x: hidden;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.3;
      color: #333;
      background-color: #fff;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      overflow-x: hidden;
    }

    .container {
      max-width: 100%;
      width: 100%;
      margin: 0 auto;
      text-align: center;
      box-sizing: border-box;
    }

    img {
      max-width: 100%;
      height: auto;
    }

    a {
      text-decoration: none;
      color: #2196F3

;
    }

    a:visited, a:active {
      color: #2196F3;
    }

    .post-outer {
      max-width: 750px;
      width: 100%;
      margin: 0 auto;
      padding: 0;
      border: none;
      text-align: left;
    }

    .visually-hidden {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      white-space: nowrap;
      border: 0;
    }

    .post-body {
      font-size: 16px;
      line-height: 1.3;
      color: #333;
      margin: 0;
      padding: 0;
    }

    .post-body a:hover {
      text-decoration: underline;
    }

    .post-meta,
    .blog-pager,
    .feed-links {
      display: none;
    }

    .widget {
      margin: 0 auto;
      padding: 10px;
      width: 100%;
      box-sizing: border-box;
    }

    .widget a[href*="/search/label/"],
    .widget .post-title,
    .widget h2 a,
    .widget .title a,
    .widget .title,
    .widget h2.title {
      display: none;
    }

    /* CSS cho header đầu tiên */
    .header-first {
      background-color: #000; /* Cập nhật từ #333 thành #000 */
      color: #fff;
      padding: 2px 0;
      width: 100%;
    }

    .header-first-container {
      max-width: 1200px;
      width: 100%;
      margin: 0 auto;
      padding: 0 10px;
      box-sizing: border-box;
    }

    .header-first-widget {
      text-align: center;
    }

    .header-first-widget * {
      color: #fff;
    }

    /* CSS cho header thứ hai */
    .header-second {
      background-color: #fff;
      color: #333; /* Màu chữ tối để phù hợp nền trắng */
      padding: 2px 0;
      width: 100%;
    }

    .header-second-container {
      max-width: 1200px;
      width: 100%;
      margin: 0 auto;
      padding: 0 10px;
      box-sizing: border-box;
    }

    .header-second-widget {
      text-align: center;
    }

    .header-second-widget * {
      color: #333; /* Màu chữ tối để phù hợp nền trắng */
    }

    @media only screen and (max-width: 768px) {
      .post-outer {
        max-width: 100%;
      }
      .content {
        padding: 0 10px;
      }
      .header-first-container,
      .header-second-container {
        padding: 0 5px;
      }
    }
  ]]></b:skin>
</head>

<body>
  <!-- Header đầu tiên chỉ hiển thị trên trang chủ -->
  <b:if cond='data:view.isHomepage'>
    <header class='header-first'>
      <div class='header-first-container'>
        <b:section id='header' showaddelement='true'>
          <b:widget id='HTML2' locked='false' title='BANNER YOU1MAX' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<div style="text-align: center;">
  <a href="https://you1max.blogspot.com" title="Visit you1max blogspot">
    <div class="separator" style="clear: both; text-align: center;">
      <img 
        src="https://blogger.googleusercontent.com/img/a/AVvXsEizetS9t0d087HL5aA_RcCXTB1u2i0WYTZWJevy0oxzI1beCSJ2gyhClp-aUvdrF0_S02ZeA028OFMuFJoyCq4o0DuaD_u4jGlmT_DFDW4SicvE-1OONS0WC3gTG78qr74oVRwWvyAJ2eICSbEKAVMZg3QbO-1oTj0x29rk6KfKMQpG30YnfNFt0_KvCSQ" 
        width="200" 
        height="32" 
        alt="you1max blog logo" 
      />
    </div>
    <div style="text-align: center;">
      <span id="text1" style="color: gold; font-weight: bold; font-family: arial; font-size: x-large;">
        sharing useful courses
      </span>
      <span id="text2" style="color: white; display: none; font-family: arial; font-size: x-large;">
        <b>you1max.blogspot.com</b>
      </span>
    </div>
  </a>
</div>

<script>
  let showFirst = true;

  setInterval(() => {
    const text1 = document.getElementById("text1");
    const text2 = document.getElementById("text2");

    if (showFirst) {
      text1.style.display = "none";
      text2.style.display = "inline";
    } else {
      text1.style.display = "inline";
      text2.style.display = "none";
    }

    showFirst = !showFirst;
  }, 7000); // đổi mỗi 7 giây
</script>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>
    </header>
    <!-- Header thứ hai chỉ hiển thị trên trang chủ -->
    <header class='header-second'>
      <div class='header-second-container'>
        <b:section id='header2' showaddelement='true'>
          <b:widget id='HTML8' locked='false' title='LESSONS OF YOU1MAX' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<!-- DANH SÁCH BÀI HỌC (KHÔNG XUNG ĐỘT CSS - GIỮ NGUYÊN GIAO DIỆN GỐC) -->
<style>
.dsh-next-button {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 6px 24px;
  background: #cf0002;
  color: #fff;
  font-size: 16px;
  font-weight: bold;
  border: none;
  border-radius: 16px;
  cursor: pointer;
  text-decoration: none !important;
  transition: opacity 0.3s ease;
}
.dsh-next-button:hover,
.dsh-next-button:focus,
.dsh-next-button:active,
.dsh-next-button:visited {
  color: #fff !important;
  opacity: 0.9;
  text-decoration: none !important;
}
.dsh-next-button svg {
  width: 20px;
  height: 20px;
  fill: #fff;
}

.dsh-custom-text-width {
  max-width: 750px;
  width: 100%;
  margin: 0 auto;
  box-sizing: border-box;
  overflow-wrap: break-word;
  overflow-x: auto;
}

.dsh-custom-text-width iframe {
  max-width: 100%;
  width: 100%;
  height: auto;
  aspect-ratio: 16 / 9;
}

.dsh-center-text {
  text-align: center;
  font-family: Roboto Condensed, sans-serif;
}
.dsh-welcome-title {
  color: #351c75;
  font-size: x-large;
  font-weight: bold;
  margin: 0;
}
.dsh-lesson-content {
  font-family: Roboto Condensed;
  color: #404040;
  text-align: left; /* ⚠️ Đảm bảo căn trái */
}
.dsh-highlight {
  color: #cc0000;
}

.dsh-center-container {
  display: flex;
  justify-content: center;
}
.dsh-content-box {
  background-color: #f1f1f1;
  color: #444;
  padding: 18px;
  width: 100%;
  max-width: 655px;
  border-radius: 25px;
  font-size: 15px;
  box-sizing: border-box;
}
.dsh-content-box a {
  text-decoration: none;
  color: inherit;
}
.dsh-content-box a:hover {
  text-decoration: none;
}

.dsh-roboto-condensed {
  font-family: 'Roboto Condensed', sans-serif;
  font-size: 18px;
}

.dsh-lesson-content em {
  font-style: normal;
}

#dsh-current-date {
  font-style: normal;
}

</style>

<!-- NÚT YOUTUBE -->
<div style="text-align: center;">
  <a class="dsh-next-button" href="https://www.youtube.com/channel/UCm9Q17kI60ufyZutWJZIiZg?sub_confirmation=1" target="_blank" rel="noopener" aria-label="Subscribe to my YouTube channel">
    <svg viewbox="0 0 24 24" aria-hidden="true">
      <path d="M23.5 6.2s-.2-1.6-.8-2.3c-.8-.9-1.7-1-2.1-1.1C17.6 2.5 12 2.5 12 2.5h-.1s-5.6 0-8.6.3c-.4.1-1.3.2-2.1 1.1C.6 4.6.5 6.2.5 6.2S0 8.1 0 10v1.9c0 1.9.5 3.8.5 3.8s.2 1.6.8 2.3c.8.9 1.8 1 2.3 1.1 1.7.2 7.4.3 7.4.3s5.6 0 8.6-.3c.4-.1 1.3-.2 2.1-1.1.6-.7.8-2.3.8-2.3s.5-1.9.5-3.8V10c0-1.9-.5-3.8-.5-3.8zM9.6 14.6V8.4l6.2 3.1-6.2 3.1z"/>
    </path></svg>
    Subscribe my YouTube channel
  </a>
</div>

<br />

<!-- VÙNG GIỚI THIỆU -->
<div class="dsh-custom-text-width">
  <div class="dsh-center-text">
    <h1 class="dsh-welcome-title">Welcome, students!</h1>
  </div>

  <br />

  <div class="dsh-lesson-content dsh-roboto-condensed">
    <i id="dsh-current-date"></i>
    <em>
      Before you begin your learning process, I want you to pay attention to this instruction. <b>Lesson 01</b> is just 3 minutes and 3 seconds long, out of a total of <b>11 hours</b> of training and <b>65 video lessons</b> in this course — but it lays a very important foundation for everything that follows. It explains the core mindset and the overall structure, so please make sure to watch it <b>first—and carefully</b>. This course includes real-world insights, proven formulas, and valuable tips that I’ve refined through years of experience, to help you earn tens, or even hundreds, of thousands of dollars monthly online, with dedication and effort. I highly recommend reviewing the course a second time—or even multiple times—to get the most out of it. <span class="dsh-highlight"><b>Note: If the video doesn't play, please reload the lesson page and it should work normally.</b></span> Wishing you health, success, and a great learning journey!
    </em>
  </div>
</div>


<br />

<!-- DANH SÁCH BÀI HỌC -->
<div class="dsh-center-container">
  <div class="dsh-content-box">






<div style="text-align: left;"><b><a href="https://you1max.blogspot.com/2025/05/1.html"><span style="background-color: #fcff01; font-family: Roboto Condensed; font-size: 18px;"><span style="color: black;">Lesson 01:</span> <span style="color: #0f77d2;">Must-Watch – Don’t Skip This One</span></span></a></b></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span></b></span><a href="https://you1max.blogspot.com/2025/04/2.html"><span style="font-family: Roboto Condensed; font-size: 18px;"><b><span><span style="color: black;">Lesson 02:</span> </span></b></span><span style="color: #2695eb; font-family: Roboto Condensed; font-size: 18px;"><b>Tap Into the Growth You Can’t Ignore</b></span></a></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/3.html"><span style="color: black;">Lesson 03:</span> <span style="color: #2695eb;">Basic Introduction</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/4.html"><span style="color: black;">Lesson 04:</span> <span style="color: #2695eb;">The Initial Preparation Steps</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/5a.html"><span style="color: black;">Lesson 05:</span> <span style="color: #2695eb;">Registration</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/6.html"><span style="color: black;">Lesson 06:</span> <span style="color: #2695eb;">Product Research Overview</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/7.html"><span style="color: black;">Lesson 07:</span> <span style="color: #2695eb;">How to Calculate Accurate Numbers for Products</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/8a.html"><span style="color: black;">Lesson 08:</span> <span style="color: #2695eb;">Demand Is All That Matters</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/9.html"><span style="color: black;">Lesson 09:</span> <span style="color: #2695eb;">My Tool Secrets</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/10a.html"><span style="color: black;">Lesson 10:</span> <span style="color: #2695eb;">Secrets to the Most Effective Product Research</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/11.html"><span style="color: black;">Lesson 11:</span> <span style="color: #2695eb;">Picked a Winning Product!</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/12.html"><span style="color: black;">Lesson 12:</span> <span style="color: #2695eb;">The Final Formula</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/13.html"><span style="color: black;">Lesson 13:</span> <span style="color: #2695eb;">How To STAND OUT</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/14.html"><span style="color: black;">Lesson 14:</span> <span style="color: #2695eb;">Bonus - How Does It Work</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/15.html"><span style="color: black;">Lesson 15:</span> <span style="color: #2695eb;">Secrets to Creating a Brand Name</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/16.html"><span style="color: black;">Lesson 16:</span> <span style="color: #2695eb;">Secrets to Creating a Logo</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/17.html"><span style="color: black;">Lesson 17:</span> <span style="color: #2695eb;">Product Variations vs. Stand-Alone Listings</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/18.html"><span style="color: black;">Lesson 18:</span> <span style="color: #2695eb;">BONUS. Getting Un-gated in Categories</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/19.html"><span style="color: black;">Lesson 19:</span> <span style="color: #2695eb;">Secrets to an Endless Source of Products</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/20.html"><span style="color: black;">Lesson 20:</span> <span style="color: #2695eb;">Secrets to Supplier Mastery</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/21.html"><span style="color: black;">Lesson 21:</span> <span style="color: #2695eb;">Secrets to Successful Transactions</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/22.html"><span style="color: black;">Lesson 22:</span> <span style="color: #2695eb;">Final Product Metrics Calculation</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/23.html"><span style="color: black;">Lesson 23:</span> <span style="color: #2695eb;">Shipping Methods</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/24.html"><span style="color: black;">Lesson 24:</span> <span style="color: #2695eb;">Printing Your FNSKU Labels</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/25.html"><span style="color: black;">Lesson 25:</span> <span style="color: #2695eb;">Secrets to Product Inspection</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/26.html"><span style="color: black;">Lesson 26:</span> <span style="color: #2695eb;">Secrets to Creating Product Listings</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/27.html"><span style="color: black;">Lesson 27:</span> <span style="color: #2695eb;">Secrets to Copyright Mastery</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/28.html"><span style="color: black;">Lesson 28:</span> <span style="color: #2695eb;">Secrets to Keyword Mastery</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/29.html"><span style="color: black;">Lesson 29:</span> <span style="color: #2695eb;">Mastering Product Images</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/30.html"><span style="color: black;">Lesson 30:</span> <span style="color: #2695eb;">Enhanced Product Listings - Part 1</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/31.html"><span style="color: black;">Lesson 31:</span> <span style="color: #2695eb;">Enhanced Product Listings - Final Product</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/32.html"><span style="color: black;">Lesson 32:</span> <span style="color: #2695eb;">SUMMARY: What We Have Done</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/33.html"><span style="color: black;">Lesson 33:</span> <span style="color: #2695eb;">UPC Barcode</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/34.html"><span style="color: black;">Lesson 34:</span> <span style="color: #2695eb;">Adding New Products</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/35.html"><span style="color: black;">Lesson 35:</span> <span style="color: #2695eb;">Printing and Shipping Your Labels</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/36.html"><span style="color: black;">Lesson 36:</span> <span style="color: #2695eb;">Understanding the Ranking Algorithm</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/37.html"><span style="color: black;">Lesson 37:</span> <span style="color: #2695eb;">What is a Product Launch?</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/38.html"><span style="color: black;">Lesson 38:</span> <span style="color: #2695eb;">Overview of Different Methods</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/39.html"><span style="color: black;">Lesson 39:</span> <span style="color: #2695eb;">My Successful Launch Formula</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/40.html"><span style="color: black;">Lesson 40:</span> <span style="color: #2695eb;">How to Calculate Giveaway Programs</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/41.html"><span style="color: black;">Lesson 41:</span> <span style="color: #2695eb;">Creating Discount Codes</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/42.html"><span style="color: black;">Lesson 42:</span> <span style="color: #2695eb;">My Secret Weapon for Ranking</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/43.html"><span style="color: black;">Lesson 43:</span> <span style="color: #2695eb;">Creating Facebook Giveaway Ads</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/44.html"><span style="color: black;">Lesson 44:</span> <span style="color: #2695eb;">Tracking Keyword Rankings Post-Launch</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/45.html"><span style="color: black;">Lesson 45:</span> <span style="color: #2695eb;">BONUS: Discovering High-Demand, Low-Competition Search Terms</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/46.html"><span style="color: black;">Lesson 46:</span> <span style="color: #2695eb;">BONUS: Building a Free Launch Email List</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/47.html"><span style="color: black;">Lesson 47:</span> <span style="color: #2695eb;">30 First Page Rankings in 21 Days</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/48.html"><span style="color: black;">Lesson 48:</span> <span style="color: #2695eb;">Overview of Sponsored Ads</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/blog-post_226.html"><span style="color: black;">Lesson 49:</span> <span style="color: #2695eb;">Match Types</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/50.html"><span style="color: black;">Lesson 50:</span> <span style="color: #2695eb;">What Do the Metrics Mean?</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/51.html"><span style="color: black;">Lesson 51:</span> <span style="color: #2695eb;">Creating Automatic Campaigns</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/52.html"><span style="color: black;">Lesson 52:</span> <span style="color: #2695eb;">Creating Manual Campaigns</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/53.html"><span style="color: black;">Lesson 53:</span> <span style="color: #2695eb;">Negative Keywords and Campaign Optimization</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/54.html"><span style="color: black;">Lesson 54:</span> <span style="color: #2695eb;">Seller Central Summary</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/55.html"><span style="color: black;">Lesson 55:</span> <span style="color: #2695eb;">Brand Registry</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/56.html"><span style="color: black;">Lesson 56:</span> <span style="color: #2695eb;">Collecting Real Customer Information</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/57.html"><span style="color: black;">Lesson 57:</span> <span style="color: #2695eb;">MBS SellerMail - Follow-Up Email Sequence for Reviews</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/58.html"><span style="color: black;">Lesson 58:</span> <span style="color: #2695eb;">Cash Flow Realities</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/59.html"><span style="color: black;">Lesson 59:</span> <span style="color: #2695eb;">Cash Flow Solutions</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/60.html"><span style="color: black;">Lesson 60:</span> <span style="color: #2695eb;">Buy Now, Pay Later</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/61.html"><span style="color: black;">Lesson 61:</span> <span style="color: #2695eb;">When to Reorder</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/62.html"><span style="color: black;">Lesson 62:</span> <span style="color: #2695eb;">What to Do When Out of Stock</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/63.html"><span style="color: black;">Lesson 63:</span> <span style="color: #2695eb;">Everyone’s Favorite Topic</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/64.html"><span style="color: black;">Lesson 64:</span> <span style="color: #2695eb;">Secrets to Supporting Your Business</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed;"><b><span style="font-size: 18px;"><br /></span><span style="font-size: 18px;"><a href="https://you1max.blogspot.com/2025/04/65.html"><span style="color: black;">Lesson 65:</span> <span style="color: #2695eb;">Where to Build Your Brand</span></a></span></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed; font-size: 18px;"><b><br /></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed; font-size: 18px;"><b>Resource:&nbsp;<a href="https://you1max.blogspot.com/2025/04/66.html"><span style="color: #2695eb;">MASTER LIST OF RESOURCES</span></a></b></span></div><div style="text-align: left;"><span style="font-family: Roboto Condensed; font-size: 18px;"><br /></span></div><div style="text-align: center;"><span style="color: #800180; font-family: Roboto Condensed; font-size: 18px;">Wishing you good health and success! ♥️</span></div>










  </div>
</div>

<!-- SCRIPT NGÀY HÔM NAY -->
<script>
  const dateEl = document.getElementById("dsh-current-date");
  if (dateEl) {
    const today = new Date();
    const options = { year: 'numeric', month: 'long', day: 'numeric' };
    const formattedDate = today.toLocaleDateString('en-GB', options);
    dateEl.textContent = `Today is ${formattedDate}.`;
  }
</script>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
          </b:widget>
          <b:widget id='HTML3' locked='false' title='BANNER UNDER YOU1MAX' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<style>
/* RESET VÀ TƯƠNG THÍCH */
#course-widget {
  all: initial;
  font-family: Arial, sans-serif;
}

#course-widget *, #course-widget *::before, #course-widget *::after {
  box-sizing: border-box;
}

/* BANNER */
#course-widget #cw-bottom-banner {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background: #0d4456;
  color: #fff;
  text-align: center;
  padding: 7px 10px;
  font-size: 16px;
  font-weight: bold;
  border-radius: 30px 30px 0 0;
  box-shadow: 0 -2px 8px rgba(0,0,0,0.2);
  cursor: pointer;
  z-index: 10000;
  transform: translateY(100%);
  transition: transform 0.5s ease, background 0.5s ease;
  will-change: transform;
}

#course-widget #cw-bottom-banner.show {
  transform: translateY(0);
}

#course-widget #cw-bottom-banner.hide {
  transform: translateY(100%);
}

#course-widget #cw-bottom-banner-spacer {
  height: 0;
  transition: height 0.5s ease;
}

#course-widget #cw-bottom-banner-spacer.show {
  height: 55px;
}

/* OVERLAY */
#course-widget #cw-overlay {
  position: fixed;
  top: 90px;
  left: 0;
  width: 100%;
  height: calc(100vh - 90px);
  background: #ffffff;
  z-index: 9999;
  transform: translateY(100%);
  transition: transform 0.5s ease;
  display: flex;
  flex-direction: column;
  box-sizing: border-box;
  will-change: transform;
  overflow-y: auto; /* Cho phép cuộn toàn bộ nội dung nếu vượt quá chiều cao */
}

#course-widget #cw-overlay.show {
  transform: translateY(0);
}

#course-widget #cw-overlay-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
  padding-bottom: 250px; /* Thêm dòng này để tránh bị nút Close che nội dung */
  max-width: 600px;
  width: 100%;
  margin: 0 auto;
}

html.overlay-active, body.overlay-active {
  position: fixed;
  overflow: hidden;
  height: 100vh;
  width: 100%;
  overscroll-behavior: none;
  touch-action: none;
}

/* NÚT ĐÓNG */
#course-widget #cw-close-overlay {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background: #cc0000;
  color: #fff;
  border: none;
  padding: 15px;
  font-size: 18px;
  font-weight: bold;
  border-top: 1px solid #ccc;
  cursor: pointer;
  z-index: 10001;
  transform: translateY(100%);
  transition: transform 0.5s ease;
  will-change: transform;
}

#course-widget #cw-close-overlay.show {
  transform: translateY(0);
}

/* HƯỚNG DẪN */
#course-widget .instructions-placeholder {
  font-size: 15px;
  text-align: left !important;
  margin-bottom: 15px;
  width: 100%;
}

/* Ô NỘI DUNG */
#course-widget .content-box {
  width: 100%;
  min-height: 200px;
  max-height: 400px;
  max-width: 100%;
  background: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 15px;
  font-size: 16px;
  line-height: 1.5;
  overflow-y: auto;
  box-sizing: border-box;
  outline: none;
  color: #222;
}

#course-widget .content-box:focus {
  border-color: #888;
}

#course-widget .content-box a {
  color: #0000EE;
  text-decoration: none; /* Xóa gạch ngang dưới link */
  cursor: pointer;
}

/* ĐẾM KÝ TỰ */
#course-widget .char-count {
  font-size: 14px;
  color: #666;
  text-align: right;
  margin-bottom: 10px;
  width: 100%;
}

/* NÚT HÀNH ĐỘNG */
#course-widget .action-buttons {
  display: flex;
  gap: 10px;
  justify-content: center;
  width: 100%;
}

/* THÔNG BÁO SAO CHÉP */
#course-widget .copy-message {
  display: none;
  color: #cc0000;
  font-size: 14px;
  text-align: center;
  opacity: 0;
  transition: opacity 0.5s ease;
  width: 100%;
}

#course-widget .copy-message.show {
  display: block;
  opacity: 1;
}

#course-widget .copy-btn, #course-widget .change-btn {
  padding: 10px 20px;
  font-size: 16px;
  font-weight: bold;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.3s ease;
}

#course-widget .copy-btn {
  background: #4CAF50;
  color: white;
}

#course-widget .copy-btn:hover {
  background: #45a049;
}

#course-widget .change-btn {
  background: #888888;
  color: white;
}

#course-widget .change-btn:hover {
  background: #777777;
}

/* HIỆU ỨNG CẢM ỨNG */
#course-widget button:active {
  transform: scale(0.97);
}
</style>

<div id="course-widget">
  <div id="cw-bottom-banner" role="button" aria-label="Gift this course" tabindex="0">
    <div style="text-align: center;"><span style="color: #f6f009; font-size: medium;"><b>Click here to gift this course to someone you care about ♥️</b></span></div>
  </div>
  <div id="cw-bottom-banner-spacer"></div>

  <div id="cw-overlay">
    <div id="cw-overlay-content">
      <div class="instructions-placeholder">







<p class="whitespace-normal break-words"><span style="font-family: Roboto Condensed; font-size: large;">Click the '<b>Copy</b>' button to copy the content and course link in the box below, then gift it to your loved ones via email or social media (Facebook, X, Messenger, etc.).</span></p><p>
</p><p class="whitespace-normal break-words"><span style="font-family: Roboto Condensed; font-size: large;"><span style="color: #cc0000;"><b>Note:</b></span> If the link doesn't work, click '<b>Change link</b>' to get a new link and resend it.</span></p>





</div>
      
      <div class="content-box" id="cw-random-content" tabindex="-1"></div>
      <div class="char-count" id="cw-char-count">0/500</div>
      <div class="action-buttons">
        <button class="copy-btn" id="cw-copy-btn" aria-label="Copy content" tabindex="0">Copy</button>
        <button class="change-btn" id="cw-change-btn" aria-label="Change content and link" tabindex="0">Change link</button>
      </div>
      <br />
      <div class="copy-message" id="cw-copy-message">Content has been copied! ✅</div>
    </div>
  </div>
  <button id="cw-close-overlay" role="button" aria-label="Close overlay" tabindex="0">Close</button>
</div>

<script>
(function () {
let scrollPosition = 0; // Khai báo biến scrollPosition
  // Hàm ngăn cuộn
  function preventScroll(e) {
    e.preventDefault();
    e.stopPropagation();
  }


const texts = [
  "📘 Wishing you a meaningful and valuable learning experience. Access to 65 detailed video lessons. Total learning time spans 11 hours – covering basic to advanced topics. All study materials are included and fully accessible. No payment needed – learn anytime at your own pace. ",
  "🧠 Hope this serves as a helpful learning resource for you. Features 65 high-quality lecture videos. Spans 11 hours of learning from foundational to expert level. Complete textbooks, guides, and notes available. Begin your journey today. ",
  "📚 May you gain valuable insights from this course. Comes with 65 full-length HD lectures. Offers 11 hours of structured content for all levels. Full access to all learning resources. Just sign in and begin: ",
  "📖 Hope this course brings value to your learning journey. Access 65 high-quality lecture videos. Total learning time is 11 hours – covering basic to advanced topics. Includes all necessary tools and supporting documents. Start learning now – no cost required: ",
  "🌐 Wishing you an effective learning experience with great benefits from this course. You'll get 65 full lecture videos. A total of 11 hours of training – from basic to advanced. All study materials are included and fully accessible. Begin your journey today: ",
  "📌 This course is designed to support your learning needs. Features 65 high-definition lecture videos. Learn over 11 hours – from beginner to expert level. Provides complete supplementary learning materials. No payment needed – learn anytime at your own pace: ",
  "📊 Hope you discover many interesting things through this course. Includes 65 detailed video lessons. Spans 11 hours of structured content. All learning tools are available right away. Start learning now: ",
  "📘 May the content serve as a helpful resource for you. Access 65 full HD videos. Training lasts 11 hours – from basics to specialization. All documents and guides are included. No cost involved: ",
  "🎓 Hope this course is useful to you. You’ll find 65 full-length lecture videos. Designed for learners at every stage – from beginner to advanced. All learning resources are provided. Begin your journey: ",
  "📚 Wishing this course offers something truly beneficial to you. Get 65 high-quality video lessons. Over 11 hours of learning content available. Full access to essential materials and tools. Start anytime – no fees involved: ",
  "📖 Hope these materials contribute positively to your learning process. Enjoy 65 full HD lecture videos. Learning path covers 11 hours – from fundamental to advanced. All supporting documents are included. Begin learning now: ",
  "🧩 This course is designed to support your learning needs. Includes 65 engaging video lessons. A total of 11 hours of structured training. Full access to all supporting materials. Just sign up and begin – no cost: ",
  "📘 Hope you find what you're looking for in this course. Features 65 high-definition learning videos. Covers 11 hours of training from basics to advanced. Complete textbooks and guides included. Start whenever ready: ",
  "🎯 Wishing you a meaningful and valuable learning experience. Access 65 full-length HD lectures. You’ll spend 11 hours mastering new skills. All necessary documents and tools available. Begin your journey: ",
  "🌐 Hope this serves as a helpful learning resource for you. Comes with 65 high-quality video lessons. Total duration is 11 hours – from beginner to expert. Includes all learning tools and materials. Start learning now: ",
  "📌 May you gain valuable insights from this course. You’ll get 65 full lecture videos. Training spans 11 hours – covering basic to professional topics. Full access to all educational resources. No cost – start anytime: ",
  "📓 Hope this course brings value to your learning journey. Features 65 HD-quality video lessons. A total of 11 hours of content – easy to follow. Supports all learner levels. No fees required: ",
  "📈 This course is designed to support your learning needs. Includes 65 detailed lecture videos. Offers 11 hours of progressive learning. All supporting materials included. Start learning now: ",
  "📘 Hope you discover many interesting things through this course. Access 65 full HD videos. From basics to advanced topics in 11 hours. Full access to all learning tools. No charges involved: ",
  "🎯 Wishing you an effective learning experience with great benefits from this course. You'll enjoy 65 well-produced lecture videos. 11 hours of guided instruction included. All resources available online. Start today – no cost required: ",
  "📚 Hope this course is useful to you. Learn with 65 full lecture videos. Build your knowledge across 11 hours of training. All materials are easily accessible. Begin anytime: ",
  "📖 May the content serve as a helpful resource for you. Includes 65 high-quality HD videos. Spans 11 hours – from fundamentals to expertise. All supporting documents included. Start right away: ",
  "🧩 Hope you find what you're looking for in this course. You'll get 65 full-length HD lessons. Designed to guide you from beginner to advanced. All study tools are provided. Sign in and start learning: ",
  "📘 Wishing you an effective learning experience with great benefits from this course. Features 65 engaging video lectures. Total learning time: 11 hours – from basics to mastery. All materials are integrated into the program. Start learning now – no cost: ",
  "📝 This course is designed to support your learning needs. Includes 65 high-definition learning videos. 11 hours of training tailored for all levels. All essential documents and tools included. No payment needed: ",
  "📌 Hope this course brings value to your learning journey. Access 65 full HD lecture videos. Progress through 11 hours of structured content. Full access to all learning resources. Start anytime: ",
  "🎯 Hope this serves as a helpful learning resource for you. Features 65 engaging video lessons. From beginner to expert in 11 hours. All supporting materials included. No fees – just sign in and begin: ",
  "📘 May you gain valuable insights from this course. Includes 65 full lecture videos. 11 hours of training content available. Complete set of learning resources provided. No upfront cost: ",
  "📚 Wishing you a meaningful and valuable learning experience. Access 65 high-quality HD videos. Learn over 11 hours – covering all skill levels. All tools and materials included. Begin your journey: ",
  "📖 Hope you find what you're looking for in this course. You'll get 65 full-length video lectures. 11-hour curriculum built for real-world application. Full access to all learning resources. Start learning now: ",
  "🎯 Hope this course is useful to you. Features 65 HD video lessons. Structured for 11 hours of learning – from basic to advanced. All necessary tools and guides included. No cost required: ",
  "📘 Wishing this course offers something truly beneficial to you. Access 65 high-quality learning videos. Training spans 11 hours – covering core to advanced topics. Complete textbooks and notes included. Start learning now – no fees: ",
  "📚 May the content serve as a helpful resource for you. Features 65 detailed lecture videos. Designed for 11 hours of learning – suitable for all levels. Full access to supporting materials. Begin whenever ready: ",
  "📖 Hope this serves as a helpful learning resource for you. You’ll explore 65 full HD videos. 11 hours of learning – from foundation to mastery. All learning tools and materials included. Start today – no cost involved: ",
  "📌 Hope you discover many interesting things through this course. Includes 65 high-definition lecture videos. Designed for 11 hours of structured learning. All essential resources provided. No restrictions: ",
  "📘 This course is designed to support your learning needs. Access 65 full-length HD videos. 11-hour learning path for all levels. All textbooks and guides included. No upfront payment: ",
  "🎯 Hope you find what you're looking for in this course. Features 65 high-quality video lectures. Training lasts 11 hours – from basic to advanced. All learning resources are available. Start learning now – no cost required: ",
  "🌐 Wishing this course brings value to your learning journey. You’ll watch 65 full HD videos. Over 11 hours of guided instruction. All necessary documents and tools included. Start anytime: ",
  "📚 Hope this course is useful to you. Learn with 65 full lecture videos. A total of 11 hours of learning – from beginner to expert. All study materials are available. Start learning now – no cost involved: ",
  "📖 May you gain valuable insights from this course. Includes 65 high-definition learning videos. Designed for 11 hours of training. All learning tools are integrated into the system. No fees: ",
  "📌 Hope this serves as a helpful learning resource for you. Access 65 full HD video lessons. 11 hours of learning content available. All supporting documents and tools included. No upfront costs: ",
  "📘 Wishing you a meaningful and valuable learning experience. Features 65 high-quality HD lecture videos. Curriculum spans 11 hours – from beginner to expert. All learning resources are included. Start learning now – no cost required: ",
  "🎯 Hope this course brings value to your learning journey. You'll find 65 full-length HD videos. 11 hours of content from basic to advanced. All materials are easily accessible. No fees involved: ",
  "📚 May the content serve as a helpful resource for you. Includes 65 high-definition video lectures. Designed for 11 hours of training. All learning tools are available. Start learning now: ",
  "📖 Hope you find what you're looking for in this course. Access 65 full HD video lessons. 11-hour structured program – from basic to advanced. All supporting documents and guides included. No charges: ",
  "📌 Hope this serves as a helpful learning resource for you. Features 65 full lecture videos. Designed for 11 hours of progressive learning. All tools and materials included. Start anytime: ",
  "📘 Wishing you an effective learning experience with great benefits from this course. Learn with 65 full HD lectures. 11 hours of guided instruction. All learning materials are included. No cost involved: ",
  "🎯 Hope you discover many interesting things through this course. Includes 65 high-quality HD videos. 11 hours of learning content available. All supporting tools are accessible. No fees: ",
  "📚 This course is designed to support your learning needs. You’ll get 65 full lecture videos. Covers 11 hours of learning – from basic to advanced. All essential materials are included. Start learning now – no cost required: ",
  "📖 Hope this course brings value to your learning journey. Features 65 HD-quality video lessons. 11-hour structured program – for all levels. All learning resources are available. Start whenever ready: ",
  "📌 Hope you find this course useful to you. Learn with 65 full HD lectures. 11 hours of comprehensive learning content. All documents and tools included. No fees involved: ",
  "📘 May the content serve as a helpful resource for you. Access 65 high-definition lecture videos. Training spans 11 hours – from beginner to expert. All learning tools and guides included. Start learning now – no cost required: ",
  "🎯 Hope this serves as a helpful learning resource for you. Includes 65 full-length HD videos. 11-hour learning plan – from basic to advanced. All supporting materials included. No payment needed: ",
  "📚 Wishing you a meaningful and valuable learning experience. You’ll find 65 engaging video lessons. 11 hours of content – built for flexible learning. All necessary tools and guides included. Start learning now: ",
  "📖 Hope this course offers something truly beneficial to you. Features 65 full HD lecture videos. 11-hour learning journey – from basics to advanced. All learning resources available. No charges: ",
  "📌 Hope you discover many interesting things through this course. Includes 65 high-quality video lessons. 11 hours of structured training. All materials are integrated into the program. Start learning now: ",
  "📘 May you gain valuable insights from this course. Access 65 full-length HD videos. Designed for 11 hours of practical learning. All documents and tools included. No cost involved: ",
  "🎯 Hope this course supports your learning goals. Features 65 high-definition lecture videos. 11-hour learning path – from beginner to expert. All supporting materials included. Start learning now – no cost required: ",
  "📚 Wishing you a meaningful and valuable learning experience. You’ll find 65 engaging video lessons. 11 hours of content – built for flexible learning. All necessary tools and guides included. Start learning now: ",
  "📖 Hope this course is useful to you. Learn with 65 full HD lecture videos. 11-hour learning path – from beginner to expert. All learning resources are accessible. No cost required: ",
  "📌 Hope this serves as a helpful learning resource for you. Includes 65 high-quality HD video lessons. 11-hour learning plan – for all levels. All supporting materials are available. Begin whenever ready: ",
  "📘 Wishing this course brings value to your learning journey. You’ll explore 65 full HD videos. 11 hours of progressive training. All supporting tools and guides available. No charges: ",
  "🎯 Hope you find what you're looking for in this course. Learn with 65 full HD videos. 11 hours of learning from basic to advanced. All documents and resources included. Start learning now – no cost required: ",
  "📚 May the content serve as a helpful resource for you. Access 65 high-quality HD lectures. 11-hour structured program – for all levels. All learning tools are available. No payment needed: ",
  "📖 Hope you discover many interesting things through this course. Learn with 65 detailed video lessons. 11 hours of guided instruction. All supporting materials included. Start learning now – no cost involved: ",
  "📌 Hope this course supports your learning goals. Includes 65 full HD videos. Designed for 11 hours of training. All essential resources provided. Begin today: ",
  "📘 Wishing you a meaningful and valuable learning experience. You’ll get 65 high-definition video lectures. 11 hours of learning content available. All tools and guides included. No upfront fees: ",
  "🎯 Hope this serves as a helpful learning resource for you. Access 65 full-length HD videos. 11-hour learning path – from basic to advanced. All learning materials are integrated. Start learning now – no cost required: ",
  "📚 Hope this course brings value to your learning journey. Features 65 high-quality video lessons. 11 hours of content – suitable for all levels. All supporting documents and tools included. No cost required: ",
  "📖 May you gain valuable insights from this course. Includes 65 full HD lecture videos. Designed for 11 hours of training. All learning tools are available. Start learning now – no fees involved: ",
  "📌 Hope you find what you're looking for in this course. Learn with 65 detailed video lectures. 11-hour learning path – from beginner to expert. All materials are fully integrated. No cost required: ",
  "📘 Wishing this course offers something truly beneficial to you. You’ll have access to 65 full HD videos. 11 hours of guided instruction. All tools and guides included. Start learning now – no cost involved: ",
  "🎯 Hope this serves as a helpful learning resource for you. Includes 65 high-quality HD video lessons. 11-hour learning plan – for all levels. All supporting materials are available. Begin whenever ready: ",
  "📚 Hope this course is useful to you. Features 65 full HD lecture videos. 11 hours of content – from basics to advanced. All learning tools and guides included. Start learning now: ",
  "📖 Wishing you a meaningful and valuable learning experience. You’ll get 65 full HD video lessons. 11-hour training path – from foundational to expert. All supporting resources provided. No upfront cost: ",
  "📌 Hope this course supports your learning goals. Includes 65 full HD videos. Designed for 11 hours of training. All essential resources provided. Begin today: "
];



const links = [
"https://samesame01111990.github.io/you1max",
"https://bit.ly/trump222",
"https://bit.ly/biden222"
];

  let lastTextIndex = -1;
  let lastLinkIndex = -1;

  function getRandomContent() {
    let textIndex, linkIndex;
    do {
      textIndex = Math.floor(Math.random() * texts.length);
    } while (textIndex === lastTextIndex && texts.length > 1);
    lastTextIndex = textIndex;

    do {
      linkIndex = Math.floor(Math.random() * links.length);
    } while (linkIndex === lastLinkIndex && links.length > 1);
    lastLinkIndex = linkIndex;

    return `${texts[textIndex]}<a href="${links[linkIndex]}" target="_blank" rel="noopener noreferrer">${links[linkIndex]}</a>`;
  }

  function displayRandomContent() {
    const content = getRandomContent();
    const box = document.getElementById("cw-random-content");
    box.innerHTML = content;
    updateCharCount(box.textContent.length);

    const links = box.querySelectorAll("a");
    links.forEach(link => {
      link.setAttribute("contenteditable", "false");
      link.addEventListener("click", function (e) {
        e.stopPropagation();
        window.open(this.href, "_blank");
      });
    });
  }

  function updateCharCount(len) {
    document.getElementById("cw-char-count").textContent = `${len}/500`;
  }

  function limitCharacters() {
    const box = document.getElementById("cw-random-content");
    let text = box.textContent;
    const links = box.querySelectorAll("a");

    if (text.length > 500) {
      let contentBeforeLink = box.innerHTML.split("<a")[0].trim();
      let linkHtml = links.length > 0 ? `<a href="${links[0].href}" target="_blank" rel="noopener noreferrer" contenteditable="false">${links[0].href}</a>` : "";
      if (contentBeforeLink.length + linkHtml.length > 500) {
        contentBeforeLink = contentBeforeLink.substring(0, 500 - linkHtml.length);
      }
      box.innerHTML = contentBeforeLink + linkHtml;
      const range = document.createRange();
      const selection = window.getSelection();
      range.selectNodeContents(box);
      range.collapse(false);
      selection.removeAllRanges();
      selection.addRange(range);
    }
    updateCharCount(box.textContent.length);
  }

  function showCopyMsg() {
    const msg = document.getElementById("cw-copy-message");
    msg.classList.add("show");
    setTimeout(() => msg.classList.remove("show"), 7000);
  }

  function fallbackCopy(textToCopy) {
    const textarea = document.createElement("textarea");
    textarea.value = textToCopy;
    document.body.appendChild(textarea);
    textarea.select();
    try {
      document.execCommand("copy");
      showCopyMsg();
    } catch {
      alert("Copy not supported on this browser.");
    }
    document.body.removeChild(textarea);
  }

  window.addEventListener("load", function () {
    const banner = document.getElementById("cw-bottom-banner");
    const spacer = document.getElementById("cw-bottom-banner-spacer");
    if (!banner || !spacer) return;

    banner.style.background = getRandomColor();
    setTimeout(() => {
      banner.classList.add("show");
      spacer.classList.add("show");
    }, 10);
    setInterval(() => {
      if (banner.classList.contains("show")) {
        banner.style.background = getRandomColor();
      }
    }, 5000);
  });

  const bannerColors = ['#0d4456', '#551b8d', '#05386d', '#1a3c34'];

  function getRandomColor() {
    return bannerColors[Math.floor(Math.random() * bannerColors.length)];
  }

  document.getElementById("cw-bottom-banner").addEventListener("click", function () {
    scrollPosition = window.pageYOffset || document.documentElement.scrollTop;

    document.getElementById("cw-bottom-banner").classList.replace("show", "hide");
    document.getElementById("cw-overlay").classList.add("show");
    document.getElementById("cw-close-overlay").classList.add("show");
    document.body.classList.add("overlay-active");
    document.documentElement.classList.add("overlay-active");
    displayRandomContent();
  });

  document.getElementById("cw-bottom-banner").addEventListener("keypress", function (e) {
    if (e.key === "Enter") {
      this.click();
    }
  });

  document.getElementById("cw-close-overlay").addEventListener("click", function () {
    document.getElementById("cw-overlay").classList.remove("show");
    document.getElementById("cw-bottom-banner").classList.replace("hide", "show");
    document.getElementById("cw-close-overlay").classList.remove("show");
    document.body.classList.remove("overlay-active");
    document.documentElement.classList.remove("overlay-active");

    setTimeout(() => {
      window.scrollTo(0, scrollPosition);
    }, 100);

    const box = document.getElementById("cw-random-content");
    box.blur();
    if (box.hasAttribute("contenteditable")) {
      box.removeAttribute("contenteditable");
    }
  });

  document.getElementById("cw-close-overlay").addEventListener("keypress", function (e) {
    if (e.key === "Enter") {
      this.click();
    }
  });

  const contentBox = document.getElementById("cw-random-content");
  contentBox.addEventListener("click", function (e) {
    if (e.target.tagName !== "A" && !this.hasAttribute("contenteditable")) {
      this.setAttribute("contenteditable", "true");
      this.focus();
    }
  });

  contentBox.addEventListener("input", limitCharacters);

  contentBox.addEventListener("blur", function () {
    this.blur();
    if (this.hasAttribute("contenteditable")) {
      this.removeAttribute("contenteditable");
    }
  });

  contentBox.addEventListener("paste", function (e) {
    e.preventDefault();
    const text = (e.clipboardData || window.clipboardData).getData("text");
    document.execCommand("insertText", false, text);
    limitCharacters(); // Cập nhật giới hạn sau khi dán
  });

  const changeBtn = document.getElementById("cw-change-btn");
  if (changeBtn) {
    changeBtn.addEventListener("click", function (e) {
      e.preventDefault();
      const box = document.getElementById("cw-random-content");
      if (/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
        box.blur();
        if (box.hasAttribute("contenteditable")) {
          box.removeAttribute("contenteditable");
        }
      }
      displayRandomContent();
    });

    changeBtn.addEventListener("keypress", function (e) {
      if (e.key === "Enter") {
        this.click();
      }
    });
  }

  const copyBtn = document.getElementById("cw-copy-btn");
  if (copyBtn) {
    copyBtn.addEventListener("click", function () {
      const box = document.getElementById("cw-random-content");
      const textToCopy = box.innerText; // Sử dụng innerText để loại bỏ khoảng trắng ẩn
      if (navigator.clipboard && window.isSecureContext) {
        navigator.clipboard.writeText(textToCopy)
          .then(() => showCopyMsg())
          .catch(() => fallbackCopy(textToCopy));
      } else {
        fallbackCopy(textToCopy);
      }
    });

    copyBtn.addEventListener("keypress", function (e) {
      if (e.key === "Enter") {
        this.click();
      }
    });
  }
})();
</script>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>
    </header>
  </b:if>

  <main class='content'>
    <b:section id='main' showaddelement='true'>
      <b:widget id='HTML4' locked='false' title='BACK TO LESSONS BUTTON - you1max' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'><![CDATA[<style>
  .post-only-box {
    display: none;
    opacity: 0;
    transition: opacity 0.3s ease;
  }
  .post-only-box.visible {
    display: block;
    opacity: 1;
  }
</style>

<div class="post-only-box">





<br />


<!-- NÚT "BACK TO LESSON LIST" -->
<div class="button-container">
    <a href="https://you1max.blogspot.com" class="custom-back-button">Back to lesson list</a>
</div>

<!-- CSS -->
<style>
    .button-container {
        text-align: center;
        margin: 0;
    }

    .custom-back-button {
        display: inline-block;
        background: #0b7b87 !important; /* Đổi màu nền nút ở đây */
        color: #fff !important; /* Đổi màu chữ nút ở đây */
        padding: 5px 22px; /* Kích cỡ nút (đổi khoảng cách trên/dưới và trái/phải) */
        border: none; /* Bỏ viền nút */
        border-radius: 8px; /* Bo tròn đều 4 góc nút */
        font-size: 18px; /* Đổi kích cỡ chữ ở đây */
        font-weight: bold;
        text-decoration: none;
        transition: transform 0.2s ease-out, box-shadow 0.2s ease-out;
        animation: scalePulse 2s ease-in-out 2; /* Hiệu ứng nhấp nhô (đổi số lần nhấp nhô ở số 2) */
    }

    a.custom-back-button:link,
    a.custom-back-button:visited {
        color: #000; /* Giữ màu chữ đen trong trạng thái link và visited */
        text-decoration: none; /* Ngăn gạch chân trong trạng thái link và visited */
    }

    a.custom-back-button:hover {
        color: #000; /* Giữ màu chữ đen khi rê chuột */
        text-decoration: none; /* Ngăn gạch chân khi rê chuột */
        transform: scale(1.05);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    a.custom-back-button:active {
        color: #000; /* Giữ màu chữ đen khi bấm */
        text-decoration: none; /* Ngăn gạch chân khi bấm */
    }

    @keyframes scalePulse {
        0%, 100% {
            transform: scale(1);
        }
        50% {
            transform: scale(1.1);
        }
    }
</style>





</div>

<script>
  // Hiển thị tiện ích chỉ trên trang bài đăng Blogger (URL dạng /YYYY/MM/post-title.html)
  document.addEventListener('DOMContentLoaded', () => {
    const isPostPage = window.location.pathname.match(/^\/\d{4}\/\d{2}\/[^/]+\.html$/);
    if (isPostPage) {
      const boxes = document.querySelectorAll('.post-only-box');
      boxes.forEach(box => box.classList.add('visible'));
    }
  });
</script>]]></b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
      </b:widget>
      <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='showDateHeader'>false</b:widget-setting>
          <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='showShareButtons'>false</b:widget-setting>
          <b:widget-setting name='authorLabel'>You1Max</b:widget-setting>
          <b:widget-setting name='showCommentLink'>false</b:widget-setting>
          <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='showAuthor'>false</b:widget-setting>
          <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
          <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='reactionsLabel'/>
          <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
          <b:widget-setting name='style.layout'>1x1</b:widget-setting>
          <b:widget-setting name='showLabels'>false</b:widget-setting>
          <b:widget-setting name='showLocation'>false</b:widget-setting>
          <b:widget-setting name='showTimestamp'>false</b:widget-setting>
          <b:widget-setting name='postsPerAd'>1</b:widget-setting>
          <b:widget-setting name='showBacklinks'>false</b:widget-setting>
          <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='showInlineAds'>false</b:widget-setting>
          <b:widget-setting name='showReactions'>false</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:loop values='data:posts' var='post'>
            <div class='post-outer'>
              <h1 class='visually-hidden'><data:post.title/></h1>
              <div class='post-body'><data:post.body/></div>
            </div>
          </b:loop>
        </b:includable>
        <b:includable id='aboutPostAuthor'>
  <div class='author-name'>
    <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
      <span>
        <data:post.author.name/>
      </span>
    </a>
  </div>
  <div>
    <span class='author-desc'>
      <data:post.author.aboutMe/>
    </span>
  </div>
</b:includable>
        <b:includable id='addComments'>
  <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:message name='messages.postAComment'/>
  </a>
</b:includable>
        <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
        <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
        <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
        <b:includable id='commentAuthorAvatar'>
  <div class='avatar-image-container'>
    <img class='author-avatar' expr:src='data:comment.authorAvatarSrc' height='35' width='35'/>
  </div>
</b:includable>
        <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
        <b:includable id='commentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
        <b:includable id='commentFormIframeSrc' var='post'>
  <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
</b:includable>
        <b:includable id='commentItem' var='comment'>
  <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
    <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

    <div class='comment-block'>
      <div class='comment-author'>
        <b:if cond='data:comment.authorUrl'>
          <b:message name='messages.authorSaidWithLink'>
            <b:param expr:value='data:comment.author' name='authorName'/>
            <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
          </b:message>
        <b:else/>
          <b:message name='messages.authorSaid'>
            <b:param expr:value='data:comment.author' name='authorName'/>
          </b:message>
        </b:if>
      </div>
      <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
        <data:comment.body/>
      </div>
      <div class='comment-footer'>
        <span class='comment-timestamp'>
          <a expr:href='data:comment.url' title='comment permalink'>
            <data:comment.timestamp/>
          </a>
          <b:include data='comment' name='commentDeleteIcon'/>
        </span>
      </div>
    </div>
  </div>
</b:includable>
        <b:includable id='commentList' var='comments'>
  <div id='comments-block'>
    <b:loop values='data:comments' var='comment'>
      <b:include data='comment' name='commentItem'/>
    </b:loop>
  </div>
</b:includable>
        <b:includable id='commentPicker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threadedComments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
        <b:includable id='comments' var='post'>
  <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>

      <b:include name='commentsTitle'/>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <div class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
              <data:messages.oldest/>
            </a>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
              <data:messages.older/>
            </a>
          </b:if>

          <span class='comment-range-text'>
            <data:post.commentRangeText/>
          </span>

          <b:if cond='data:post.hasNewerLinks'>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
              <data:messages.newer/>
            </a>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
              <data:messages.newest/>
            </a>
          </b:if>
        </div>
      </b:if>

      <div class='footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <b:include data='post' name='addComments'/>
          </b:if>
        </b:if>
      </div>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
        <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
        <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
        <b:includable id='commentsTitle'>
  <h3 class='title'><data:messages.comments/></h3>
</b:includable>
        <b:includable id='defaultAdUnit'>
  <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:style='data:style ?: &quot;display: block;&quot;'>
    <b:attr cond='not data:blog.analytics4' expr:value='data:blog.analyticsAccountNumber' name='data-analytics-uacct'/>
  </ins>
  <script>
   (adsbygoogle = window.adsbygoogle || []).push({});
  </script>
</b:includable>
        <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
        <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
        <b:includable id='feedLinks'>
  <b:if cond='!data:view.isPost'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>
  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments and data:post.feedLinks'>
          <b:include data='post.feedLinks' name='feedLinksBody'/>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
        <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:messages.subscribeTo/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
        <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
        <b:includable id='googlePlusShare'>
</b:includable>
        <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
        <b:includable id='homePageLink'>
  <a class='home-link' expr:href='data:blog.homepageUrl'>
    <data:messages.home/>
  </a>
</b:includable>
        <b:includable id='iframeComments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
        <b:includable id='inlineAd' var='post'>
  <b:if cond='!data:view.isPreview'>
    <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
      <!-- Ad -->
      <div class='inline-ad'>
        <b:if cond='data:this.adCode != &quot;&quot;'>
          <data:this.adCode/>
        <b:else/>
          <b:include cond='data:this.adClientId or data:blog.adsenseClientId' name='defaultAdUnit'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <div class='inline-ad'>
      <div class='inline-ad-placeholder'>
        <span><b:message name='messages.adsGoHere'/></span>
      </div>
    </div>
  </b:if>
</b:includable>
        <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
        <b:includable id='nextPageLink'>
  <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:messages.olderPosts'>
    <data:messages.olderPosts/>
  </a>
</b:includable>
        <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
        <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
        <b:includable id='post' var='post'>
  <div class='post'>
    <b:include data='post' name='postMeta'/>
    <b:include data='post' name='postTitle'/>
    <b:include name='headerByline'/>
    <b:if cond='data:view.isSingleItem'>
      <b:include data='post' name='postBody'/>
    <b:else/>
      <b:include data='post' name='postBodySnippet'/>
      <b:include data='post' name='postJumpLink'/>
    </b:if>
    <b:include data='post' name='postFooter'/>
  </div>
</b:includable>
        <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
        <b:includable id='postBody' var='post'>
  <!-- If metaDescription is empty, use the post body as the schema.org description too, for G+/FB snippeting. -->
  <div class='post-body entry-content float-container' expr:id='&quot;post-body-&quot; + data:post.id'>
    <data:post.body/>
  </div>
</b:includable>
        <b:includable id='postBodySnippet' var='post'>
  <b:include data='post' name='postBody'/>
</b:includable>
        <b:includable id='postCommentsAndAd' var='post'>
  <article class='post-outer-container'>
    <!-- Post title and body -->
    <div class='post-outer'>
      <b:include data='post' name='post'/>
    </div>

    <!-- Comments -->
    <b:include cond='data:view.isSingleItem' data='post' name='commentPicker'/>

    <!-- Show ad inside post container, after comments, if single item. -->
    <b:include cond='data:view.isSingleItem and data:post.includeAd' data='post' name='inlineAd'/>
  </article>

  <!-- Show ad outside post container (between posts) for feed pages. -->
  <b:include cond='data:view.isMultipleItems and data:post.includeAd' data='post' name='inlineAd'/>
</b:includable>
        <b:includable id='postCommentsLink'>
  <b:if cond='data:view.isMultipleItems'>
    <span class='byline post-comment-link container'>
      <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
    </span>
  </b:if>
</b:includable>
        <b:includable id='postFooter' var='post'>
  <div class='post-footer'>
    <b:include name='footerBylines'/>
    <b:include data='post' name='postFooterAuthorProfile'/>
  </div>
</b:includable>
        <b:includable id='postFooterAuthorProfile' var='post'>
  <b:if cond='data:post.author.aboutMe and data:view.isPost'>
    <div class='author-profile'>
      <b:if cond='data:post.author.authorPhoto.url'>
        <img class='author-image' expr:src='data:post.author.authorPhoto.url' width='50px'/>
        <div class='author-about'>
          <b:include data='post' name='aboutPostAuthor'/>
        </div>
      <b:else/>
        <b:include data='post' name='aboutPostAuthor'/>
      </b:if>
    </div>
  </b:if>
</b:includable>
        <b:includable id='postHeader' var='post'>
  <b:include name='headerByline'/>
</b:includable>
        <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
        <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
        <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
        <b:includable id='postMeta' var='post'>
  <b:include data='post' name='postMetadataJSON'/>
</b:includable>
        <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://blogger.googleusercontent.com/img/b/U2hvZWJveA/AVvXsEgfMvYAhAbdHksiBA24JKmb2Tav6K0GviwztID3Cq4VpV96HaJfy0viIu8z1SSw_G9n5FQHZWSRao61M3e58ImahqBtr7LiOUS6m_w59IvDYwjmMcbq3fKW4JSbacqkbxTo8B90dWp0Cese92xfLMPe_tg11g/w1200/&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
        <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://blogger.googleusercontent.com/img/b/U2hvZWJveA/AVvXsEgfMvYAhAbdHksiBA24JKmb2Tav6K0GviwztID3Cq4VpV96HaJfy0viIu8z1SSw_G9n5FQHZWSRao61M3e58ImahqBtr7LiOUS6m_w59IvDYwjmMcbq3fKW4JSbacqkbxTo8B90dWp0Cese92xfLMPe_tg11g/h60/&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
        <b:includable id='postPagination'>
  <div class='blog-pager container' id='blog-pager'>
    <b:include cond='data:newerPageUrl' name='previousPageLink'/>
    <b:include cond='data:olderPageUrl' name='nextPageLink'/>
    <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
  </div>
</b:includable>
        <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
        <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
        <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
        <b:includable id='postTitle' var='post'>
  <a expr:name='data:post.id'/>
  <b:if cond='data:post.title != &quot;&quot;'>
    <h3 class='post-title entry-title'>
      <b:if cond='data:post.link or (data:post.url and data:view.url != data:post.url)'>
        <a expr:href='data:post.link ?: data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    </h3>
  </b:if>
</b:includable>
        <b:includable id='previousPageLink'>
  <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:messages.newerPosts'>
    <data:messages.newerPosts/>
  </a>
</b:includable>
        <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
        <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
        <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
        <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
        <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
        <b:includable id='threadedCommentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
        <b:includable id='threadedCommentJs' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
  <b:template-script inline='true' name='threaded_comments'/>
  <script type='text/javascript'>
    blogger.widgets.blog.initThreadedComments(
        <data:post.commentJso/>,
        <data:post.commentMsgs/>,
        <data:post.commentConfig/>);
  </script>
</b:includable>
        <b:includable id='threadedComments' var='post'>
  <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>

    <b:include name='commentsTitle'/>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threadedCommentJs'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threadedCommentForm'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
      <b:if cond='data:post.showManageComments'>
        <b:include data='post' name='manageComments'/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
        <b:includable id='tooltipCss'>
  <!-- LINT.IfChange -->
  <style>
    .post-body a.b-tooltip-container {
      position: relative;
      display: inline-block;
    }

    .post-body a.b-tooltip-container .b-tooltip {
      position: absolute;
      top: 100%;
      left: 50%;
      transform: translate(-20%, 1px);
      visibility: hidden;
      opacity: 0;
      z-index: 1;
      transition: opacity 0.2s ease-in-out;
    }

    .post-body a.b-tooltip-container .b-tooltip iframe {
      width: 200px;
      height: 198px;
      max-width: none;
      border: none;
      border-radius: 20px;
      box-shadow: 1px 1px 3px 1px rgba(0, 0, 0, 0.2);
    }

    .post-body a.b-tooltip-container:hover .b-tooltip {
      visibility: visible;
      opacity: 1;
    }
  </style>
  <!-- LINT.ThenChange(//depot/google3/java/com/google/blogger/b2/layouts/widgets/v2-style.css) -->
</b:includable>
      </b:widget>
      <b:widget id='HTML5' locked='false' title='SHOP 2 - You1max' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'><![CDATA[<style>
  .post-only-box {
    display: none;
    opacity: 0;
    transition: opacity 0.3s ease;
  }
  .post-only-box.visible {
    display: block;
    opacity: 1;
  }
</style>

<div class="post-only-box">





<style>
  * {
    box-sizing: border-box;
  }

  .center-container {
    display: flex;
    justify-content: center;
  }

  .embed-box {
    background-color: #f2f1dc !important;
    color: #444;
    padding: 1px 18px;
    width: 100%;
    max-width: 750px;
    border: none;
    border-radius: 25px;
    font-size: 15px;
    font-family: Helvetica, Arial, sans-serif;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: box-shadow 0.2s ease-out;
    text-align: left;
    margin-bottom: 20px;
  }

  .embed-box p {
    margin: 0;
    font-size: medium;
  }

  .embed-box p.title {
    text-align: center;
    color: #800180;
    font-size: large;
    font-weight: bold;
    margin-bottom: 10px;
  }

  .embed-box b.highlight {
    color: #800180;
  }
</style>

<div class="center-container">
  <div class="embed-box">







<p style="margin: 0px; text-align: center;">
  <span style="font-family: Roboto Condensed; font-size: 17px;"><b style="color: #800180;"><i><br /></i></b>
</span></p>
<p style="margin: 0px; text-align: center;">
  <span style="font-family: Roboto Condensed; font-size: 20px;"><b style="color: #800180;">Dear students,</b>
</span></p>
<p style="margin: 0px;">
  <span style="font-family: Roboto Condensed; font-size: 17px;">I’ve spent over three weeks carefully building this course to make it as detailed and comprehensive as possible, and I truly hope it proves helpful to you! At the moment, I’m working on a small project aimed at developing and delivering many more high-quality courses in the future. This project requires a significant investment of both time and resources. To help support this effort, I’ve launched a collection of fun and adorable designs. I’ll be regularly adding new patterns so you’ll always have fresh and exciting options to choose from. This collection is part of a fundraising initiative to help bring the project to life. I’d be so grateful if you could take a moment to browse the collection below. If you find something you like, please consider purchasing a product or two—as a gift for yourself, or for friends and family. Your support means a great deal and will go a long way toward making this vision a reality. <b style="color: #800180;">Thank you so much!</b></span>
</p>

    







  </div>
</div>

















<!doctype html><style>body{font-family:Arial,sans-serif;text-align:center;}.container{display:flex;flex-wrap:wrap;justify-content:center;}.content-box{background-color:#f9fbfd;color:#444;padding:18px;width:100%;max-width:750px;border:5px solid #71a3c1;border-radius:25px;text-align:left;font-size:15px;margin:0 auto 5px auto;box-sizing:border-box;transition:box-shadow 0.2s ease-out;}.content-box:hover{box-shadow:0 4px 8px rgba(0,0,0,0.2);}.content-box img{max-width:100%;height:auto;display:block;margin:0 auto;}.caption{text-align:center;margin-top:5px;}.caption a{color:#2196f3;text-decoration:none;}.caption b{font-family:Arial;}.caption i{color:black;}@media (min-width:751px){.content-box{width:31.33%;margin:1%;}}</style><div class="container" id="product-container"></div><script>const products=[



  {url:"https://teechip.com/thankyou-124?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-6318B64D3F0F-GS0-TC0-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgdXQwcE_tJLDsViAObbv5DLQ7n8uGZ_-WiQOAqn1UCT9r6kzNFpbBlKJLCGjaOMA7Wrhkf7eiLXRPx16z_piA988iAvZ2sXINBPtyG1TW_8jssQLnUk8RSqTzO_NjwhV0aYZZbCdIVgQXGn43OSnizyLNR9yURp-aUFE_xp49u4nVYrUB3Q8tUZ5DFeiG1=w512-h640"},
  {url:"https://teechip.com/thankyou-124?name=ceramic-mug-lifestyle-55&retailProductCode=F1BC1B0006F0A7-6318B64D3F0F-MSV2-TC1003-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiUnwf-rCLXtrqmKc5HrB4n3TsbAf51I4NKRyseNCz22FxPIyrJ1n_0n-FyYCZYrrkJ-SVfL5s1IAmrt_a9Zl09XiUX2ICbuWRQJTRt89TSC2UBAjbiBZVtpPGydKyanoiZIdbXtS6Drmr096oLdgpMK3qokCBv2UquP8Yjkk5j2-xV40cp3h73oL5RCnRZ=w512-h640"},
  {url:"https://teechip.com/thankyou-124?name=aos-car-seat-cover-set-2-pcs-ghosted-front-02&retailProductCode=F1BC1B0006F0A7-6318B64D3F0F-S3CSC1-YL1028-FGR",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi84aLYcihAYT4gxTt76MIQdk31Qr-Nw7s0TrawtMjXyhCBh6taszLxKg55ZOwupwQat3cCO-Kam5xU5NNBdLpGtyrHDbpuvaQYkpHhRTN7C7p01vCWBako4lP3cJE14Dw0iaILNm33YSNgy3Z5Y-aCIBunoZJ607AMlxhbVM0H2ggtpYtPbybCOPwfuxci=w512-h640"},
  {url:"https://teechip.com/thankyou-027?name=custom-crewneck-sweatshirt-lifestyle-front-130&retailProductCode=F1BC1B0006F0A7-2DEB33083B0E-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhfXxQCk-2cqsN6wCJ2fBlj9hAtgcWyEhHejO5Grh2TilW4-boT7NlGpNvIbkPoSMSQLRO6NndQoSWKpWtUKUEa-xXuR6vcN1Nc3zd0M5ZVfsOIqht3rrurt70BmwCW_t0qCtSzjIi5rNF9HOkw4v9cHuU0zQwmw7r7klr8al0MRotSPABHlTmqSdGgeDfA"},
  {url:"https://teechip.com/thankyou-046b?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-B4E9F3497A1B-GS2-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEglKw1JWhE8UHfK0U3HEGWo_7T7FyCXnvaEXRUUUlJluIttBnntt3jds662B-cFKYdw5NlhgeRYlHThmtWQhVuE0C4RJaD4OAPx94z9ihILasZla2dT_7hWdzczUv73pQalSM5OkR5EWHR_dABw0nJhHu4LZE4oA7Wz4Ia9rhF31FEUTrMJmRA5Nlx9nksh=w512-h640"},
  {url:"https://teechip.com/1000class-006?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-FF03725C7A0F-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjxghKgzvblf10dOZ_Mg5FL15STJcwqJJFtlSOfFdQ3b8-pw0-8PNh2ByyY3f1cc4JtsSaEzlRyZAm61yeu8anIDm_LpWUb9PeJHkXfv0_nub_2qmxjaW7scADGqZEuDm8fmOOK7GwVJdAy5gzsVufQzlkxTF_YkR1OfpAYvCMctlUho6wjOO0aUPHkO20F=w512-h640"},
  {url:"https://teechip.com/1000class-012?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-F687320C7A5E-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEh3uxXfWzIhp0oLlsK4iALS4eR_yRIUG1ZQzU5nCQUQfFFe3OaN7soaiKDhjiVTsztcSjKeyM824x9_y74oiZBbYzoSa2E4HaH8wh4fmWnlQSSi_GnXPGBwOh3ekVNTNbQaQnerXqaO0yBIcD_JuCAvy9pYmCtuASmfCLnnIYJrLLoWVOLaaMiAxuR2lhIX=w512-h640"},
  {url:"https://teechip.com/thankyou-037?name=apparel-classic-tshirt-lifestyle-front-97a&retailProductCode=F1BC1B0006F0A7-D41B37597A1B-GS1-TC0-ROY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhG73qZYwn1f9YUACC1aRD4UkwAQTb-YoZJlHD_2tSIDAy1CgBHc_Qjgn0Hbgivh5XZgmOiJ8LILpnFuvBCWzQGTUpLUa00xzKp_TfY9IN_1-IjOySW-1W7n80fzxpW74aAAQm2zLewGnCZsHsO1fUDK37Ugv69P4AmGGEAQAsSLzVAKtjVkNF2YW7FdGC9=w512-h640"},
  {url:"https://teechip.com/thankyou-047a?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-D08F73596B0E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhoLz1QfEtYem36h_fIoqhbNro8UA_1_Yzi0g8_bK5xvnOBGjmztNYhWuzYzbLo0WHsa_bjsQ-FNkt4Kad9FNW-rXTcqWF__w_NG4s9_wkjZReY6_7_LVzDn0JBLUDqGGismEqHgvrJnIaLw1P9__glyLsy0HS0COwXpRGkkYZ5qBIZF3DGAAD7QCHkNJZu=w512-h640"},
  {url:"https://teechip.com/1000class-004a?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-FBCA37196F0E-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiDlVF7nZG08VOsxvqTx_NHaG8hPRJvXtYqUsC50TfsNXoHuRB5IieA3GMvukU1o6vrL8nA3SfMrt4i5f-Ch6l0IaMyTyRN11JW58Yp3JF_Gk3RVgDuWPokkU015N9Db38_P1sQvg0xTN8ZkHmgYw0yYJw0TsWu7KO11Rhsf-MYIOUooPwT5wSSPXcVaar8=w512-h640"},
  {url:"https://teechip.com/thankyou-028?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-02AB22187B4A-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgq-c2dxpiDcUXwTqJFdigEZQMEcHAIRQYzio7fVEmy2O3FroOnm71GPqdnepQHSyuhFssaegyAevopz5UzxhfSlvLaUzWpWK7goa3K-CPVcQXUEvBwgYRBA5nZy557sfNL3r1MDoqn_ZFU2uRbGnGLBTHz7PuwkDDWIuPUMpA9ISy6AUM6qY0GGix09Wf5=w512-h640"},
  {url: "https://teechip.com/thankyou-118m?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-0D1DF64C2F5A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiksxb9W9SvVwTxOaQuDeVTSuaFnQBEqIs26NCu5r6iNjEAppaeTa9xaw_edxgdB4s2-I7-8Ar4NmmP_fFcsbNg0BHBMd7xrBHrb8WhutIE7RF0eVxQGAtTEDMzzb8vnpz6hcWsLp4WB6aHPRYlDrQr7ykPkmm8wS8gHKbQtymku3dLml38QzT_8TopfYCl=w512-h640"},
  {url:"https://teechip.com/thankyou-114?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-B778F20D6A5E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiIXFwzPr3uOO2BsxLxpgAkU8aoGvCTCPmWV_m6OF8BXUArzJ-xDM5jsZ8J2UyJCXubgNd1S4M_eo3C3TcFjaanQcyKBV3_dpcu6bVpP18D9GE8drLGu1QoCzbi7EdxcAnOeikKHOoOMR74EHTXjFMOITD30w6Q4wK0pXw0Da5IydXgwJoY5-UOA0o4EROW=w512-h640"},
  {url:"https://teechip.com/thankyou-116?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-21F8F74C6E1E-GS0-TC0-BLK", image: "https://blogger.googleusercontent.com/img/a/AVvXsEiHzsCAn0LyJLBU1_Om_sibjUoVkvFgWEpKxSgYNkswN8oyVszLUIF3eQ5SQ-GEwjQ2BHy5tA39iZFRoo7y7hGmdiDVxIzh4cd3reM0wvXLzWksxKy2et41KAsjBfj8R6VNGokTlYTCWg1-y2yjfl0HVU6LLTKLrvfL3CkQPj14rhVILhwTm8aIqFuKOQsz=w512-h640"},
  {url:"https://teechip.com/1000class-002?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-B35627192B0F-GS0-TC12-BLK", image: "https://blogger.googleusercontent.com/img/a/AVvXsEheOHeTBamybnAiSpAZPzprNMWUTKushXg_U0p1ADXUMgI2i26OVUgWtKns6uYaV8T0IQZ4Dhey7CCdk1iNOJKj7RSNP22Ty650p0hUh4nG0D4-eevELsCWuYjzXzyCU_RQK-gqatgJLPJNNmg4gHRbli1MfIiRa7SrrxU4GRCPOn0m2sOYqkpHvq_kwMP5=w512-h640"},
  {url:"https://teechip.com/1000class-001?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-2607771C3B0B-GS1-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjwKr_tX7DTaqvaqo-MOTBtkMSN9munbT7Dns5AVarhIkCIdw_aOyxYxzuYKEtCoV8kDTHIARPesDd4_cBN-pbRXFOk4u5u2nuLrX63d89U1KNgjDNgSbJLPycfQkyPFgNJN-iySsvCTeAmQGsQtxTqKjZ9WT2_g7j1Gg6JJjuWDM-Cbp22a-VjTv8KIDqJ=w512-h640"},
  {url:"https://teechip.com/1000class-001a?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-B8FA23087F4F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhiVB6Jj2qhDGF0ugM8-gXL2BqCiiLWo2YOfktu8Zg14m6xM0TFSU8BnUTngszGrZAF5EEFwiV1N-d9snLbDmCLzCyx6qqb--2uP9Vl1pJomhUqQswGEsThDqDahKTo79iq2KJGhP8XYQnOONBL3T5BgMNqpd9dHcKLU9W01lzGOwPCsrc6QzTwNL64Cxan=w512-h640"},
  {url:"https://teechip.com/thankyou-114a?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-4F78B7587A5E-GS0-TC0-NAV",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjWAP3KiUnmbf4gpTAKPFWwpodMCWVG_Ro4N7lPUBCwfAFCD8qNxl5xZ9_R8WLEUcaZ4gaGq1r8Zf_WpslOLbGw-lTmqMv8pL1IkF2_vV2VkF6AHhmXUa3XVHGNfQFd2UG32pv3OQh0lYnkk7B6oh6gNFcBD71g7gs54MaAje6aDjkUHfW5jHLKM8nULwO8=w512-h640"},
  {url:"https://teechip.com/thankyou-114b?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-8E7DF34C7E5E-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgSG6Vd7EY8Q797n3xfTt5bLMiO5HXya394d5rILn8M47MwmgD3TAF9mRKuMScNbRzvzpPOzO47q35zr3NfqJXTe8Je5reGvmImevfTOmj_2RYOs8QceACU_7GcCVDK3MabXJh50fGa8Cfxvbyqi5ppueHOlRM0fNf4HhSsNThrXb3WOnrOPGDpY1Go84Ug=w512-h640"},
  {url:"https://teechip.com/thankyou-115?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-7A28A35D7E1A-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgngQ9bYMr0T5TrRV8U3oyoWBQY_fcIT1_RsRNAqdngfKLpTKUiQc_QPFgVfmLIklweHhlmTHjcUtyH28_hAwlhgz6oLrisUxII2JbEMHmRuC-sWLI7L4H7F43VBaJ5xgVFEjtx5t5EEDrXSmeH_yP2nwynbse0EmWSlwnYfPdsd8IrdJFIowiqG9yzSZXD=w512-h640"},
  {url:"https://teechip.com/thankyou-115a?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-EA38E7187F5F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiSLrqh5Bh9dsgLOGyhcxiigg_PmMJ2kBcUE86tp67H3exq21pQt89i4B0OaxdsZyVQh_nxenvtiI-nC4YVp2DauK86oKY22LKa-GACgOSGd8u2fGASoYKLQF-E6GOelu7LUvXZMEWw9ucAsegGvFuP9N1RjhWAUnhX3ymBri3u5VZk4G0fY-3NxG6ONLag=w512-h640"},
  {url:"https://teechip.com/thankyou-115b?name=garment-youth-tshirt-front-lifestyle-01&retailProductCode=F1BC1B0006F0A7-15E8E6182A5A-GS0-TC17-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiYG42TL3_-YW6DH3xU7Z17WdHfQnc33TTwRnwye2WB0EMSsYp8OGgmQRfiVop9ieHZIpKu5qrQYw70oj0ieM9tyebbGWoVJITQRQ4cZVwgZk7Bu_iU95K5d_jcn_CYw4ytGGCQxo9X8ZWwxwa5Z7ZpZMsB3OGilp0OxmFFeFcnSxctliEQEajkPnb4pLlC=w512-h640"},
  {url:"https://teechip.com/thankyou-115c?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-84F8A70C3E1B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgfUYJEEX5SXvx4UiAB5lK69u7YvVQ1zgPljBPY9XGsGr4Zd0PK6wx9MbPzLaitCJTgpoAm8cmVXE_XwKdHqJmPOpLe6UbH6hjEFpI3objjGfJk_9sLjmSl9iNTDPL-D3bdGRgypMMGMidOweyuqsAH79_c3DWz2FWg9onHl8dGZMtklpDzXe71Hy-aGKUE=w512-h640"},

{url:"https://teechip.com/thankyou-119?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-DD1CA24C6A0F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhm3QUBwf2SWW-fwwZHLPtNrfvIuNQMq-v4pmfOxl1pKykZaR1Z5GilxwXOFtE9ilVXXtBPz3olUwpOsosUJgk9KmP3Io9isHx9Nd7jp495D_NWO8H7Ta8fI9903PzbjKOlTOwc4_SWCOh6V7GBxhi2jEXzgrbjIVywPjI2_4f95_0jh75-U7AwUuzdJh6k=w512-h640"},

{url:"https://teechip.com/thankyou-120?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-6D0DA3596B1A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhSULfO6KL2Cdyh_hpUp0hpqyWjC_-f3K2dREnej-qVpaVnf5QbuZAEu2x6BRjPtria-WaBTGj9kjlrI7Uu9YL_O0EsF8w3zVxT8yte0WFsiNfOdA41Z08LQO6OAGgmGBY5VJHVfmhxz_MeZCkdYHqJ7DtOxiP1qeCPaZx15yEJ2BXEvHEh6MUzvysf2Zkx=w512-h640"},


{url:"https://teechip.com/thankyou-121?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-A81DE30C6F1B-GS1-TC0-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEg05wNAkuL-LxHum_8Xx0UXSkgfb5WISiWB5HvIgViwgk9YBAis-PY7vN7aOjdkMLXcydVCjOAsQdPskB0JDepGDij2gJYEZS4C2Y0Jg-XS9JMad8A5Lygw-XEfft0hp74f6_LK7hTfff3-_bikjD3fzp-W8OGV7C8mNmuFoxXM8yh6_9EXZyKn1hZ-OYr-=w512-h640"},


{url:"https://teechip.com/thankyou-122?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-165CA74D2A4B-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEheggND7C8cQk9T9_RkqFsmjYlemETto-oCQvgUHa6QzcxGQQjdguADiTC4jytGoQZvc7uieQdzTfzLDOq0WxK09SZAU4PVVFcFIkgPLyqegVxHQ29NyHa4tGLKGuLtOGALoEnSBi8BdvaMY33N0X7CxDBxBDninq7xs8qHSmsFvU5zyLKiGtTvBuCM-tnj=w512-h640"},


{url:"https://teechip.com/thankyou-123?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-830CE7087E1F-GS1-TC5-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhvsSrDx_udqqp2NNoBwsNkAHMFpFZrA3B_4IlzmLpclnbF8FZugfMFRoOFrmleWpjfPdrSCJkzOsaMOWHkhmwbujGUw8GGyDB7lEOJjZz-i7LlBqTVCQ-Rw4E3Psz9KfyHL3LkvjrCJfy2wVkjJWl4mgZXqPuFXNdhuTkx2jR2r28_I360rfb89vnu2Uzp=w512-h640"},

{url:"https://teechip.com/thankyou-125?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-F34DE7187B0B-GS0-TC4-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEikQHxFr70W2Zu-ULDhRtVH59tU-mdW5M1DjxkV7RcFgKEDURtLK2FUNa_pd0jB-e9__pD0twN1leRDcQhGv4GOlLrMwvXKTPYZQDa9ZDKq3X5QlxO2zF3GMXtN1G_8qLMw3BcQnCFBLsVbV8KVyl7ShlPNyWIB3H_plzHq7JflM5oPkCa-FgoJwzBxA5TS=w512-h640"},

{url:"https://teechip.com/thankyou-033?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-CFBA36093A0F-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEilnIPYQbETczj9vo07LROTYtUECj9ZsITDO8nOCV0oHz929xJnba8DoqpHH0zWngSGGFGi_rVewAQiv28o-ebWenHDeWcWphnmE3xFev1ScO963EP3yCqF8fhmi6zLseiyjmvlL0yjSKnRjQIeGzRzx_4xbnY2YCtwvWV2FGuJ4h7m0XJ0mNkAhqYjpRTC=w512-h640"},

{url:"https://teechip.com/thankyou-102?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-83C4A24D7B1E-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhx7gjbONja1mX08EWywPRQtIYS2XhY8E_zAP0zj7C8lmVZ4hBranqvRVxvulULGGLt-ye6GkME8qhKJd4XP0a_T9tVV_qjwBKUWQSnN4VfsVnzpTodLwyOZqEMHfb5al-9v2fAOst1GuyRgOWLtOnvXQZ-kTHck9wuGYShxfu1EgSDc51wHJ3q9DepSBQf=w512-h640"},

{url:"https://teechip.com/thankyou-101b?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-06C0B65D2B0E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgpqwsbNKyfsy4u11-KfzYdPEJEOfSondo-YsdVr9QrcUDlz43B2GDVUTE8hWDw403m78IuZmx0dm3sUdOpHYExZT6SdrtwL_tPsa8YrtrXYk6yoqbcsh7FI1Dmm3yv0SV6FIda4Tz4rVaLoIIp1s99uVY_VvmRTPwmp4MW9nthBaJgNdWfOlfy6TZ8qnr0=w512-h640"},

{url:"https://teechip.com/thankyou-097?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-2904E6493F0F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi9XZfjJjJOcxmYH9UobBd90ZxcOxIvRQ25CZWWlB5K9yUvJZ4C8Ufa0zVHxdHymvvwK-3KAFBm9_HNBv93Q7S_3tbUAqIQdsKhUbJzGC9YUprua7r-eAvMfpeVaPEUcCLoTeKibBNZtNdi75lMAGwyMFPVU8x7EUmVhbE0CmCTtuvh9kept21ew-r0MWsU=w512-h640"},

{url:"https://teechip.com/thankyou-092?name=custom-hoodie-sweatshirt-lifestyle-front-179&retailProductCode=F1BC1B0006F0A7-C055A74D3A5F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEj7jL3m2G2OvVKEbJkvfLTDEIDJoNWNVc8KGM8XhPXzhivHSe0IRdP6BwuNkWFA_UxENdoDEM3N3S8eEQFShRufp9tpGBmSz6bMKJEXwDjpOXmbntICjSlpQ0l9tnbgPghoWmSqSCCkkit017v7lSQnlz8KPRes7I3zT2i_SlO3dabw_8QFL_sZ7FKAB2wB=w512-h640"},

{url:"https://teechip.com/thankyou-043?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-B95F625C7E4B-GS1-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhD596X0Gfl-vSHK0S_MLCx7SQEudV_aNUFsNhOQj0xmWypxWsQjYHeSADlSB2uAGWRRJU0y6M8fuEGX24L9p4TmKdh3vGdgrc0bBCeljXeGUzFjtu9_KBGr3mWkuXGvQm5bwToEYHN_xY5MfsCKmpUiLjvCtD4bVNSuksnD5SsoWgA8Q3dB-DWWIeNhZ-P=w512-h640"},

{url:"https://teechip.com/1000class-017?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-146B26183A4B-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiBH2jhS6HIQHEhbJY4VXAX8gTHc-xMr_QiKtg-mwRXQnPzQOoHs0KTxXENZ4kdydfTL7rcQkkGvRWeEd-j1hUOAZ28dLNdSzMitxB2vN0nxgIVbNCEPY2q1aM4WJXAAoLzDz_Y0y1hfHyie8mR2bc8noNvxFQU8zHzjGl8f3-pxDDQBz6Nv2BbDGAIpe9L=w512-h640"},

{url:"https://teechip.com/1000class-013?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-5FD3230D6B4E-GS2-TC0-ROY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjfMvXl5nmAZB_VAfLbApzVgYssI32C-L-7407onqKq9HGogJVN5yYR81MGEZZhsxFdEiE32vE1gDh9r26R9vFqN2Ak3fngPsJEWfV_fpLid6SaDg8TKJbtp2SuY4qJ7TS4M9kCIqhoaTU_YgThXr6WBvnzyuvMob20vvgsgmW8J6nUT2X3Z-iDS9NVzx6g=w512-h640"},

{url:"https://teechip.com/1000class-014?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-9F83771D7A1F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgwQDOA5Eiy_euFgxBCUL1WjCiqy6LwQyLMJR0a3wvtBvgsqyj7xH9Lm96nCCfrOjO0-p5grnvrTGnJWbVtUvwgMP08t924ibr-TZGPTeHW2xvPANYD2SXTbNuhxVG3lIw_2c3Xz4S1EwvXZXZFuzGZ5ylI2sy-2QnqoXQZzG6arCxmbTeaiymSjLjz4BaG=w512-h640"},

{url:"https://teechip.com/1000class-016?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-ABC3665C6E4A-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEihCIMNhW6VXXSIBpK7Ngs2GdSbnkc6FS6fGvVICpqUWhsJZbW_Lu9G4P1UEXyzRTeratgTlwaaBWwU25N7qt5S8b23gWXL_Seqt_5OTbNyMmEfncmQmeMY5ar2gOseC46Tp8URKSvEesZ0bMdLgCDZL1M2JlrQ4NtItqv0HuEKlz1Bm6Jg8izIwRxw5hDH=w512-h640"},

{url:"https://teechip.com/1000class-015?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-3A97220D6F4B-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhUghuiCbn4aHewLLI0-eob6kIr3QxflhF9aB2m-RxmSr1sELfwAaT8_G7kRc4Z2ce5N-ES6gVLDH4_tMHKkTo2p7sQBqRQ8CLsg7Kws1NM5M182OwbGg9x5ccbb2IwSzc_tG1A--OJXa-uQqZx1m9XbOKpdj6gqqg1JKKNx9fteWKCP2CUnQE-D8V4Okvr=w512-h640"},

{url:"https://teechip.com/thankyou-117?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-1DA8E61C7E1B-GS0-TC0-GOL",image:"https://blogger.googleusercontent.com/img/a/AVvXsEictP8jpq8GfHg9j-60Jk7qX1_YL908Fq9TDjvu-QKrg9tBLXeam4KBmothRZpNKapCK5h1PFgNRcCCpTaQLABjIiB_QesNWl8MbDqca38T577mN8ju5RS_bilighz3VkSJxZ0t7k4z_SXGKtjy4FOQVLRzlMWvv9etX12-zNpYk1ypFAbzi29IfqKO_-s1"},


{url:"https://teechip.com/thankyou-104?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-7FC0E65D3A0A-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEj3WcIiHm-v5-Nt-KSbh1cgLkRDWeLxZsog5RUYc6WRZhQKniI-IpO3R7BmcOZuiXNIUGyI3fNiehX7jecnce0Nacrfby9_txujV4Fdqo3sk4EwS6j9wnTRgyQshIBgi6fZUl3oCWe-B3U8tji7aimOhbfzpsuIXtps5_1Yl9F5vzJ7vOLyO51SoqfImpxI"},

{url:"https://teechip.com/thankyou-106a?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-192CA61C3F1E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEggjkiv9pw-EhJxLShPCOXF5vocqn7CbFuQgQQpFWBGYLRoPQmSFAjnW_lU_0tPAD3zFoVgDz9LaL455oZXfRtmdG_BPZYXtbhsJSW9-N3cvg8jmMzZVOWhdgDQ_kyO7komfKpFzxTLbQcYn82rkkhHFijogp-UhlC-pNW3d68RbpdZ-X8i7qYxvX-OVQfL"},

{url:"https://teechip.com/thankyou-109?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-F469F61C3A1B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjL0DhTlLLvdVqHww6JU1PdDk0gvy2qDVbpYFnMt1lEPhzFrT1oTsMTe72hTvYxyDAT6v1Sk_dEV3Hn4iFs7BE3nTgtkB55RzQbv6KLYI4gNrHKVp5de6JYNSnihy3ILB_NwGpxj_TuGU_-zaxRhQYRk3s9AjeShEvm9xNQJ8fIGY6T0pqdtpVAF2nLe_-a"},

{url:"https://teechip.com/thankyou-110?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-9868E7083A5B-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgxj2SMVuiC52YsS3kgDsRAdIwrHemf72yFa7ZxLMxCTwOVn1adaBMNvTx3oXQ7njQKZkQioSTGKfpxRUlFlt2lCyHPjfnwEEvp4ck7FJILMqf_7GUqtf90vkNriLkmBy-2Z968Xa4tfIj1fMdpgQhKAkAcoQOKrL5rj-gsoPTwdHGnT1vf5IiAADOBWBpH"},

{url:"https://teechip.com/thankyou-117a?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-9CB9F3197A0E-GS0-TC5-PUR",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgtgRFT3j3mqvkUjoZ2YAFL1vTEUBnPATMQqmPpcymKfVXTdStirIJ53stMzxOT684hErwB3L_KaNCG0ytgovtYdOSXtJ_r_ombLq0ggjyp0vEvO7lJx-M_FVSzOmjjhawRDGo0zTVL9CG8T3BytaCX_Aq0j870RsyCLqsvDPFxdXZZzqJzUVxhkM2IqB0-"},

{url:"https://teechip.com/thankyou-105?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-FF95F35D3A4A-GS0-TC5-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjFSGfNaWHl7H1Zo2_p7s_2oS9j0IK8jVPofvokWcy7cOCCdFgxT1t49uiPAFrbRc4giKWH6hhaVRq6FSYBD8m_JVIie0JTdOXnAdJL2MnOhH2yJSmKHV9OtuVSQHrwskv4BL5SzCb25XRMp60EVheCgVOViPUnK6XSN7mmmCPs0-rCF52xYA7-UdE1RR2j"},

{url:"https://teechip.com/thankyou-111a?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-562CE64C3F0A7-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjxtALInEDTE356fnAUeKxSxMQgb9GSuSdn4Q1NKNzKRw1sdwyOmeCqx5AlM49jYcsNCT6rf1tggSKKYJllB_dqvf3RmvHyXMFCuEkVM176Llju36VtJYS04iJWDNw-OkiqAi_vAjSnMco0OCHUUbXBW0WNnFWAPSWaxRahGlYLNnxOjNIR1W1p65D3DXp6"},

{url:"https://teechip.com/thankyou-117b?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-68B8B3086F1B-GS0-TC5-PUR",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiEPRQQjwkkxLc0uDLiVNFw-2GppCCNaHjXE3Tfv83IhTxcwJxrAJKt2-_9ojgCk_oq4E1C-gmjaCQF5PGsGZU5zAMMabfHFdPVrii9bcazUm6QgdKILX5mS-3adCH_FAi_sy0p_vQmUvmczARJAx3QcdVD9rwXdyapioiLv9iZ6SofISQ3qe2sWn-vwSCY"},

{url:"https://teechip.com/thankyou-107?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-8068E7483B5F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiMPmd6xibtsxUt_4Cw2fQLejN7MusG-CGqGQOsiMrn0ywCK014bt88P_b06xfjtABgPeGizv8-kvuuW32iys1vc2gXdLi_aG6NwgZ63GuuQ7pwT1ITFM1pmkxlzAwOeM8jQsOysJYlhMxL43q0z5wjaQ6Fcm44j_hy2JJb5_xC-Z_R2B7xK-WQolMERWQZ"},

{url:"https://teechip.com/thankyou-108?name=garment-youth-tshirt-front-lifestyle-01&retailProductCode=F1BC1B0006F0A7-3078B25C6F1F-GS0-TC17-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEizn9Z5K53SmTKCWc39SUVeUda0AnzOAeBYXuvOlqq4hBpdTEKNd_EcGGPsdiBtBx4tyFlAkxB7JmodUMUdV8zZmRg6-_pvLee-uq8obYwD6ims0y6isrCLXlQZtTNTafdQ0Ug23-bcgzMZLeYX-DTcGPFOM6tQWYKJGoLE1_WjJDF3flD1iNtdFjaM2mFn"},

{url:"https://teechip.com/thankyou-113?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-3769B35D2E1F-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiGniI-Io31HUx_eMTUVhqIZ2-43_Nw3bEE3ko2y5u0hGSr9z7rEMvqtNkTa9I3KM67IxWJJvIJ0KW0RhFKJTw52jnhWHh21YLiJ12wYK3BmWwLaLALofTMDq_LqH6Xj6l9eEmgHAuQseouoVeWRllQr6tb5BLsp9X05PhWyN47_tezls6cv-EGozNE2UXt=w512-h640"},

{url:"https://teechip.com/thankyou-112?name=apparel-crewneck-sweatshirt-lifestyle-front-42&retailProductCode=F1BC1B0006F0A7-932CB3483F4A-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEinRQWqj3jHOMc-036SPbdRQ5IF509mKotbztpy9yFuvpf0XIhecTzKZE6QatobGgwAc4r4FBqvL1v8kiD6maC8qF6I5ZXYCxlwV8RQ7ikS3oJuWDPrgurr3F2R6ayFqG1zsexiNrnznn_ui4D1yFZN28NDzwTQWMRZ9FOiy0WyLBZMSZM-9V30X54ootyZ=w512-h640"},

{url:"https://teechip.com/thankyou-117c?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-E9FCE7583A4B-GS1-TC5-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgniJDfMvoYcVnpr_hcwAAN20c8cK4f2bR6u_ANd25i36ke9zcsoRVz7UO6Z9CMjw7gyW6aH90SnVdJjklU-LPuL9QqnfVcCUYnhWKftEP5EWrSSQn6fg4tzQ1ooHMEi6FRE0ruwiTYFBhU6druRJczvL1v-WrkSf5bucDcr5QxgfX2s7vBTUElP-zqHnj3=w512-h640"},

{url:"https://teechip.com/1000class-023a?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-463F72596E5A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjOF-HeAPF3tqBdGgysa1Tcufv61pAnS1aiNuF11_hau4zrWBPHHnJMTEiHGa_UYEL-IbushEXClqtefGm54ag1UNGRMctVKvL_ah6ER1WmNKw7-Q2R4Oj_3AFS4WDJZPrPCj02n09RNHSDrQUlYTUobvRnTkgH4S5nRJ-Rjecwc0B1eSU-jADp_Yh94pmR=w512-h640"},

{url:"https://teechip.com/1000class-023b?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-866B72583E1E-GS2-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEheStJj5yL0Q0uPorX4xr-g_J898MDHF7SF-iUZKCiYtajBW488ZR9mwG0muRP5_YE7HlQb8HGjntnLpd6g77GwaU-cI1uqpWdGVxXOJ39dySoKTPrjR6aspAJbKyDlRDCIK7N3VUxStaAo8pq3Vudnj-GOQKytOMzqIAYm-zkKtiU1yctYE9c4mC--Uuwr=w512-h640"},

{url:"https://teechip.com/1000class-023c?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-373B235C2A5A-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjn54z8o78OdtO1aAdN_wiuAk46BfKVSEtgsbIwwyPFbPaZEh0EQcUC5jdIIo3g9Rh4XB_ssCCQ3DpTv_lcVin7-lc3u0UrRKBSGrXu9T4bCxQA1B-io7WIampLztCH3GTdFZlY376DCMdSapGZLqGzNQQXFRWFt_RigccznVRCkkcyzNHTBf8SzC_f3F_x=w512-h640"},

{url:"https://teechip.com/1000class-023?retailProductCode=F1BC1B0006F0A7-EC2A37196B1B-GS0-TC0-BLK&name=custom-t-shirts-classic-lifestyle-front-451",image:"https://blogger.googleusercontent.com/img/a/AVvXsEimCV4_BNSEgVuRSXbn9prdafidlZ-ETokJTnk3myoBDICWE7zkrvgWrHTePR48urna923VqsLHL_pzKKmaTFx5veZYcPbZyHeUfMqQFk3P9AWxZWSTDZaOjWhRtX_knxE8N8Je9qdT2t4itO1vf9Svj8Fw0WTBzR1Kybf-g2f7VpWL7eBD42r0wxx3aIx8=w512-h640"},

{url:"https://teechip.com/thankyou-117d?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-06F8E24C6B5A-GS0-TC0-ROY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiw08kSubR_9d9Zem4joWlOzPKpgEkJtbQ9nQeShh8DL-1k-1n55EjuDGpQVmgiqKB8LmQkTdRdnY2gi22LhwNUCdg39ZZfafLxE2llFuI8vzPT1qH0BvJMQLGCbLllm-40mWHhDkgIirCsSf40N83MPTzzovjOSS6ZhpcgYebEQRspPYmta5OvRzi7czcW=w512-h640"},

{url:"https://teechip.com/thankyou-024a?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-0E6B66187A1F-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi-TG4BESN10dtfcT2-qQCo_p3Lg2suSscpbrgeU-FbTupJtS2e0hsUI1B_xAKlgiHvu3GfE4eLj3eHddYRftCMQbanevnsY2-hrPQ6vpUuLLiTiUGWIuZzP2Zf_xLdD5a-8rVQlgqJku1DBQFIuX4B1NLhACID5A5C-OXSf-ISLKYmTALBIhafMtvCEdq2=w512-h640"},

{url:"https://teechip.com/thankyou-024b?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-9B3B260C3B1F-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiWGTjbjLV77aUrXtp42ts7bX-Hz_InqbxzZd8dEt-DTmgL8-VcQeAYu9bfWQclT9qjq0c30jkv_R1V9U_GF0leO5E3wGE00LF3GHgyc2T-yfH8drWt5tzisyrhOpc7NCVNNyjplaz1TKpj3tKtTvdQxhXjKd35I0XwslxmpBpzElt60-MOA6gGzVm_plMD=w512-h640"},

{url:"https://teechip.com/thankyou-024c?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-2F7B23583B1F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjMWbfw8hfY5D7dKYindUDhAt5lLn-9nBB6d0VvXHjLn9gtc8Nb-0l7LhtVtD5Qjel7pkQp0mcjwpZjvw9E_KThrMcwRKVDgIT9aBECOTfl8sOB8vKlle_gIa28TAZMcXazjBWyUSok669Xb8h_MD5Los5I1rXMKr5EKvJk_yLwrExhHmS-Pa_19_U7jDlY=w512-h640"},

{url:"https://teechip.com/thankyou-024d?name=garment-youth-tshirt-front-lifestyle-01&retailProductCode=F1BC1B0006F0A7-BB7A72092E1E-GS0-TC17-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiDS6oMbo_AlFBBC-zkSHYOW3uZpF2L-G8wObVVLbjN2_rRyPRHGnZHNy0dLQBZO9YPWu6Ca-etXnplRiUCHvxz_Cz-vQ1IsfRoE34Eeoe8Q7B0koXiWrARKY9oPoT2xJL-PdE2zRXCCMEUSdFtcUzTIHUJGpqWiNgg_LxbFuBTqUs744a-QFv4iowuLs1u=w512-h640"},

{url:"https://teechip.com/thankyou-024?name=custom-t-shirts-classic-lifestyle-front-330&retailProductCode=F1BC1B0006F0A7-B33B664C6E1E-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEht455dFurHvKxNjXx7hTjXE1-lSAGjKWC1bsUXqSE1WFzmKONKQiLEcY4TC7r_DDoKdAsOHn_ghWkQ2-l0AGIbU7fc_8ZH2hLXSbIOPHsHWTAA6eQVk5ios6UlIvoXoqoLxJqAb_Klf3ETYjb9fF6XxMHGMg9j1hOJvXYYBhm7c5bhYpzBKwSF5EmNl8wN=w512-h640"},

{url:"https://teechip.com/thankyou-025?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-01AE26592F4F-GS0-TC5-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgIcBLZQ6n_uzsjvAgVqZ6IiNU6fCiPn21wxQNrqIS95GBh0fR0WufpVtwn7us9lcsl4nyipEY_eN0a1B6jaUyZwuPI5rgzVsUfl56tSZbDiE9TDe4j6mNldP4vidJBLYfT5bzEgwpT2RvcyHzN0cAUdTVw1IUNjNRmqZsF5EPcGme1ls3RUoLqyiaIW8Y2=w512-h640"},

{url:"https://teechip.com/thankyou-025a?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-D5FB27597E0E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjsCxLlDSrzsHHRKkLxK-03cHX9-QpfJE7xBlfvtXUZV-g4DMGqOvv-Is0DuXUFoNEz_tL0TZaOuZR959JDgjsNNVrtcbmqEKwP-N3WGquzm54c2FZZIevavBx0r65PaSzFp-2jmXrBkXPJzchkoHNXiS5xbKhH9_xrtEqmkrUH9k3Sy32CWtxGQzWv9Qym=w512-h640"},

{url:"https://teechip.com/thankyou-025b?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-74FB73586A1B-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgNlDtqN6vbdGu1c12MCC3s4bJaRMCLWTojAXxtr2HdVyW4zPfyBeoq9KBC69tsJGhatkn1WsGqwKxnKj6KcbQjW5VVkw1eGIG_ZdGNXQa5vRJgJcjPvjQWS2cyvSziye71FNELwst1J9qHnUbu8YXCMI_3gilKfS5BY-PpOSTjengQUuYhmEQ8FkATsiOg=w512-h640"},

{url:"https://teechip.com/thankyou-025c?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-E5BB231D6B1F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi4VpXhEA3LKk0uA7vNZh4hkQyBRleDqGPtwK18e_N84VbHPhv9CKBFz1nObxNv_RrbVILuS8x7hjK95flgy0T6YgO1cBio3qdpBkebndmCO5yhiQlQMeRKY2Poq6q1cF_0XI_sA0eXHt6tXmEr_RlzFUEFhCCKQLH0u90jYrcsjcpiAfl31hVXGmsunGAZ=w512-h640"},

{url:"https://teechip.com/thankyou-025d?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-19BB720C3A5E-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjb011DI0-FyZf7FUFHDoiIN1CmcGL_zV8hn_90QIKYEI9I6E_Yplam58ylodj-qm41EQVAmg4KYLKZQD0YbZK9p44CkXBVcsmseRyInjdGNX7uSj57ccYLfPC0-xUITle8uJDCck3aTsLF0G0ORySiX5e5kmy1K26oM9J4IRkVzPYc7XnaLmscifF4fcCs=w512-h640"},

{url:"https://teechip.com/thankyou-031?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-E6EB23483F0B-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEj2nR8IpjRW8YAOST9VeA2tr7mJJwA2EM4pJytlRBNdHMMlWvRijSPbM-psMmwLrUAeE7RspD4LMKVtMrBr0qAhdrlpTsmTYdDr6qoPkY2iXkSYVJp6Tow6ll7QeZyz0AYYLyEzOKzsiuVqyjrA6tdyvXOS2gZFIcTvAXEonYedOUYvsS5s0ITn4Qh3_yUE=w512-h640"},

{url:"https://teechip.com/thankyou-032?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-4EFE76186F5B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEj9AOtoO1EF4wJH9iil8uPS5U_2wMM5E0OKDuZ6NhwYrtajCZ4G3neMRk0cSR0ppiHvCDaKe4PZ9rcOBII0igl_BompWBoG_PX8s-_l_2peUPShV9VVYmRY0lDB7UjqIr7xSKGEhYzctlU0bScb_tb0vI5tkhf8CvkgpL5R-_UEZ-tifbyDzr4Sjzq1uvQ_=w512-h640"},

{url:"https://teechip.com/thankyou-034?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-6ABA67487B0B-GS2-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgFyxg3I9pyWR2KSMyRNPAoQ8D0oh3JitAUsxnaLS160YVyhjDfbfsSxB2KOrY0tIPsB8rMCinIJ2t5KBR0RR3e-B-cVw98icaxX4aqQ4hi2-OmjmGuxIBoRCOXybZhakIGoyw_zwnxJZz69uBvI0Sz2hy71Exmbb4KtevqaL06O-2hXoGmvuTFlMzG-Hd9=w512-h640"},

{url:"https://teechip.com/thankyou-035?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-FBFA63497A4F-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhab9x2UsF2_Jd-uhEUXouQ-Mi-Nq2JMiqwwgJCYGlhilImWxfidrpOFqHzN5Bh90cKNu0AhPFrHYOfC1_L4iv5sq3oqBvz45sGub4TzSlonJKYRyP2MTyiTpn5fnODV4voUPgb3siw60wwKa3_QNA4WnEzdNGjlDtWbhVOeHTFsPk8MBEmFhIpSsqNeel_=w512-h640"},

{url:"https://teechip.com/thankyou-036?name=custom-t-shirts-ladies-lifestyle-front-112&retailProductCode=F1BC1B0006F0A7-141F77486B0B-GS2-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgVSyBvwAdM1dH2vKIWAdnXgLuGRSOoqY1rjtFVYY5eL5827LKVq5kIJvmC7y7VnhXW4zg0EowTufg0bMSjtLIZMLwF1ywxARlaYbXesg2o1zUMRpUn2Tb66TOoJAosvhul-BiALvemUN3lYmwTZBnQD-H1rfGLCz5jJFoPf6V0W1hCVLt6T0blk-mrsxux=w512-h640"},

{url:"https://teechip.com/thankyou-038?name=custom-t-shirts-classic-lifestyle-front-330&retailProductCode=F1BC1B0006F0A7-214E761D3A4B-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhvdpV5j10gNQGp_btrjTF1Betd_WLdkg4MxHxmbeNpD4Nb8Gw3kr3qREqZktCx3_qYpMYQTbX-nkitjxZn7VDcHE4b2dJgYW7Lqd472F4IOA52GdRytlUTzVnO8VUMRFSrHqjK_JLVVjG1An9f7IC2TYLqi-jnTD27ALcIxhf-GtVSVPTQ5hYbGMbc36U0=w512-h640"},

{url:"https://teechip.com/thankyou-039?name=custom-crewneck-sweatshirt-lifestyle-front-130&retailProductCode=F1BC1B0006F0A7-A00A62496B5B-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhGV_i1vC2kH59ZQ8mXEzdResHItP8vkz3wH4wY--XhUgM6hymzR6dN5XMz3DHXnxScSzhtlyYIRSdBGOB3OKZrg2A4eJpv5iQBOmOPw6HUHRvtKQB59pv0mJpbN7Waqs2IQe8QHRcHl-G5kmvCzKfv6czHtnntPwrBL16uFeAZGQg2J9Nob8ongrDhEvgo=w512-h640"},

{url:"https://teechip.com/thankyou-040?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-1C4B63082B1F-GS2-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEh3dUhhvXbRvcO_tDk53w60Q4esc_QG8euN3qeS_dXLpBrQlE-cXEktv82pzttsYcrVwnR375_UsdxLS2nfHj1XW3K4axcqUai7oI6b9vvdZtZPBA-K94-4V_CAjeOoLawh_sMAnHVBvv8XCy1OpW9SgYJ0YcA53DU1Up6dLptKiIyCOJWqMA0pjsZXnaET=w512-h640"},

{url:"https://teechip.com/thankyou-041?name=custom-hoodie-sweatshirt-lifestyle-front-179&retailProductCode=F1BC1B0006F0A7-985E73586E0A-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEigaE2symUaypXO9DvaSrsBoZFfIYEle2UnffZLUm-vkfzj10PvXGDBFs_zKc_qi79YjC9JsYWSua-4GZu66uBAuIfWM8eM_EDyjhakoRSYr7Qw1QGO0Rviy0CJffGmzxWl-m09hRVtpBBojHMpBWryh1pYEdohJc_GpQIfqev92BHRLL31Wl7SQl6IPhd9=w512-h640"},

{url:"https://teechip.com/thankyou-042?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-281E671D2B5A-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhhgn1wGNxZGYhWv4FBfpszpjeOH-Nj6xykpZZXKLa4QUUo2_osnE3mcO8qFMzM2WeabgOPlfkhBFla-7JThiaTVAeMlkIaOOya00tWeUSSuxEm6kkFQjpruNNKBT2VmhQ7V5Bw_HK_3Qk8jVewC_-eWQXGY52vewWRIorRHMw7Xg4i4TkiHUD1kSmXbBuT=w512-h640"},

{url:"https://teechip.com/thankyou-044?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-024F27087F1F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjWC4uJK8IcnePMFd3VX6TJKDgfZINjKzS2Kpx2melj9Vl0GCW0Dj0uh0L0e5mvypLZTt1Ko-vOyXLG7jV2jARJVE60ao0o5ecI04xpbQDiLDEAhhUxB4gCyFTvwmjDNSVnP1zNJrj304XYGh5UpQiBFKADIe-mWjCpdjAgSa7Bs6bJvx6tyWA9XyKj9EJE=w512-h640"},

{url:"https://teechip.com/thankyou-045?name=apparel-crewneck-sweatshirt-lifestyle-front-31&retailProductCode=F1BC1B0006F0A7-D60B26492B5E-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjNRh17AvUJkxOzI2TpYoFAi3LVPJIBWTNk49S0aDoezYDdZnCflwC5RZP6RKZ7l2D914uDnogIgX4KwQn36-9AlyGupAilpddK2RVFSOxO-lxz6s6D5hPhT3iySFwAaJ6hmpx6CaUw43cJizt7Px1PV50HnbeWDbwCGVq7rtlp6KECQ1VWECsIXBFtUGzN=w512-h640"},

{url:"https://teechip.com/thankyou-048a?retailProductCode=F1BC1B0006F0A7-759A62587E5B-GS1-TC0-BLK&name=custom-t-shirts-classic-lifestyle-front-451",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhkR2hbWcX4ha1xk8ZPXeoMhczTd_n_azm1SavLJxtFBnvdJR3QGxxlJJSv3GsFjU7b_wC86HwX-urjgBFJe0W1m61OMTh-kB1dB6VDHaBU4QYVXy4doMS9J2HiJJGURONFwQrFGqCbYbEy_wfN3AEpRZhRcuE3bG7zSHL8uoozHKkd8ZUI1rg-QmAjNz79=w512-h640"},

{url:"https://teechip.com/thankyou-049a?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-A1DE275D7F1A-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgGdSr16kM4PH-ab_sAl4PHXRqlm4buq1_-015VA2J4fkpq7mKI9IlaZXHoJx5Fuv-E1Ji6PV8iznWX4s7FfwhL1zPzGrz94OTLYAAkgauqksicxAS-z-Ba22ozIbuEMyzqzCtLGC0GfFz9qHWUrFOHiSdIUmEe34pu-GPOeGc__txN5kKqIQb_imR2UEQ9=w512-h640"},

{url:"https://teechip.com/thankyou-050?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-2E5B73193B4A-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEimdsR-uCT0eAuypNm87pdj7CrAsBVwej8unpi6eOC1ngp6U7IjxJO7Py8HJG12Fp1SRaNKIdwnWLOn5bW93vZF5F3ToE5U17omxElprWSLzv6y5IPCepmNw36VLUCsKE14MiN-RZZeZsRzn4ucv0bzqz793BcP2Mi6znD7aJk_GN4MQo6aJ9Sj12RltZ8H=w512-h640"},

{url:"https://teechip.com/thankyou-051?name=custom-t-shirts-ladies-lifestyle-front-112&retailProductCode=F1BC1B0006F0A7-DDCA630D7B1F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjdmjp9F6svPi3nNPt6glZcPwK5cEcDC8QQOpVTUib_6R4tHpdaNJZbXpbGeDdTeMvkYHrupqMoLW-ODxlERWM3OCwSo659w1DBZKGHo6O2Ggv81mfUgWgojwcS3TswWYo62ZpzSrXwx9JoCqZkRzhPu_UOLIRoPBAZP_26JZXlvkyFW2kYRehZ6xT5IaD9=w512-h640"},

{url:"https://teechip.com/thankyou-052?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-6CCF73092F5F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEh5CkswMV9UBZBPTSgeEqJV1wP7nUaBaffZ51sdqGwMDjpUb8isv6B3R3n7N0rKv4BaFQ8NWnJXAj07ObWdEkpEWHVZk4f3WM_eZPXu0xDAilfdWyHS6NAxAX-Klg2rm0mEJMr61Ye7TG177c1kblOIIijDIbgrwIP1BUCN2AogJZ03lQSchsFiQuTtjnDV=w512-h640"},

{url:"https://teechip.com/thankyou-053?name=custom-t-shirts-classic-lifestyle-front-330&retailProductCode=F1BC1B0006F0A7-A8DF665C3A0B-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgMbj5r8Frur8AuUZ0HIWJVBhBzs1DOGTyq7y1r8_rKG_bqvC1yrn6mtzAUZy5uzG9xGqhMhlLL3Hn5AIhOhftVJ7fZML5nQ0zviWFfnTSyLBuNbuHhImjZ-j3exfOTK-1wrvLcmppRTMALCyRKf6cgFz9pOkud49nUZvATlrEh1Clcd_CjnBGCZ2Y1KQAL=w512-h640"},

{url:"https://teechip.com/thankyou-054?name=custom-crewneck-sweatshirt-lifestyle-front-130&retailProductCode=F1BC1B0006F0A7-178F33187E5F-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi9quOY-UhD8JW-3aAJr2bAegCzM0YL1l--Xndmsb7M5YEDMBR8nFl0--7Pwidkm9KJPajfnShiy-YmVgdTxbUJV0_tNhlF9wrINnN998sRnx8x6DklBJ6kun5N3roU-X59WFup6C49NHGXWKhaEN9SV22dkkKYnVC0tafuYMjutoCDGa1RsP6ZoO-ZPzH1=w512-h640"},

{url:"https://teechip.com/thankyou-055?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-968F770D6B0B-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhqTHef92f_m0qKtutaWmCSGK1Un8py9ZZ2bRXl-5sIy_4dhZz3N8MWGeQSvhwxMGpcSqL8OAzAPKdxhs7FYYmXMwe9qU8s_mqDGd9uM-vkXXAnSpBKb7KbMAaK7zC64vFnf4MIOoxRFHd4nOW6exDlLExqXEdwtF5JJO98-_aOfn-Ldf01aGbD6JwjmovF=w512-h640"},

{url:"https://teechip.com/thankyou-056?retailProductCode=F1BC1B0006F0A7-329E66082B5B-GS1-TC4-BLK&name=custom-hoodie-sweatshirt-lifestyle-front-179",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiTlgi4MjP5M34dm-vfpLQdC__WSPjfG0yHhVJjswXGd47sfD0DphW6BjILas34JgDeAHmV2DEegjyh8Fg0AC3hM5RthjTucf9ajsSK1cXfNhxt2JkCnEggVaDgvr8YOMroq0334a9N5FZsn5wmcJEXkFF0RATs-IRLIlju9h3RlZ14JZ9USHt26vihNGmC=w512-h640"},

{url:"https://teechip.com/thankyou-057?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-B28A370C7B1F-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhsTqozc5AQAOqDA537qyX5o2atMva2nEZlDReaDTpbYCGPnD9u65uXei1l4bk8FGHq7lVRKcogHbGjMSCVcTd9paIpdLREKLRxQKwTuwVKqAKAdTDxiEJocLo4NdNVkTYrRAhCY5zESR5uuaF447iAXeR1IfWQfiKha1OHKImiLH-KVcx6RqXS9cfvTKN0=w512-h640"},

{url:"https://teechip.com/thankyou-058?retailProductCode=F1BC1B0006F0A7-0ECE66496F0E-GS0-TC4-BLK&name=custom-hoodie-sweatshirt-lifestyle-front-291",image:"https://blogger.googleusercontent.com/img/a/AVvXsEh2jx2T7fmYFxUiGL6WF68yGvyDZIb_BeGO174YGxWRE7r9Pvo7sdDr6QNx6wBqEBOjX55vJvzD-WDWlLFAQUOoAmtyIuvwEzVdlf38-YCOvUcbIlLa6qdpL2swohpoGh8CiUFbLQe1CJsGM8htrvCYFvH57v-b4pCmbqX7BpIsVT4JTnqVWHCVc5N4pYq9=w512-h640"},

{url:"https://teechip.com/thankyou-059?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-8B8B630C3F1E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi9JPKOLj_RTD__PWDnTxrxCLSymJW8TAOBUIusKi69JmHceX-4wyvR4tEgaJAECa3wc-JodKjhDb5AuXYN2-FW5uSpny-LqXw0ngSGjoppAbZJ5dME-Q_djfNCdY8w3_3CHrQJcaXmIex2M8eg6SnL5YDhlMtPGxj3FEx3Z0BU_HI9zo0kuUc1iuAKD3vB=w512-h640"},

{url:"https://teechip.com/thankyou-060?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-6A8E661C2A1B-GS2-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgnOgX4W5BGoCD2YNT0P2D797hzuDfPIbt5pHZnxAHeRBUPlCVI3KQD4AwjS4VyP6OsIrViSV3JL2uA7b1PKTV8xkbz71DnYw5nzey-20ROi1Ck7wp0CSM2W_2RpgPtT177aK-oqYnWMWuDDyFiCcM_rto3g4hiZejE9TAzjemtCkCDJld7Fcx0-KSsBFYG=w512-h640"},

{url:"https://teechip.com/thankyou-061?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-6461B24D7F4F-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjAR1pov99g1qFO6vHrUKIY_lshbk7GcYiRiD9bgsmXVOvQB6k6LNruy3fH8KoM971Hog4TAsoQs0rkTHPM728KtzVEEcYH0vCSsxEyJcwNNz3nVxDb_lQixax72Vv1I2oEnbIdkHouO7W6L_MwS2RtkTRFLKWVFP6DDVP37h7N_Q_7bFbeENFg1pFmEFOL=w512-h640"},

{url:"https://teechip.com/thankyou-062?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-F135F24D7A4F-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEguQ6BLMikZDbk0NFfP7RgzVXuFS3NgP58gCzS3Gpp5LxHyJDrrdw5lbh7DjgkAvxJvcrZnw4HnQqNP1oSPPQg8yK66ZGLz9ZZhso_X4daFYdvNzh78EB8jHaNZHxFDw6-5Rvkd8uJMP1HvfJTDBOf2mhdy3QQghrKwf78t35aPys4xOTyPrbWhcYCt9w1A=w512-h640"},

{url:"https://teechip.com/thankyou-063?retailProductCode=F1BC1B0006F0A7-5C60E64D7F4F-GS0-TC0-BLK&name=custom-t-shirts-classic-lifestyle-front-451",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjfC7LG6ChhH6Yzo4Orx0SasO5vqg2PHC_g6XaBD27HHRiqjAuMGlXjlQHjZXA3MOr1sqyGBb7fIHjTACvsJ1b6pJDQ0OaoQCnNM3pBFC24SOPGZcbdiWAPepsVBNJrDTSp6bkevMrX3CxYpfSHJyRtzfpx4J61KAo7Wd-LaMtQn1ZtedhxM6xC_9Xn1lnl=w512-h640"},

{url:"https://teechip.com/thankyou-064c?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-A481B64C2B5B-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEh47kRJcRdxq6ZjpZY7N_-oTCpWHJVL2b8h3wC_9JUMBfipE9kNRVw6-0Wsog7203xL4vHvY5e3s43xunf8ks6HvXEqSxmipU1UGoD0r2Mf8a5jgikJoPldFB5KWgJ9Le6_HRRW6eYMz-nPlI5l27RwVYoC1brVMB9be1igZ_EaxN9DurjsaebpPgJ-bu2-=w512-h640"},

{url:"https://teechip.com/thankyou-065?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-2C31B64C7A1F-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiEQh8H7-6pGza7py2PBu5puZnK_mlvAyAsoYQXioisQmsOL_L1RMg8S4bMVUiujqnjdjt1oXUHHOkjIdXHNDYzgpWL6bGb3fD2XX11Crb74cRSYSn4m1hl099n4vSv3TKBNiIi8Ndt3vmi_XG2WXYlx8n3sSVIFwv-it3d8bLBZSOOa3PrD7hpWlfe3DOz=w512-h640"},

{url:"https://teechip.com/thankyou-066?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-AD34F2496A5B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi6aD3F5hbSfAiFYCPvKQdMibR-ClqcYB8KOyBEh0XF4evPDHPUwbdJtCEQ5V9HQs7kg5Z1zoXfgJ8brFnpw-hXVqNRh-tkBRebDgYQy2NU6-3mNpsBVgOpxIgvS3Qh7eXRwEhLMWiN_oJ-gShRH7vH8bQGBO-j8dUu-WwM1NfFfBISU46mUos5w9jAeIRy=w512-h640"},

{url:"https://teechip.com/thankyou-067?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-1275A24D7B1F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgyba0_jqvOoWbO053wbD_-DIDF3KF7enQaNlYf4oFd6dJjWikno5DMXftY-Abj83ohnOsJUszwZasHEoskXH53p60DSLvciHInQjEQLblXw0aVYRiULWAE8oIOR4yQpbY3la7QvQ4rk-AXvTGchGeeMdKjGDJzkOrEbdtjtRmyerHSUa8xWAUlVl7dgRFI=w512-h640"},

{url:"https://teechip.com/thankyou-068?name=custom-t-shirts-classic-lifestyle-front-330&retailProductCode=F1BC1B0006F0A7-9760B2187A5E-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjpMY6tW6PrHd0KfZdmsQUdUMsVhxqH0BfT2bzZ4VLqTb9tU_uHHoWaDPMtHgs3bh04nPdIG1eEWUN-tJpcVQ-evNfZjmk6CGKW58HtigVv_VcgNAX2JgF1sWeTKG_OCgizgvwpdJfKsSAMv3XXwtk4u1xZvxxSCO64DqkNF9y3v2-PCTs7kM3mjDu1IGvj=w512-h640"},

{url:"https://teechip.com/thankyou-069?name=custom-crewneck-sweatshirt-lifestyle-front-130&retailProductCode=F1BC1B0006F0A7-7635A74C2A1B-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEibNDKc7alhpHvxCwT-qH3FFIs2bN88L5icbwlnj3o3Jnm7n3gHeWDxCVt3UzxxvyAsF_9BKMa-OBIsGBYzETt3Fi3lqtt1zHMGvx1JxR2JSOpQyxY7JuDKtJbUHZBSj6T4Uo6N49ygI0kVaTtWT1ypvQoLxBtaWtYp-o624Mlc1LA4x1MZfB6GWC0hthvb=w512-h640"},

{url:"https://teechip.com/thankyou-070?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-B335A3582F4B-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi1_3BAnlPrKiLTJZhNCUXEHfyy4wbkOBAeoMHmXM2lZCXUeuSNSlDqhQ_Jo1Yg0iVbXEkN3CyReRBWSlIJ77I5iHcQzXlziIljgSyZnSLG1fB5g0SyKYzN8QwQnisfv2HatUSjN4oqW8EG9p9VtA5t9qsuRq_4_sR1L0FzsOxHWoQVR2XIDj6fRlPOE-1-=w512-h640"},

{url:"https://teechip.com/thankyou-071?name=custom-hoodie-sweatshirt-lifestyle-front-179&retailProductCode=F1BC1B0006F0A7-CB64B25C2F4F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiqz71QUjuMVqAA9XzNuCBDUQWbPuF7dSbB1Xe1ISpCgS6OT3bBnWk_Y-FfzhB98NrdrrlczqUieVefSXDXGMB-47dGylR9Fy34vHfuIocuZFRVfHvve6iulrRPJGHs3htdavHtacDKVcDgOm0Nth04Kx_arUznQXNR31glT2tSFl5LJ4R4SBoAtEP-9r3m=w512-h640"},

{url:"https://teechip.com/thankyou-072?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-2B31A6592E4E-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiZKvMHfFC96TyuNzWE1ZGUdK9hzG_-9PD2IDvCSnPJulubiMq4f5eesu_jVSj_0JiUUODwmgl434R7Dae-CWMGboQwXDiolFoF07CWW8FrqPhR5JyRVTtklktB7tJxpc02LXx-D_ggBc_sh5GSOKu54R2JrTKsLb2vTrjnF52S6HhFQ4WPGXuDRtkfnQlR=w512-h640"},

{url:"https://teechip.com/thankyou-073?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-EB74A2082E0F-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgjfvDylhX1krDgfTOiZqg3RmGq-FyH0fHIX0Om9Ck6dhJg_u8Hie03u66_GTCHoF2weoQ-ijBtMcwoxos16pYM9u6pkss6_3tpbIXxq3yqd4DOzwZU0EzNafL0FfGkI3f_YZ-ihpmPzlpgp8GlV_0lmGxHXpUvcbDYNqhe9PrT4B_I9x8J4zG2rUbY0aYZ=w512-h640"},

{url:"https://teechip.com/thankyou-074?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-15B1B64D7B1A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgDlI_gfrvrsHvjxN_iAagc34KijZxPSjjG2zIRfBx_H_Y0Fbc8CrP3ydz9NuZBtIQUzSl2yXDdHXH0qNDMn9I9m6lE0LMDZeij7HYaCj3JAAR9P2A7h2Zr6jGcp0ELel1r6FSSLye6BsAPg4xIe9VCARoYX9ocw9K4265FSPMYn8mgFvCE71NOrCj4mQ5f=w512-h640"},

{url:"https://teechip.com/thankyou-075?name=apparel-crewneck-sweatshirt-lifestyle-front-31&retailProductCode=F1BC1B0006F0A7-84F4E60C3A5B-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEid0GGSs7acBlSKnR2hJ09ujqwZ7h3PaRb6i22GQ60Y-aZraPrxU8G1VOu2Zho1eorRfa-eAFOncdHqJPqhJCa-Dvpz2g1ViqhK8Qxca5vV8gXpDFes-mEkZ00h6C5Be3h2dimrd_RVUZQek1-KJ8pR350fs97usCNomuZhNXwtZxlRgTDh_n8YzJ4idQxR=w512-h640"},

{url:"https://teechip.com/thankyou-076?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-71F5B6596E5F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgVjWmA35ASehTbzOJLMT0VEMUGFpOVgKTwtlq4hkd8HsgEngLLY4eQT7AlGmtzpbmyBL2Scrx6nvy_nUom1S7j-WZu9QLku57fM4EsJm96bAWqSZHtTBeRcFIxqgAVlwnhmZJD5gx8zSfCAOMDGcQeAr84oX8YPxUERYdK5TB702mwgDQvSuTnRheiruW9=w512-h640"},

{url:"https://teechip.com/thankyou-077?retailProductCode=F1BC1B0006F0A7-F4E4E24C3A1A-GS0-TC4-BLK&name=custom-hoodie-sweatshirt-lifestyle-front-179",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiRRirHDg6O2Qszha_pB6l77OxEQxt11PmEE2qxFdoIXUXos9SJArBoF0poKWNl3V7uuYd3woxxYlEERRifq1vMc3KXj9glZVw4NLQBlOIP92k_tnAVsIeT-4rarPubaYx9bHny2wB5zMqzrN_ZCOX-fkt07RBH6JJv4cPet-5np1Kebs351No8n6rDY5n7=w512-h640"},

{url:"https://teechip.com/thankyou-078?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-4CA5F6183E5A-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiA_ZX9dnBBRCskFCPb_6JbnmqMMXucD6IGcfYAq_HNbmHWXurvGHulmIKTWow5kojd58SbLoEJO3HLuNzvHEsg8AVwTvrikw5IT6vuQOpduxZuAz7PbV_0iATu041GH41iXxpT-gPBmI3qytoGDGaGEa2Cw0F93u81QCZp3Fc6eRP4U2St-5qpA-WRVtEe=w512-h640"},

{url:"https://teechip.com/thankyou-079?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-DDA5F2492A0B-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEicl7znW8lnEkUmfsftndNbrDgHvBuphWKdr4DXQHu3XtRNmiezcuV4uCKOk8zWMu0LChQWOQ7QA1AIuT7PGLPFE_iX08wTT80MRiKpD_aw7UcA48N04bHcjymcdkCAnphU7dD0LjZL5Nv7OfWCNTVmiCBzgaylrZK5HKgsmFOO-sbgASgA3UqZJlcEpgGS=w512-h640"},

{url:"https://teechip.com/thankyou-080?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-5A24B35D3A5B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjitPeDt3JChRVLyCaAj5I1NZwpor1mwK4UUvW4XqoGTrR_ErJOT1qkC91qULtK68j1OD4g44z8E6UXcWdIYMntohdfqG66C1hS6W1yCqbdKFeOc8nLPHNOvpfofJtqXW9yEjLGbJenqAE-_kIkp4MRGlAckdSshJaZcc6ad8EaSrbDGyUib8vEXm8i9XtZ=w512-h640"},

{url:"https://teechip.com/thankyou-081?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-6DA1F2092E4F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiyLYLBcRfzKMzebDG7fPUT6hVJGDkH2lH345vZI3B8O7CsJ2p4NrgHBy0scA5CXMktb4DOFLsmJA7Ecy-FRRdIGspK-YTd0__Ds-OYZk9pAO2bW9209WQ0oGN62OA8phOo_wo8KqYFrae5c06mVa7bq6_6TySnyqJ72IqNY2o-HTeh7iP6nskbKxeKTru7=w512-h640"},

{url:"https://teechip.com/thankyou-082?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-B9E0B61C6B1E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgY_L_mxcqrS87U3MM-kr8MXDY9w1vqlYMbmv-hMRFC1QrL2snyublMvIsd73IsBya-82WfqmpXeyWlHL1xa8xhBYkrBoCCgPeKzXJ-Bk4sVkym9JP5c3X49LavmmWyDDz9wLAFJvf5jMWKE7RNhFGRA7JkEMaS337sfXxDhtBLep4nES1wgRChr-TJWQK1=w512-h640"},

{url:"https://teechip.com/thankyou-083?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-53A4A2486F1B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEj6AmkmgMZsqHhp4wim6RR9IJQurMCW4-yfmB9qGZkFcRuw73ifd20Hfs6rJ8wlEMdBEz_yLFAxDNctGDE1YpDm58z88cHnfTWXZVSdLRsiNIbY5Pus6WW0NrRFL1RUe5tTHXGpc_MszJpjW3JyEBn4Gjrt0fCbZRLa0Du5QSjJOtGhu68YoOn0R8tCwUk2=w512-h640"},

{url:"https://teechip.com/thankyou-084?retailProductCode=F1BC1B0006F0A7-C6E1E31D2B1B-GS0-TC0-BLK&name=custom-t-shirts-classic-lifestyle-front-451",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjgOfEz9MF9Z8OrJkc8vyNeykippSNcP9g9AHrXRSu2GmK0rdwvRiquOTcZ2TpkQ_7PhR3Z06W6VKSrHzo7ERjWuzjr0eK6xWTaGC3gBIyznC4J2gob-vqB3jZLGxgAk86WxGkC7wig8ef9LlpOXD23fchk5ANdBUbBaazqCfiCbQSatgk4KJOQaSqlfAXz=w512-h640"},

{url:"https://teechip.com/thankyou-085?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-76B4F3496B0B-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjrmOdeGxSIdoiJs6ywI5J-3x2x13nLqN-Uo5VTlElzLLXT7QgAT-uXWiOepwLt1FlZQ5R6vUPkbnpF0xF0GfWAS0znocNEBh5TaOppltXHhHoa3i-re6LcK_pg3b6rdgMui61kgXR_rCah8THYVLZR8jEpMW2bA4lF2mFSR_7J-X_iAb5qhFF0pvNIyxnl=w512-h640"},

{url:"https://teechip.com/thankyou-086a?name=apparel-crewneck-sweatshirt-lifestyle-front-90&retailProductCode=F1BC1B0006F0A7-E780F74D3B0A-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhVTSjUkrTkNzkIHjYzhNQNPRbpopL0-Xhm4yhpUsiad43uExH1HUiQS7DDQd9N7nvUacXPo3ex1440Ky8kULv0OpReUc2CxwgWOnjg_YHQIBVF35kJCSGpmDJZTu9ZBEha_SdpxzONdPvrfXuGJhL8MWEXBYCnQKzHsQddLn2vdsuSQ4plQcH-i9UOA8JX=w512-h640"},

{url:"https://teechip.com/thankyou-087?name=custom-t-shirts-ladies-lifestyle-front-112&retailProductCode=F1BC1B0006F0A7-5EA1A3593B4E-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgiDf0fh0Ke784DGouru2NV_0hwIMpRKRITdATgUoRjZ2IES-8kg9koZuj1RGv3-OC1eZA477N7oMncIbVZtrBiFA7tOmLJrmmOtGJoYp6MR6n0VvIul7Bt4PSLyzhC_YmNlu4ofzvlZTpS4vNGdnbG_KOnjJPWqYnULUjTgP8YV3Gntp4xyrSqAg77gHtx=w512-h640"},

{url:"https://teechip.com/thankyou-088?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-8EA0F3183E0F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjU3xM__6_UZ88UwZ1YpUsxG_hyC7JmlPZmjQvgzcqtFxWcKUo0zmDv-uR0P3cJmwqHY1Yy7HiUx4Hq8xf6itJ3gqN26Kiz0WZAwXlJaiM-L7BL49S2ZyXr05ur3CEqiCB5Iz8KXG4A7ZHVb1UIdfmONmmXvkcv2sr_EwMjD7Fs1b6ENODeOR9SW7klu8Jd=w512-h640"},

{url:"https://teechip.com/thankyou-089?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-7BE1A3182B5A-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEg_4FrNPWVLZK_n3h8GJHGxsE8GZPd33NN5DCfAGsPv2dX5YZac3AsMzJiot8ydFQzLPBpoMMznh19gyt-oXLWuLcRYqSbMq1f8AuTikpEFGiM6DjDqoTPM6sMEs55VzESy1wEbgsNJLIGMfY_Ku6aoEs5gK3gISrfI23xfFkHBy3O7oZJQT03uFiHAajHq=w512-h640"},

{url:"https://teechip.com/thankyou-090?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-EFB0A65D2B0A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjwE25X65_5_wQGckmaPeram5wZDHOobxki8K2EjXzPRr2edMTxm2nGftTx9soWgP7QVk1oMr4WgKO6C6WTEt79H8THbajkSrVNfAIddIN12DYbXkR0tSEkpwYr0QnrS46CXwCgf8MJGUDeh8UCQHyjwPxVgpCWfyBv4RjIeL8YaIsHJjUUqgf_XKAywbNv=w512-h640"},

{url:"https://teechip.com/thankyou-091?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-0404E2087B1E-GS1-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgKiROxa9nCEhaZ5tYqycTm9djo-34WAOBO2zP6_le1x89uNtgANqK5AeWE6QyE5jebkzfGUTGD1A6x2SiPDPuwTyouhYCm8FThTpLJtRvmqIUncXqRH6nhjVHfpRfbNYYWDeq-oV8NKffCBh0sjERjIqsP5ar8wlSR9un1oDdoNCCLJDC4qi5LIP55pLq9=w512-h640"},

{url:"https://teechip.com/thankyou-093?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-7551E7596A0A-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEieJ_RPrCa_i1v3pxo-36nhplFk5UdR7QSO55HqdcaXEfZ0n4UWDDGF1sWRFN-PpgEmYCaUkdE4JTDd1kSN6SZXtC0m6pGr2YU3y8d6MR5hERNf-zD9FAEd17lD69GyHquGwffCIhy7kW4P6RWbvwIOlX9nvfPCyOqJaLkQNEDQbVwid-NXeZ1-30-NCAqd=w512-h640"},

{url:"https://teechip.com/thankyou-094c?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-1CD5F6187E4F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjX-g2mSLJaOZzV3GBK-KRgbSAd6dpMwNGdsJliZxxl7dWkyII5MfZuQ2eZz78S6MhFPNZGze7WfZKPNjT7nwuDkL7o3BUewkbXRtrPO3wQ-EhdTlczvsefoTzOp94Nx-Amhv6Qr0hDWWpSO7zFMXvom3Nur06vcjD-81SY7a4CZRymG__FHVkW99i_j4IU=w512-h640"},

{url:"https://teechip.com/thankyou-096?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-DC54A20C6E4A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjAS_sfXm2a7YSQ7sZ4rgsOWET-fRLtcxwrpfruUU-iKOPEWEdxUhlW4TYvL9Mrjb2IO2TbdhL8f7NDKgLSwt8hr9-YMBa1Ksg6w8HbzbfvwvL7JKNSGTyWIGmU6k6w_JYniP0sHkQIpf7M8dsdEPbdPFeSRwYX89YaMb7AZjsiLf701sU7iyqByJhytDup=w512-h640"},

{url:"https://teechip.com/thankyou-098b?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-CD84A7092B4F-GS0-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjTk4QProDCyDQ_o1CNhVh9VuGPUZm_eTerICKpO8UcA7mWTHP89jgdDrXLh4aGgU-Qr8M_ciyEWuTEMu5eSu6L8XGa-AwlncCTeO4MNsCXR1N4woYWVBu-txSPJ18HnzPP2am0NQ2NN5eb1KDPUw7sjp3mQzyLrBhjxMa65qOFSBIOBFObVKTO6JB7I6w5=w512-h640"},

{url:"https://teechip.com/thankyou-099b?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-3CD5B74D7B0E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgu9yPKG6g29M02H9dHIHy36GgVSh-whdqWNJa2bOG07oZrCqIFgVmJFzBepBZUiLZSoktQN7pNqdGTJdcOQqwU_EkLe3hQjKN5lWXrCzNAThk-3nPMCuJi306G24xiM_ZRpl1XXUrIzJrDu2WezRlTbyouKwMr9BU8icIGovb_q4YBPuwF2mvGhNJYSRna=w512-h640"},

{url:"https://teechip.com/thankyou-100b?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-B9C1A6093E1F-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiB-4y2ewtu6OymP4iurSp9ICamNxwMBwceX--sYIC8L0TdQurQUot0E5y8TY5aW7BgX23TNT4fNtnUhyO0Cz3fZV7__8kFUwlE_CN_PUFqPXkJc-9rcvsXVx9eCvtq1esVCtlRAskzh6KqGhq4Pye0hXxYIbuJ89qYrj_KcD9FoMjmTFtigT6__QQGPDeY=w512-h640"},

{url:"https://teechip.com/thankyou-103?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-3284F3482B5B-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEh0JcbRBTMzVoYLFWpIabHcgzWQKP8Y17iOysAsNQCi-obQ0ZSBd645Qf76kvgMuZ7pSYoXJzTHPE16zublYhDXWZmbKL0QSFGQ0yc2ZILUsGeueOcz9gbXcGbN5IUs4kjqZWDcdxwwzHbG8B5lgFq5Qa0w56WKd3XgI-dX4pt2V33_f--suBJUu5ZbkHKl=w512-h640"},

{url:"https://teechip.com/1000class-005a?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-4165A75C7E0B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgnq62Qq8I9cCpJZQBrNhWH6gjMp4zRRxzjDSXQYB0jH1ifzBSM626bXAHOAy-UMoUUc62CqmDo1LQFPe8WCjfEAgNbF57bEq5SAmBPWF1-0TlH2yuUSZJ6-aEvW8KwFhPD2W_EXOpT--mztfCkkwRUggcemh5ngVWBZ27VZTIEFTumsNClcYDuDC0dt7b_=w512-h640"},

{url:"https://teechip.com/1000class-007a?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-D165A7087E5A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhcNDz2ShKbnVmYkSz8SRmbILg5IS0zqNQSl1ugReGhhqkhFJxVoIDB3Eum4IB8Gfg7P2lMw8hW7OsuHl7jFyPe-Sebk7lilCUVOsGcuAvck-Vpe-MkdMhhKtQGPG4wxqDHy--ZqpU4XofbFLVb8a_6WLmz-7v1CscKMT3V9mrXtGggvfMtF4_FPM64sLF_=w512-h640"},

{url:"https://teechip.com/thankyou-029a?name=custom-t-shirts-ladies-lifestyle-front-92&retailProductCode=F1BC1B0006F0A7-189A73483F0E-GS2-TC5-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjOWc1kfpzBBUQ_vY7En5PT-RXa2jiKqhEIhFLM_6gpMcWrS_c01l_axPjt8_sZWDpjDDhUKjSF604UWRhOL9el_6SbqJgz_CaEPd3m0lBlQXfips0ID6NkviRMr-npRhqHJKXy9R2tkPNLNvGw6w3TiNknQsDW3ds0I02AKH23p8IxpvAp9AwYY3D1mwEh=w512-h640"},

{url:"https://teechip.com/thankyou-030?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-22EF275D3F1A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhdoO3_X7ZADi7Fxwiog_1wRib7WhI_Oum-X2pZKq7MymgAiTTHR9wOEngyXUIwhv31Hu71AInmWLWGG2XTwJhgSaTDBCGNMf-GL9__e5IaSJknbQOL46iBUasveIhve6Yvnwa9ZgwX1F0_AKei1XTIMj_9UkMwRG98wc_H1cDPdfns3ne-dpmVpI7KvA0I=w512-h640"},

{url:"https://teechip.com/1000class-020a?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-283E76596F1F-GS1-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgWH334e7A4WuVaA0l_jxMLM5o2TV2KCHJHeuPfa4cUNQyp3npPmwFbvf046yNlZZx6K5rhXvXAnVn6lz5i9Ru372bKzzQ5viCnfnfGXLN8Rnh7oorCubdIn2l8f52rwPq5NCJTq3nrPfXXy1ATvCRm6e0N63BsoFfrGGFsbjEEtzb-ysUwhltVdpu0QMRb=w512-h640"},

{url:"https://teechip.com/1000class-021?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-0D2F621D3B4A-GS0-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhlQ4ZG6-Ji0fAQCWYfCZ77kAj95Oa0WkzfwFkD5lPU-4xj95lPhj13Q3RnFalHx1H7VW7CwXewb80qhLJYUwmTvEKZIKjIrxSANJT6Rpo7xH_KsDPc8sBfLomw6lDCDS5TTde4lTp_Myk4KxTS4QAiqiyy7jjPuKWmLAyXC4YhqD9BlF75Ixzy9y5vGNJo=w512-h640"},

{url:"https://teechip.com/1000class-003?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-4A4726082B0B-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjlhdSVXf_O5pIaqQEmOmOagBDS06EGEyHzGZxaDji9Ly5th5_f1zh8j0u1rv0H3kaXK81UuqSe3RglcK13Dzleg1-dLksULU65wyFUcrkJpLc75y3mjdhWB43JZohe3ivc29Fw1NkE97BTB9BDOSAbT3IHNNbUM4Uqkt4b4aFjvRWKLFS4Raxo0sSiaMqD=w512-h640"},

{url:"https://teechip.com/1000class-011?name=apparel-crewneck-sweatshirt-lifestyle-front-31&retailProductCode=F1BC1B0006F0A7-499237182E4E-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEg65CkUAycy-nJeHhu9ORW3txpSHoADRfOMBsB-0ukPLKzfqN2t9RbHvBTM9LCU2eWyhLo-XcwhTaTVAXz01xliXZkQai8TtYElNmOvczb4cDsR76o8Qb-rTlM6M7YROx5Zfz_9C4hrneA9mzFwN-RLLnDAhIuNr3Xxx3Btg64xH5cAJOuHs2-EtRiM8i5B=w512-h640"},

{url:"https://teechip.com/1000class-011a?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-39D3361D6E1A-GS2-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjuzOiMc5a0kBQc_q3K3sSVx1mcro9k0HU9MR0TwNADmSUcfh_XVUUyZWBCC4Ff42BxVigo6Ecf6Ypqzra1xp_XPZDSVpXHLDPkqiN63yIraK5XlsXdF-AySAA8BdvUkcx9Rdf-g0YyVBqdY_MZhcOuap_dZc-F5XWyN_4tuLnjsRXMZBusM6Q1gZ2f6a2M=w512-h640"},

{url:"https://teechip.com/1000class-008a?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-EC87324C3B0F-GS1-TC0-GOL",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgTiGQcimgYtLLFlJi4ll8MS-9sh1CEEiFJ1y8oNrYExufK--VFsC5xioXFsEwnw5CoMPbYbL_tPEUCx71jyh1V9EId0ir33YR_anN5WktgC82DKwTzTj2tZqPNoxjl_AiOlYCNSU22-0DvRv3efRME1o3UrAOLEH_DAqNt5ZJr5_1sHbGltJMz5WKxCnY-=w512-h640"},

{url:"https://teechip.com/1000class-009?name=custom-t-shirts-classic-lifestyle-front-407&retailProductCode=F1BC1B0006F0A7-70C2275C6A1E-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhpaWuOYF0I6JejH0E8bmC834_qDVTpYQzkrkigtmS7vQOXMUn13gd9LvWQo_UgvgHUi6fq2XmQv29XJXpH2kFaYkk09l-YQFIHKAzSz5CboGe68dH01spGTnc0gJbtPWljbMRVo4p2uVGCVXcvZQitPoK-iwz3YYjvfPq-KisyVQMOKi5gKn5wHeaTiMNI=w512-h640"},

{url:"https://teechip.com/1000class-009b?name=custom-t-shirts-ladies-lifestyle-front-112",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjlvHwgWGaOOZ7L4LMsRCLYs3AJlY623d3gq-Shn11PS8Gjlm9yyADQd2jJsGs6QcUq564zc1wT4HQZKjKABiiUWaqaIB1W-QjvGikUXMW3j7cQsHyMWsgmE3wgdPHuSISu1rMuJk-0Yoqs_BM48dfxXRXM5kxqQMH7TPV6n_RGvqldXRW9U6whiYL2_JF-=w512-h640"},

{url:"https://teechip.com/1000class-019?retailProductCode=F1BC1B0006F0A7-613B77196F4E-GS2-TC4-BLK&name=custom-hoodie-sweatshirt-lifestyle-front-291",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhqWDhzRj9O3FFElO8PI-2dgxvKIfezasI5WxP_DJFgkWMoDZ3e8gQrjucEQwNDjLhJ4qS8BHJwI86fEMNfA-2kXySz-PW2w1uWAAGunLEm5tsPogL4hxrOMAqY7kdwVVb84L1Aea9esKQPEp87_0ttA3rEMh9i47WFzju0nB9bxNIz5OBPCOf5qFagbueX=w512-h640"},

{url:"https://teechip.com/1000class-010a?name=garment-youth-tshirt-front-lifestyle-01&retailProductCode=F1BC1B0006F0A7-9C9637483F5A-GS0-TC17-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhsLbN_NlOPIK-XFyA0Mdw1xD-kAioB9ihDejFHVrdBugnaDyWSKsacIbK1FfAZaNo35kBTGOFnQj5_O6sqF9jxLyTBowEW9OB4TwjHvFmRgWylhQkr5w8DXMEel01TVFHgqWnqN2Z7jIkIRvoRh0ASq94P7_XENHeyCqA1tneoSSrgTUccjFB5cBSdq_xO=w512-h640"},

{url:"https://teechip.com/1000class-010b?name=custom-hoodie-sweatshirt-lifestyle-front-291&retailProductCode=F1BC1B0006F0A7-D6D3235C2F0B-GS0-TC4-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiBAbcv2glxFKSMHAvtVrhpeMC8I4z7tx9ZHZwhcQVig9JCKHG5Kj7MJqJMR-mLJiSspYfFvl3DRgymY-2rBYstIwHJI4AbEcvXuW8Ze42FjjSOIf_zveW85akHp7bKf8LO6fPfNGnz4gunMqkjsyabbTiAUMs5G9v030kY8BnniuIrXjft_zz5Op-iQgW6=w512-h640"},

{url:"https://teechip.com/1000class-018?name=apparel-crewneck-sweatshirt-lifestyle-front-40&retailProductCode=F1BC1B0006F0A7-907E660C3B4A-GS1-TC12-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhY0LuKDz80Hio1jSpvxJBOh4yDsy_02wa7v_m-zFoKZEX1SHWVj0BfnBvHqKpqoXzWns0aKUBZSdQdc9lfWzFnr7gRIw0sUsW6_48ZQTzez5QoBblM73KIaJEZf3jd8NdFwpsm9JgAdFkJcAEFCo4fiTpVR6YwioLAp5n8pdVvXJUJTBtIXJRyJgSEMeU4=w512-h640"},

{url:"https://teechip.com/1000class-022?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-D92E72482F0B-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhsHu_SunE8dOH82rXJTsrcua_oNzOZVzaGiLztaf-eVQCG86sKxuMKImMttDWYeuPmTEWouusURkr7Cc2-msEClKNVZDHYSbaLmkFtGOgHluC0RPxKOi27XYWOITnDYo-0YQmeM1bgs0aF6OeMGI7hApr81eOMyrK605_xw-QCxFPgVsJOzcMMrHbZOgCF=w512-h640"},

{url:"https://teechip.com/thankyou-026?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-99AA72192E5A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjsHkpRZ5IKusKR1n6snzg_tb7tSHBg21TATsuIk_5F1fNWbjHfzGiQREAQjW6juR-yFdS7QxR8QfK1_hVtJZ3MkbMZcjYnvzQBvjzmBbBmIWo4lHhEMwm9qiaHtvLaUkRrwbmW5oySS5PbQ6SJz9_gsIIBORfeOfsmrSCIE7pxzT8B5tdmRmKq5v9YqnW-=w512-h640"},

{url:"https://teechip.com/thankyou-118l?name=garment-youth-tshirt-front-lifestyle-01&retailProductCode=F1BC1B0006F0A7-F109F2582A5B-GS0-TC17-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi823jZFT6A2m9eRcoSiCUAoBN6JOcc3G6yesbsyYKGIVCaegboLqGUi5hUvoYQjrhrAXd7CR5OqCY2ZYEqJkZKpNmEYg5lVJ3O3UatsygKxcXIBNlC03CzlXcUH-u6G-1iLTBSDg3zTEDsYCgbUHfnsXWs_gAQT4qjr1Os_G-jqr33Fgl8i482zlWE5S92=w512-h640"},

{url:"https://teechip.com/thankyou-118k?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-7448B65C7A0B-GS0-TC0-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEi7sPxFfBsl6oHxyBY1kR--MZPjGIkhWXyPL9EGpoEJHt3Ua_MEPsr7hMPQ69tNLYkqnnm-XtzIKYeNpHzZJFALVOK8sTd10T4JgIpcdcGUyHzmx7g_dzsYLlECexJdCUQ3VlY43tFSY3b2-nK6E_xoeDjSaFmxQQI3xYdBDeh7A-Ivif-sjTjjF-3aixJa=w512-h640"},

{url:"https://teechip.com/thankyou-118i?name=custom-t-shirts-ladies-lifestyle-front-94&retailProductCode=F1BC1B0006F0A7-C508F3486B1A-GS0-TC5-PUR",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiFNpXw5E2BY44AAoJGABeJL9YZZjVhD0kMv0T4yBXPDL0J-eBRBWpuAJWxtY5Bq6W3lDYGWPbZ3I6zJzw--RIkWIHPjf2qPvy2Ikce7eWCD_SxU5zYI_Y0vgkci868685BYjSf6B8wUOhF9daa-MEDmVX-FpNhx257OCg5SM_ZxEHG1AGohfKkuoTldkvN=w512-h640"},

{url:"https://teechip.com/thankyou-118h?name=custom-t-shirts-ladies-lifestyle-front-112&retailProductCode=F1BC1B0006F0A7-4549B34C2F0E-GS0-TC5-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEgXIh15jZUMEb2HJyEUtPT2gOs16QJpnnYp_XKqk4LI3ThpgU5l3-78zvqCQ4CH54poGkc0MO6PSJe5JIrKM7r3KX0kpSp-i8BAAmR5ZX6dkiiQjPYCTfF6Qckw6u8jRsJmI9l0lk0-KabgcRC9t1_sCgyv_tDN48PA_3XnTlw85iGrlQaXUVEuk9hXQGs4=w512-h640"},

{url:"https://teechip.com/thankyou-118g?name=custom-t-shirts-classic-lifestyle-front-382&retailProductCode=F1BC1B0006F0A7-AEBDA7592E0E-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiZf1Ub9pPmL-kyiHA7keyY_Nf1j2t3pHBwn-bqDSi0wy4-_vf0o9fp-FI_tJYWqHc85QJJxbwM93RopeU7f6OzKsibnZiBzi-dlsHw4ZAAURCz8PxFBMHphqaQ_AE4-NP9BVxGGvdww86qEWEm8BwM39FANDksO4aWeGS0LTw5wZpHI5VEpJjVnB145LgQ=w512-h640"},

{url:"https://teechip.com/thankyou-118f?name=garment-youth-tshirt-front-lifestyle-01&retailProductCode=F1BC1B0006F0A7-2FACB6497B1F-GS0-TC17-ROY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEidCYJgUaxqA6kPFZ5ngrMOq8-zvefzN_iCcMDJfK10FT7wpyH3ozsfsjMgQ39b-lNNL4vZYQTxF3WCMbcdBzfm55btDhjxU214xwkooEYQSf0zIo2j5sHkUcSXWsiknFjfLEv9iA42FRLwVeJmKcoXe0VBe481AYbuEkKvIZBz4bp2Hr6A47fBvgZ2_iLT=w512-h640"},

{url:"https://teechip.com/thankyou-118e?name=custom-crewneck-sweatshirt-lifestyle-front-130&retailProductCode=F1BC1B0006F0A7-CEBCE64C3F4B-GS0-TC12-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjpcfSCtWq_W1iOsFVIwhrGg-YEG33ETLDTvCAxB_I7sfRh6yI6Bl8YJ9yucZdjWIoLoPd-GCvpem5qfVCPEETsGv3kKalkeekk-IvaBDn4eGHdDj18hUGPYfmah9LZRuowQlNXrL3-PygYvGjvsGAQ7D9urXYQnm-ZCi1ZmSrTtLTRZJwdNZqmAz8Sut7R=w512-h640"},

{url:"https://teechip.com/thankyou-118d?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-4EACA24D2F5A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhB4EqNzS0ZJBy-Vvz3_LSkSAMKKqIJM9-cCEMizvzAsoF9LDL9uhEFLF48Pvkw5aB8P2ZhRl50-mYjpDLIj8bsX25oSSjJaooCMwvmL62CIyJ-fHuIY6_0gaOCROEkfY7YuiNyNIuJgwVQkrOxxCk_t84lwZd3Wu72nWqoxsG_ugSqyXyDqVXDCowTQy1X=w512-h640"},

{url:"https://teechip.com/thankyou-118c?name=custom-t-shirts-classic-lifestyle-front-342&retailProductCode=F1BC1B0006F0A7-B2ADB60D6A0B-GS0-TC0-GRY",image:"https://blogger.googleusercontent.com/img/a/AVvXsEhGFfySH0h4GXaOV6mXj9Hca5liyvxaoJERgDbQdANPJtiW0EYb4Sye5ZXp7Z2Ukcpo4X37nJ1YywMeALM3btgNj-ND6S1miqbzVLGImTNIQp8JSWMNF_8J-iuJsROnDMmS0P7Vz4oeH_yz-Y0ke0Gw6BY9kcqEpn2Cpsv4RkMCESY8fsFtEyMczTAp1XiN=w512-h640"},

{url:"https://teechip.com/thankyou-118b?name=custom-t-shirts-classic-lifestyle-front-451&retailProductCode=F1BC1B0006F0A7-72BDF2497E0A-GS0-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEjxQcnTWc6oY3AUbafE_DrIA-M1BiHYQxkkPTahzrETzv8s7B6zwUkTy6aDPXqYnN48VVcmmrpEv8FPhz1e6whGIqmU__Xz0VWcRy-K6HcMzj35ne-nz5MmZ4fxWZ9sXki2G8N8EdC7d8v3M5d6Ma8CeFN9iFCgdJgHDMIuUyBYAffZVVuyj6Cf6HLN5ipj=w512-h640"},

{url:"https://teechip.com/thankyou-118a?name=custom-t-shirts-classic-lifestyle-front-376&retailProductCode=F1BC1B0006F0A7-C3FDB2497E4B-GS1-TC0-BLK",image:"https://blogger.googleusercontent.com/img/a/AVvXsEiXbjAF4texh_Z9ZAC6ft6M4kNsZGutGAG2DQbZHYDde9VD4ZSOv1UEKfei3akrqeqBLQa3fsEfDfTeBqHvRXvlNj0ONt1Vdzz85zqqSZqt1gcG3SZ3kRZtfxhOIflnYFi1SIZ8g6KIuJRdfxVZ1gnh7JwLl1iEj0HaKpT6vAFju19LhEatjNAyWTY6yxiv=w512-h640"},





];const container=document.getElementById("product-container");products.forEach(product=>{const productHTML=`<div class="content-box"><a href="${product.url}" target="_blank"><img src="${product.image}" loading="lazy"></a><div class="caption"><a href="${product.url}" target="_blank"><b>CLICK IMAGE TO VIEW DETAILS</b><br><i>many products, colors, and sizes</i></a></div></div>`;container.innerHTML+=productHTML;});</script>

















<style>
  * {
    box-sizing: border-box;
  }

  .center-container {
    display: flex;
    justify-content: center;
  }

  .embed-box {
    background-color: #FFFACD;
    color: #444;
    padding: 1px 18px;
    width: 100%;
    max-width: 750px;
    border: none;
    border-radius: 25px;
    font-size: 15px;
    font-family: Helvetica, Arial, sans-serif;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: box-shadow 0.2s ease-out;
    text-align: left;
    margin-bottom: 20px;
  }

  .embed-box p {
    margin: 0;
    font-size: medium;
  }

  .embed-box p.title {
    text-align: center;
    color: #800180;
    font-size: large;
    font-weight: bold;
    margin-bottom: 10px;
  }

  .embed-box b.highlight {
    color: #800180;
  }
</style>

<div class="center-container">
  <div class="embed-box">



    
    
    

<p></p><p style="text-align: left;"></p><div style="text-align: center;"><i style="font-family: helvetica; font-size: large; text-align: left;"><span style="color: #800180;"><b><br /></b></span></i></div><div style="text-align: center;"><i style="font-family: helvetica; font-size: large; text-align: left;"><span style="color: #800180;"><b>Thank you so much for your support!</b></span></i></div><div style="text-align: center;"><i style="font-family: helvetica; font-size: large; text-align: left;"><span style="color: #800180;"><b><br /></b></span></i></div>
    
    
    
    
    
    
    
    
  </div>
</div></!doctype>





</div>

<script>
  // Hiển thị tiện ích chỉ trên trang bài đăng Blogger (URL dạng /YYYY/MM/post-title.html)
  document.addEventListener('DOMContentLoaded', () => {
    const isPostPage = window.location.pathname.match(/^\/\d{4}\/\d{2}\/[^/]+\.html$/);
    if (isPostPage) {
      const boxes = document.querySelectorAll('.post-only-box');
      boxes.forEach(box => box.classList.add('visible'));
    }
  });
</script>]]></b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
      </b:widget>
      <b:widget id='HTML6' locked='false' title='LOCK 24H - YOU1MAX' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'><![CDATA[<style>
/* Lớp phủ */
.overlay {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #fff;
  z-index: 9999;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  padding: 20px;
  box-sizing: border-box;
  opacity: 0;
  transition: opacity 0.3s ease;
}
.overlay.active {
  display: flex;
  opacity: 1;
}

/* Hộp mật khẩu */
.password-box {
  background: #fff;
  padding: 20px;
  max-width: 500px;
  width: 100%;
}

/* Container ô nhập và nút */
.password-container {
  display: flex;
  max-width: 500px;
  border: 1px solid #8736af;
  border-radius: 8px;
  overflow: hidden;
}

/* Input */
.password-box input {
  flex: 2;
  padding: 10px;
  border: none;
  border-right: 2px solid #8736af;
  font-size: 16px;
  background: #fff;
  box-sizing: border-box;
}

/* Nút mở khóa */
.password-btn {
  flex: 1;
  background: #8736af;
  color: #fff;
  padding: 10px 5px;
  border: none;
  cursor: pointer;
  font-size: 15px;
  font-weight: bold;
  box-sizing: border-box;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  display: flex; /* Dùng flex để căn giữa */
彼此
  align-items: center;
  justify-content: center;
}

/* Trạng thái đang mở khóa */
.password-btn.loading {
  opacity: 0.7;
  cursor: not-allowed;
  position: relative;
  pointer-events: none;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Hiệu ứng loading - vòng tròn xoay */
.password-btn.loading::after {
  content: '';
  position: absolute;
  width: 14px; /* Giảm kích thước cho gọn hơn */
  height: 14px;
  border: 2px solid #fff;
  border-top: 2px solid transparent;
  border-radius: 50%;
  animation: spin 1s linear infinite;
  margin-left: 6px; /* Giảm khoảng cách cho mobile */
}

/* Animation cho vòng tròn xoay */
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

/* Thông báo lỗi */
.error-message {
  display: none;
  color: #ff0000;
  font-size: 16px;
  margin: 5px 0;
}

/* Text */
.text-content {
  color: #333;
  max-width: 500px;
  width: 100%;
  margin: 10px 0;
  font-size: 19px;
}

/* Responsive */
@media (max-width: 600px) {
  .password-box {
    padding: 15px;
  }
  .text-content, .password-box input, .password-btn {
    font-size: 14px;
  }
  .error-message {
    font-size: 12px;
  }
  .password-container {
    max-width: 300px;
  }
  .password-btn.loading::after {
    width: 12px; /* Nhỏ hơn cho mobile */
    height: 12px;
    margin-left: 5px;
  }
}

/* Ẩn thanh cuộn */
html.locked, body.locked {
  overflow: hidden;
  height: 100%;
}
</style>

<div class="overlay" id="passwordOverlay">
  <div class="text-content">




<!-- NÚT "BACK TO LESSON LIST" -->
<div class="button-container">
    <a href="https://you1max.blogspot.com" class="custom-back-button">Back to lesson list</a>
</div>

<!-- CSS -->
<style>
    .button-container {
        text-align: center;
        margin: 0;
    }

    .custom-back-button {
        display: inline-block;
        background: #0ac3ef; /* Đổi màu nền nút ở đây */
        color: #000; /* Đổi màu chữ nút ở đây */
        padding: 5px 22px; /* Kích cỡ nút (đổi khoảng cách trên/dưới và trái/phải) */
        border: none; /* Bỏ viền nút */
        border-radius: 8px; /* Bo tròn đều 4 góc nút */
        font-size: 18px; /* Đổi kích cỡ chữ ở đây */
        font-weight: bold;
        text-decoration: none;
        transition: transform 0.2s ease-out, box-shadow 0.2s ease-out;
        animation: scalePulse 2s ease-in-out 2; /* Hiệu ứng nhấp nhô (đổi số lần nhấp nhô ở số 2) */
    }

    a.custom-back-button:link,
    a.custom-back-button:visited {
        color: #000; /* Giữ màu chữ đen trong trạng thái link và visited */
        text-decoration: none; /* Ngăn gạch chân trong trạng thái link và visited */
    }

    a.custom-back-button:hover {
        color: #000; /* Giữ màu chữ đen khi rê chuột */
        text-decoration: none; /* Ngăn gạch chân khi rê chuột */
        transform: scale(1.05);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    a.custom-back-button:active {
        color: #000; /* Giữ màu chữ đen khi bấm */
        text-decoration: none; /* Ngăn gạch chân khi bấm */
    }

    @keyframes scalePulse {
        0%, 100% {
            transform: scale(1);
        }
        50% {
            transform: scale(1.1);
        }
    }
</style>

<br />






    <p style="text-align: center;"><b style="text-align: center;"><span style="font-family: arial;"><span style="color: #800180; font-size: x-large;">Enter the password to unlock the lessons and verify you are not a robot</span></span></b></p>
  </div>
  <div class="password-box">
    <div class="password-container">
      <input type="text" id="passwordInput" placeholder="Enter password here..." />
      <button class="password-btn">UNLOCK</button>
    </div>
    <span class="error-message" id="errorMessage"></span>
  </div>
  <div class="text-content">
    <p style="text-align: left;"><span style="font-family: arial; font-size: medium;"><b><span style="color: red;">Note: </span></b></span><span style="font-family: arial;"><span style="font-size: medium;"><i>The password was sent to your email by</i></span></span><span style="font-family: arial;"><i><span style="font-size: medium;"> </span><b style="font-size: medium;"><span style="color: #800180;">You1Max</span></b><span style="font-size: medium;"> when you first </span><span><span style="font-size: medium;"><b>subscribed to receive courses and updates 100% free</b></span></span><span style="font-size: medium;">. Please check your inbox again, including the spam folder and promotions folder. If you haven't subscribed yet, please </span><a href="https://home-you1max.blogspot.com/2025/06/2.html" style="font-size: medium;" target="_blank"><b>CLICK HERE</b></a> </i></span><i style="font-family: arial; font-size: medium;">to get it now.</i></p>
  </div>
</div>

<script>
(function() {
  if (!document.querySelector('.post-body')) return; // Chỉ chạy trên trang bài đăng

  const overlay = document.getElementById('passwordOverlay');
  const passwordInput = document.getElementById('passwordInput');
  const errorMessage = document.getElementById('errorMessage');
  const unlockButton = document.querySelector('.password-btn');
  const encodedPassword = 'eW91MW1heA=='; // Mật khẩu đã base64
  const storageKey = 'blogPostUnlocked_' + window.location.hostname;
  const expiryHours = 24;

  // Giải mã base64
  const decodePassword = (encoded) => {
    try {
      return atob(encoded);
    } catch (e) {
      return '';
    }
  };

  // Kiểm tra localStorage
  const isLocalStorageAvailable = () => {
    try {
      const test = '__test__';
      localStorage.setItem(test, test);
      localStorage.removeItem(test);
      return true;
    } catch (e) {
      return false;
    }
  };

  // Kiểm tra trạng thái mở khóa
  const isUnlocked = () => {
    if (!isLocalStorageAvailable()) return false;
    const unlockData = localStorage.getItem(storageKey);
    if (!unlockData) return false;
    try {
      const { timestamp } = JSON.parse(unlockData);
      return Date.now() - timestamp < expiryHours * 60 * 60 * 1000;
    } catch (e) {
      return false;
    }
  };

  // Mở khóa
  const unlockPost = () => {
    if (isLocalStorageAvailable()) {
      localStorage.setItem(storageKey, JSON.stringify({ timestamp: Date.now() }));
    }
    overlay.classList.remove('active');
    document.documentElement.classList.remove('locked');
    document.body.classList.remove('locked');
    errorMessage.style.display = 'none';
  };

  // Kiểm tra mật khẩu
  const checkPassword = () => {
    const password = passwordInput.value.trim();
    const correctPassword = decodePassword(encodedPassword);
    if (!password) {
      errorMessage.textContent = 'Please enter a password!';
      errorMessage.style.display = 'block';
      unlockButton.classList.remove('loading');
      unlockButton.textContent = 'UNLOCK';
    } else if (password.toLowerCase() !== correctPassword.toLowerCase()) {
      errorMessage.textContent = 'Incorrect password!';
      errorMessage.style.display = 'block';
      unlockButton.classList.remove('loading');
      unlockButton.textContent = 'UNLOCK';
    } else {
      errorMessage.style.display = 'none';
      unlockButton.textContent = 'Unlocking...';
      unlockButton.classList.add('loading');
      // Tự động mở khóa sau 1.5 giây
      setTimeout(() => {
        unlockPost();
      }, 1500);
    }
  };

  // Hiển thị overlay nếu chưa mở khóa
  if (!isUnlocked()) {
    overlay.classList.add('active');
    document.documentElement.classList.add('locked');
    document.body.classList.add('locked');
  }

  // Gắn sự kiện
  passwordInput.addEventListener('keypress', (e) => {
    if (e.key === 'Enter') checkPassword();
  });
  unlockButton.addEventListener('click', checkPassword);
  // Tự động kiểm tra khi nhập
  passwordInput.addEventListener('input', () => {
    const password = passwordInput.value.trim();
    const correctPassword = decodePassword(encodedPassword);
    if (password) {
      errorMessage.style.display = 'none'; // Ẩn lỗi khi đang nhập
      if (password.toLowerCase() === correctPassword.toLowerCase()) {
        unlockButton.textContent = 'Unlocking...';
        unlockButton.classList.add('loading');
        setTimeout(() => {
          unlockPost();
        }, 1500);
      } else {
        unlockButton.classList.remove('loading');
        unlockButton.textContent = 'UNLOCK'; // Đặt lại nút nếu nhập sai
      }
    } else {
      errorMessage.style.display = 'none';
      unlockButton.classList.remove('loading');
      unlockButton.textContent = 'UNLOCK'; // Đặt lại nút nếu ô trống
    }
  });
})();
</script>]]></b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
      </b:widget>
    </b:section>
  </main>
</body>
</html>
