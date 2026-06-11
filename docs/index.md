---

permalink: /
title: "Next-Generation Waveforms Design for Communications, Sensing, and Integrated Systems: Information-Theoretic & Application Perspectives"
excerpt: "Workshop at IEEE ISIT 2026 (Guangzhou)<br><span class='workshop-date'>July 03 (Friday), 2026</span>"
author_profile: false
header:
  overlay_image: "/assets/images/guangzhou.jpg"
  overlay_filter: 0.3

---






<style>
  /* 1. 引入 Google Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700;800&display=swap');

  /* 2. 全局设置 */
  body, h1, h4, h5, h6, p, li, td, th, div, a, span {
    font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif !important;
  }
  body, p, li, td, th, div { 
    font-size: 18px !important;
    line-height: 1.6 !important;
  }

  /* 3. 正文标题样式 (左对齐) */
  h2 { 
    font-size: 26px !important; 
    color: #0056b3 !important;
    margin-top: 0 !important;
    margin-bottom: 15px !important;
    text-align: left !important; 
    border-bottom: 1px solid #e1e4e8; 
    padding-bottom: 10px;
  }
  h3 { 
    font-size: 20px !important; 
    color: #0056b3 !important;
    text-align: left !important;
    margin-bottom: 5px !important;
  }

  /* 4. 页面容器设置 */
  #main, .page, .page__content, .archive {
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  .sidebar { display: none !important; width: 0 !important; }
  .page__inner-wrap {
    width: 98% !important;      
    max-width: 100% !important; 
    margin: 0 auto !important;
    padding: 0 !important;
    float: none !important;     
  }

  /* 5. 卡片盒子样式 */
  .section-box {
    background-color: #f8fbff;
    border: 1px solid #e1e4e8;
    border-left: 6px solid #0056b3;
    border-radius: 8px;
    padding: 40px 12% !important; 
    margin-bottom: 40px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    
    width: 70% !important;        
    min-width: 800px !important; 
    margin-left: auto !important;  
    margin-right: auto !important; 
    
    text-align: left !important; 
    box-sizing: border-box !important; 
  }

  /* 6. 表格样式 */
  .program-table, .dates-table {
    min-width: 500px;
    border-collapse: collapse;
    font-size: 18px !important;
    width: 100%; 
  }
  .program-table td, .dates-table td {
    padding: 12px 15px;
    border-bottom: 1px dashed #ddd;
    vertical-align: top;
    text-align: left; 
  }
  .program-table tr:last-child td, .dates-table tr:last-child td { border-bottom: none; }
  
  .time-col { width: 160px; font-weight: bold; color: #555; }
  .label-col { width: 280px !important; white-space: nowrap !important; font-weight: bold; color: #333; }
  .date-col { color: #d90000; font-weight: bold; }

  /* 7. Organizers 样式 (照片长方形) */
/* 7. Organizers 样式 (照片长方形) */
  .organizer-grid { 
    display: flex; 
    justify-content: space-around; 
    flex-wrap: wrap; 
    text-align: center !important; 
  }
  .organizer-item { width: 30%; margin-bottom: 20px; }
  
  /* 照片改为长方形 */
  .organizer-item img { 
    border-radius: 6px !important; 
    width: 150px !important; 
    height: 200px !important; 
    object-fit: cover !important; 
    border: 3px solid #f0f0f0; 
    background-color: #ddd; /* 占位色 */
  }
  
  /* 【关键修改】Organizers 人名黑色加粗 */
  .organizer-item h3 { 
      text-align: center !important; 
      margin-bottom: 5px !important;
      color: #000 !important; /* 黑色 */
      font-weight: bold !important; /* 加粗 */
  }
  
  .organizer-item p { 
    text-align: center !important; 
    font-size: 0.85em !important; 
    line-height: 1.4 !important;    
    color: #444;
  }
  
  .btn--info { margin-top: 10px; display: inline-block; background-color: #0056b3 !important; border-color: #0056b3 !important; }

  /* 8. 封面标题样式 */
  .page__hero--overlay .page__title,
  .page__hero--overlay .page__lead {
    font-family: 'Open Sans', sans-serif !important;
    font-weight: 800 !important; 
    font-style: normal !important;
    color: #fff !important;
    text-shadow: 1px 1px 10px rgba(0,0,0,0.8) !important;
    font-size: 1.7em !important; 
    line-height: 1.3 !important;
    width: 100% !important; 
    max-width: 100% !important; 
    padding: 0 20px !important;
    text-align: center !important;
    margin-bottom: 10px !important;
  }
  .page__hero--overlay .page__lead {
    margin-top: 5px !important; 
  }

  /* 9. 【关键修改】日期样式 */
  .workshop-date {
    font-family: 'Microsoft YaHei', 'SimHei', sans-serif !important;
    font-size: 0.65em !important; 
    font-style: normal !important;
    font-weight: bold !important; 
    letter-spacing: 0.5px !important;
    color: rgba(255,255,255,0.95);
    display: inline-block;
    margin-top: 8px;
    text-transform: uppercase;
  }
  
  /* 10. 折叠面板样式 (暂时保留，以备后续增加Program使用) */
  details {
    width: 100%;
    margin-bottom: 15px;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    background-color: #fff;
    overflow: hidden;
  }
  summary {
    padding: 12px 20px;
    cursor: pointer;
    font-weight: bold;
    font-size: 18px; 
    color: #0056b3;
    background-color: #f8fbff;
    list-style: none;
    outline: none;
    transition: background 0.2s;
    text-align: left; 
  }
  summary:hover { background-color: #eaf5ff; }
  summary::-webkit-details-marker { display: none; }
  summary::after { content: '+'; float: right; font-weight: bold; color: #0056b3; }
  details[open] summary::after { content: '-'; }
  details[open] summary { border-bottom: 1px solid #e1e4e8; }
  details .program-table { margin: 0; width: 100%; }
  details td { padding: 15px 20px; }

  /* === 手机端适配 === */
  @media screen and (max-width: 768px) {
    .section-box {
      width: 92% !important;      
      min-width: 0 !important;    
      margin: 0 auto 30px auto !important; 
      padding: 20px 15px !important; 
    }
    .section-box table, .program-table, .dates-table {
      display: block !important;    
      width: 100% !important;        
      min-width: 0 !important;       
      overflow-x: auto !important;  
      -webkit-overflow-scrolling: touch; 
    }
    
    .page__hero--overlay {
      width: 100vw !important; 
      max-width: 100vw !important;
      background-size: cover !important; 
      background-position: center center !important;
      background-repeat: no-repeat !important;
      background-attachment: scroll !important; 
      min-height: 40vh !important; 
      margin: 0 !important;
      left: 0 !important;
      right: 0 !important;
      padding-left: 15px !important;
      padding-right: 15px !important;
    }
  }

  /* 隐藏多余元素 */
  .greedy-nav .theme-toggle, .greedy-nav button, #theme-toggle, button[title="Toggle theme"] { display: none !important; }
  .page__footer-follow, .social-icons { display: none !important; }
  .page__footer-copyright { display: block !important; margin: 0 auto !important; text-align: center !important; }
  
  /* 强制白天模式 */
  @media (prefers-color-scheme: dark) {
    body, .page, .page__content { background-color: #fff !important; color: #333 !important; }
    h1, h2, h3, h4, h5, h6 { color: #0056b3 !important; }
    a { color: #0056b3 !important; }
    .section-box { background-color: #f8fbff !important; color: #333 !important; border: 1px solid #e1e4e8 !important; }
  }
</style>

<div id="home"></div>

<div class="section-box">
  <h2>Workshop Overview</h2>
  <div style="text-align: justify;">
    <p>With the rapid expansion of high-mobility applications, ensuring reliable communication in rapidly time-varying environments has become a critical challenge. Conventional Orthogonal Frequency Division Multiplexing (OFDM) suffers pronounced degradation in such dynamic scenarios, underscoring the urgent necessity for next-generation modulation waveforms. Consequently, emerging multicarrier schemes—including orthogonal time frequency space (OTFS), orthogonal delay division multiplexing (ODDM), orthogonal chirp division multiplexing (OCDM), affine frequency division multiplexing (AFDM), interleave frequency division multiplexing (IFDM), and random multiplexing (RM)—have provided new perspectives for robust system design.</p>
    <p>This workshop highlights fundamental challenges in waveform design that arise at the intersection of information theory and wireless communication. By bridging theoretical limits with practical system considerations, it aims to motivate participants to address core problems in next-generation waveform research, and foster innovation across theory and practice.</p>
  </div>
  
  <h3>Topics of Interest</h3>
  <p>We seek original completed and unpublished work. Topics of interest include, but are not limited to:</p>
  <ul>
    <li>Novel Waveform Design for Communications and Sensing</li>
    <li>Information-Theoretic Foundations of Novel Waveform Design</li>
    <li>Channel Coding and Decoding Design</li>
    <li>Channel Estimation and Equalization</li>
    <li>Signal Detection and Receiver Design for Novel Modulation Schemes</li>
    <li>Integrated Sensing and Communications (ISAC) with Advanced Waveforms</li>
    <li>Multiple Access and Resource Allocation Mechanisms for 6G Waveforms</li>
    <li>Low-Latency and Ultra-Reliable Transmission under High Mobility</li>
    <li>Joint Waveform and Coding Co-Design</li>
    <li>Signal Processing for Waveform-Based Transceiver Designs</li>
    <li>MIMO and Massive MIMO-Aided Systems</li>
    <li>Hardware Implementation and Prototype Validation of Novel Waveform Systems</li>
  </ul>
</div>

<div id="submission"></div>
<div class="section-box">
  <h2>Paper Submission and Dates</h2>
  
  <div style="text-align: justify; margin-bottom: 30px;">
    <p>
      Submission will be handled via <a href="https://edas.info/newPaper.php?c=34669&amp;track=135792" target="_blank" rel="noopener noreferrer">EDAS</a>. The paper format follows the main ISIT conference guidelines.
    </p>
    
    </div>
  
  <h3>Important Dates</h3>
  
  <table class="dates-table">
    <tr>
      <td class="label-col">Paper Submission Deadline:</td>
      <td class="date-col">07 April, 2026 (firm)</td>
    </tr>
    <tr>
      <td class="label-col">Acceptance Notification:</td>
      <td class="date-col">21 April, 2026</td>
    </tr>
    <tr>
      <td class="label-col">Final Manuscript Submission:</td>
      <td class="date-col">28 April, 2026</td>
    </tr>
  </table>
</div>




<div class="section-box" style="font-family: 'Open Sans', sans-serif;">
  <h2 style="margin-bottom: 30px;">Invited Speakers</h2>

  <!-- Speaker 1: Prof. Jinhong Yuan -->
  <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 40px; padding-bottom: 20px; border-bottom: 1px solid #eee;">
    <!-- 照片 -->
    <div style="flex-shrink: 0; width: 150px;">
      <img src="{{ '/assets/images/yuan.png' | relative_url }}" alt="Prof. Jinhong Yuan" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); object-fit: cover;">
    </div>
    
    <!-- 信息 -->
    <div style="flex: 1; min-width: 280px; text-align: justify;">
      <div style="color: #000; font-weight: bold; font-size: 1.2rem; margin-bottom: 5px;">
        Prof. Jinhong Yuan
      </div>
      <div style="font-size: 0.95rem; color: #666; font-style: italic; margin-bottom: 15px;">
        University of New South Wales, Australia
      </div>
      <div style="font-size: 0.95rem; color: #333; line-height: 1.6;">
        Professor Jinhong Yuan is a Professor of Telecommunications with the School of Electrical Engineering and Telecommunications. He received the B.E. and Ph.D degrees in Electronics Engineering in 1991 and 1997, respectively. From 1997 to 1999 he was a Research Fellow at the School of Electrical Engineering, the University of Sydney, Sydney, Australia. In 2000 he joined the School of Electrical Engineering and Telecommunications, the University of New South Wales, Sydney, Australia, where he is currently a Professor and Head of Telecommunications of the school. He has published two books, two book chapters, over 300 papers in telecommunications journals and conference proceedings and 40 industrial reports. He is a co-inventor of one patent on MIMO systems and two patents on low-density-parity-check (LDPC) codes. He co-authored four Best Paper Awards and one Best Poster Award, including a Best Paper Award of IEEE Wireless Communications and Networking Conference (WCNC), Cancun, Mexico in 2011, and a Best Paper Award of IEEE International Symposium on Wireless Communications Systems (ISWCS), Trondheim, Norway in 2007. He serves as the IEEE NSW Chair of joint Communications/Signal Processions/Ocean Engineering Chapter and an Associate Editor for IEEE Transactions on Communications and an Associate Editor for IEEE Transactions on Wireless Communications.
      </div>
    </div>
  </div>

  <!-- Speaker 2: Prof. Yong Zeng -->
  <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 40px; padding-bottom: 20px; border-bottom: 1px solid #eee;">
    <!-- 照片 -->
    <div style="flex-shrink: 0; width: 150px;">
      <img src="{{ '/assets/images/zeng.png' | relative_url }}" alt="Prof. Yong Zeng" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); object-fit: cover;">
    </div>
    
    <!-- 信息 -->
    <div style="flex: 1; min-width: 280px; text-align: justify;">
      <div style="color: #000; font-weight: bold; font-size: 1.2rem; margin-bottom: 5px;">
        Prof. Yong Zeng
      </div>
      <div style="font-size: 0.95rem; color: #666; font-style: italic; margin-bottom: 15px;">
        Southeast University and Purple Mountain Laboratory, Nanjing, China
      </div>
      <div style="font-size: 0.95rem; color: #333; line-height: 1.6;">
        <p style="margin-top: 0;">Yong Zeng, IEEE Fellow, Young Chief Professor of Southeast University and Purple Mountain Laboratory, Nanjing, China. He received the Bachelor of Engineering (First-Class Honours) and Ph.D. degrees from Nanyang Technological University (NTU), Singapore. From 2013 to 2018, he was a Research Fellow and Senior Research Fellow at the National University of Singapore (NUS). From 2018 to 2019, he was a Lecturer at the University of Sydney, Australia.</p>
        <p style="margin-bottom: 0;">Prof. Zeng was listed as Clarivate Analytics Highly Cited Researcher for 7 consecutive years (2019-2025), AI2000 Most Influential Scholars in the field of Internet of Things for 4 consecutive years (2021-2024), Stanford "Top 2% of Scientists in the World - Lifetime Influence". Prof. Zeng is the recipient of Australia Research Council (ARC) Discovery Early Career Researcher Award (DECRA), IEEE Communications Society Asia-Pacific Outstanding Young Researcher Award, and won 10 international and domestic best paper awards including IEEE Marconi Award (2020 and 2024), Heinrich Hertz Award (2017 and 2020), etc. Prof. Zeng proposed the concept of channel knowledge map (CKM) and Delay-Doppler Alignment Modulation (DDAM) transmission method. His works have been cited by more than 38,000 times. He serves/served on the editorial board of SCI journals such as IEEE Transactions on Communications, IEEE Transactions on Mobile Computing, and IEEE Communications Letters, and leading guest editor of journals including IEEE ComMag, Wireless ComMag, China Communications, and Science China Information Sciences. Prof. Zeng was elevated to IEEE Fellow “for contributions to unmanned aerial vehicle communications and wireless power transfer”.</p>
      </div>
    </div>
  </div>

  <!-- Speaker 3: Prof. Zhiqiang Wei -->
  <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 20px;">
    <!-- 照片 -->
    <div style="flex-shrink: 0; width: 150px;">
      <img src="{{ '/assets/images/wei.png' | relative_url }}" alt="Prof. Zhiqiang Wei" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); object-fit: cover;">
    </div>
    
    <!-- 信息 -->
    <div style="flex: 1; min-width: 280px; text-align: justify;">
      <div style="color: #000; font-weight: bold; font-size: 1.2rem; margin-bottom: 5px;">
        Prof. Zhiqiang Wei
      </div>
      <div style="font-size: 0.95rem; color: #666; font-style: italic; margin-bottom: 15px;">
        Xi'an Jiaotong University, Xi'an, China
      </div>
      <div style="font-size: 0.95rem; color: #333; line-height: 1.6;">
        Zhiqiang Wei received the B.E. degree in information engineering from Northwestern Polytechnical University (NPU), Xi'an, China, in 2012, and the Ph.D. degree in electrical engineering and telecommunications from the University of New South Wales (UNSW), Sydney, Australia, in 2019. From 2019 to 2020, he was a Postdoctoral Research Fellow with UNSW. From 2021 to 2022, he was a Humboldt Postdoctoral Research Fellow with the Institute for Digital Communications, Friedrich-Alexander University Erlangen-Nuremberg (FAU), Erlangen, Germany. He is currently a Professor with the School of Mathematics and Statistics, Xi'an Jiaotong University, Xi'an, China. His research interests include delay-Doppler communications, resource allocation optimization, and statistical and array signal processing. He received the Best Paper Award at the IEEE ICC 2018 and IEEE WCNC 2023. He was the organizer/chair for several workshops and tutorials on related topics of orthogonal time frequency space (OTFS) in IEEE flagship conferences, including IEEE ICC, IEEE WCNC, IEEE VTC, and IEEE ICCC. He has been listed in the World’s Top 2% Scientists by Stanford University and Highly Cited Chinese Researcher since 2021. He is currently an editor for the IEEE Transactions on Communications, IEEE Transactions on Wireless Communications, IEEE Open Journal of the Communications Society, and Electronics.
      </div>
    </div>
  </div>

</div>






<div class="section-box">
  <h2>Workshop Program (July 03, 2026)</h2>

  <!-- Session 1 -->
  <details open>
    <summary>09:50 – 11:10 | Technical Session 1 (Invited Talks)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">09:50 – 10:30</td>
        <td>
          <strong>Keynote 1</strong><br>
          <span style="color:#555; font-size:0.95em;">Invited Speaker: Prof. Jinhong Yuan</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">10:30 – 11:10</td>
        <td>
          <strong>Keynote 2</strong><br>
          <span style="color:#555; font-size:0.95em;">Invited Speaker: Prof. Zilong Liu</span>
        </td>
      </tr>
    </table>
  </details>

  <!-- Tea Break -->
  <div style="background-color: #eaf5ff; padding: 12px 20px; border-radius: 6px; margin-bottom: 15px; color: #0056b3; font-weight: bold; border-left: 4px solid #0056b3;">
    11:10 – 11:30 | Tea Break
  </div>

  <!-- Session 2 -->
  <details open>
    <summary>11:30 – 12:50 | Technical Session 2 (Oral Presentation)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">11:30 – 11:50</td>
        <td>
          <strong>Low-PAPR OFDM-Based DFRC Waveform Design with Constant-Modulus Modulation</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Shide Wang; Xiuping Peng and Tao Zheng (Yanshan University, China)</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">11:50 – 12:10</td>
        <td>
          <strong>Improved MRC Algorithm with Weighted Update Mechanism for Coded OTFS System</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Hui Chen, Jinhua Sun and Ke Dang (Xidian University, China)</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">12:10 – 12:30</td>
        <td>
          <strong>A Universal Random Precoding Framework for MIMO Systems</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Jiazhen Dong and Lei Liu (Zhejiang University, China); Xiaojun Yuan (UESTC, China); Baoming Bai (Xidian University, China)</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">12:30 – 12:50</td>
        <td>
          <strong>Non-Coherent Transmission Meets OFDM in Presence of CFO: TDS or FDS?</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Yiding Wang, Sirui Miao and Neng Ye (Beijing Institute of Technology, China)</span>
        </td>
      </tr>
    </table>
  </details>

  <!-- Lunch Break -->
  <div style="background-color: #eaf5ff; padding: 12px 20px; border-radius: 6px; margin-bottom: 15px; color: #0056b3; font-weight: bold; border-left: 4px solid #0056b3;">
    12:50 – 14:00 | Lunch Break
  </div>

  <!-- Session 3 -->
  <details open>
    <summary>14:00 – 15:20 | Technical Session 3 (Invited Talks)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">14:00 – 14:40</td>
        <td>
          <strong>Keynote 3</strong><br>
          <span style="color:#555; font-size:0.95em;">Invited Speaker: Prof. Yong Zeng</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">14:40 – 15:20</td>
        <td>
          <strong>Keynote 4</strong><br>
          <span style="color:#555; font-size:0.95em;">Invited Speaker: Prof. Zhiqiang Wei</span>
        </td>
      </tr>
    </table>
  </details>

  <!-- Tea Break 2 -->
  <div style="background-color: #eaf5ff; padding: 12px 20px; border-radius: 6px; margin-bottom: 15px; color: #0056b3; font-weight: bold; border-left: 4px solid #0056b3;">
    15:20 – 15:40 | Tea Break
  </div>

  <!-- Session 4 -->
  <details open>
    <summary>15:40 – 17:00 | Technical Session 4 (Oral Presentation)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">15:40 – 16:00</td>
        <td>
          <strong>Joint Iterative Detection and Decoding for LDPC-Coded Faster-than-Nyquist Systems</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Hong Wang, Tongzhou Yu, Jian Fang and Baoming Bai (Xidian University, China); Dan Feng (Xi'an University of Posts and Telecommunications, China)</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">16:00 – 16:20</td>
        <td>
          <strong>Storage-Efficient and High-Reliability Interleaved Transform for Enhanced Random Multiplexing</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Ming Wang (Communication University of China, China); Lei Liu (Zhejiang University, China); Shufeng Li (Communication University of China, China); Yuhao Chi (Xidian University, China)</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">16:20 – 16:40</td>
        <td>
          <strong>Neural Network-Based Hybrid Digital-Analog Beamformer Design for Wideband Massive MIMO Systems with Large-Scale Users</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Haojie Cheng and Liquan Chen (Southeast University, China); Beiyuan Liu (Northwestern Polytechnical University, China); Julian Cheng (UBC, Canada & Great Bay University, China)</span>
        </td>
      </tr>
      <tr>
        <td class="time-col">16:40 – 17:00</td>
        <td>
          <strong>Unified Analytical Model for Atomic Receivers Under Typical Quantum Interference Paths</strong><br>
          <span style="color:#555; font-size:0.9em;">Authors: Yiyue Xiang, Neng Ye and Jianping An (Beijing Institute of Technology, China); Qihao Peng and Pei Xiao (University of Surrey, UK)</span>
        </td>
      </tr>
    </table>
  </details>
</div>



<style>

/* === 新增：头像和名字链接样式 === */
  
  /* 名字链接：默认继承黑色，去掉下划线 */
  .name-link {
    color: #333 !important; 
    text-decoration: none;
    transition: color 0.2s;
  }
  
  /* 名字链接：鼠标悬停变成主题蓝 */
  .name-link:hover {
    color: #0056b3 !important;
    text-decoration: underline;
  }

  /* 图片链接：去掉默认边框等干扰 */
  .img-link {
    display: block;
    width: 100%;
    text-decoration: none;
    cursor: pointer;
  }
  
/* === 1. 整体容器布局 === */
  .org-grid {
    display: flex;
    justify-content: center; 
    flex-wrap: wrap;
    gap: 50px; /* 【改动1】间距变大：由 20px 增加到 50px */
    margin-top: 20px;
    align-items: stretch;
  }

  /* === 2. 单个卡片样式 === */
  .org-card {
    /* 【改动2】宽度调整： */
    width: 22%;          /* 稍微减小百分比 */
    min-width: 200px;    /* 手机端最小宽度 */
    max-width: 240px;    /* 【关键】限制最大宽度，这样在大屏幕上也不会变得很大 */

    background-color: #ffffff; 
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    
    /* 【改动3】内边距减小：让卡片看起来更紧凑 */
    padding: 15px 15px;  
    
    display: flex;
    flex-direction: column; 
    align-items: center;    
    
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    box-sizing: border-box;
  }
  
  .org-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  }

  /* === 3. 照片样式 === */
  .org-portrait {
    width: 100%;
    aspect-ratio: 3 / 4; 
    object-fit: cover; 
    object-position: top center; 
    border-radius: 4px;
    margin-bottom: 12px; /* 图片下方的间距稍微减小 */
  }

  /* === 4. 文字信息样式 === */
  .org-name {
    /* 【改动4】字号微调：配合小卡片，字号稍微改小一点点 */
    font-size: 1.05rem; 
    font-weight: bold;
    color: #333;
    margin-bottom: 6px;
    min-height: 1.4em; 
  }

  .org-info {
    font-size: 0.7rem;
    color: #666;
    line-height: 1.4;
    text-align: center;
    /* 高度稍微减小，因为卡片变窄了，换行可能会多，保持弹性 */
    min-height: 60px; 
    
    display: flex;
    align-items: flex-start; 
    justify-content: center;
  }

.org-email {
    /* 【改动1】字体调小：建议直接用 px 精确控制，12px 或 11px 通常比较合适 */
    font-size: 15px !important; 
    
    /* 【改动2】强制不换行：这是核心，保证邮箱只在一行显示 */
    white-space: nowrap !important;
    
    /* 【改动3】去掉之前的强制打断属性，改回 normal */
    word-break: normal !important;
    
    margin-top: 8px; /* 稍微调整一下间距 */
    margin-bottom: 5px;
    
    /* 增加宽度容错，防止溢出 */
    width: 100%;
    text-align: center !important;
    overflow: hidden; 
    text-overflow: ellipsis; /* 如果实在太长放不下，会显示省略号...（通常邮箱够短不会触发） */
  }
  
  .org-email a {
    text-decoration: none;
    color: #0077cc;
    font-weight: 600;
    
    /* 确保链接也是内联块级元素，接受对齐 */
    display: inline-block; 
  }
  
  .org-email a:hover {
    text-decoration: underline;
  }

  /* 标题样式 */
  .section-title {
    text-align: left;
    margin-left: 0;
    padding-left: 0;
    margin-bottom: 20px;
    color: #0056b3; 
  }
</style>

<div class="section-box">
  <h2 id="organizers" class="section-title">Workshop Organizers</h2>

  <div class="org-grid">
    <div class="org-card">
      <a href="https://person.zju.edu.cn/leiliu_cn" target="_blank" class="img-link">
        <img src="{{ '/assets/images/Liu.jpg' | relative_url }}" class="org-portrait" alt="Lei Liu">
      </a>
      
      <div class="org-name">
        <a href="https://person.zju.edu.cn/leiliu_cn" target="_blank" class="name-link">Lei Liu</a>
      </div>
      
      <div class="org-info">Zhejiang University,<br>China</div>
      <div class="org-email">
        <a href="mailto:lei_liu@zju.edu.cn">lei_liu@zju.edu.cn</a>
      </div>
    </div>

    <div class="org-card">
      <a href="https://web.xidian.edu.cn/yhchi/" target="_blank" class="img-link">
        <img src="{{ '/assets/images/Chi.jpg' | relative_url }}" class="org-portrait" alt="Yuhao Chi">
      </a>
      
      <div class="org-name">
        <a href="https://web.xidian.edu.cn/yhchi/" target="_blank" class="name-link">Yuhao Chi</a>
      </div>
      
      <div class="org-info">Xidian University,<br>China</div>
      <div class="org-email">
        <a href="mailto:yhchi@xidian.edu.cn">yhchi@xidian.edu.cn</a>
      </div>
    </div>

    <div class="org-card">
      <a href="https://www.researchgate.net/profile/Yao-Ge-3" target="_blank" class="img-link">
        <img src="{{ '/assets/images/Ge.jpg' | relative_url }}" class="org-portrait" alt="Yao Ge">
      </a>
      
      <div class="org-name">
        <a href="https://www.researchgate.net/profile/Yao-Ge-3" target="_blank" class="name-link">Yao Ge</a>
      </div>
      
      <div class="org-info">NTU,<br>Singapore</div>
      <div class="org-email">
        <a href="mailto:yao.ge@ntu.edu.sg">yao.ge@ntu.edu.sg</a>
      </div>
    </div>
  </div>
</div>
