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



<div class="section-box">
  <h2>Invited Speaker</h2>

  <div style="padding: 10px 0 20px 0; text-align: left;">
    <div style="margin-bottom: 5px;">
      <a href="https://www.unsw.edu.au/staff/jinhong-yuan" target="_blank" 
         style="text-decoration: none; color: #000 !important; font-weight: bold; font-size: 0.95rem; font-family: 'Open Sans', sans-serif;">
        Prof. Jinhong Yuan
      </a>
    </div>
    <div style="font-size: 0.95rem; color: #666; font-family: 'Open Sans', sans-serif;">
      University of New South Wales, Australia
    </div>
  </div>

  <div style="padding: 10px 0 20px 0; text-align: left;">
    <div style="margin-bottom: 5px;">
      <a href="https://oic.seu.edu.cn/oicenglish/2026/0522/c68505a568543/page.htm#:~:text=Prof.%20Zeng%20is%20internationally%20recognized%20for%20his%20pioneering,in%20the%20integration%20of%20aerial%20and%20ground%20networks" target="_blank" 
         style="text-decoration: none; color: #000 !important; font-weight: bold; font-size: 0.95rem; font-family: 'Open Sans', sans-serif;">
        Prof. Yong Zeng
      </a>
    </div>
    <div style="font-size: 0.95rem; color: #666; font-family: 'Open Sans', sans-serif; line-height: 1.6;">
      Southeast University and Purple Mountain Laboratory, Nanjing, China
    </div>
  </div>

  <div style="padding: 10px 0 20px 0; text-align: left;">
    <div style="margin-bottom: 5px;">
      <a href="https://gr.xjtu.edu.cn/zqwei/" target="_blank" 
         style="text-decoration: none; color: #000 !important; font-weight: bold; font-size: 0.95rem; font-family: 'Open Sans', sans-serif;">
        Prof. Zhiqiang Wei
      </a>
    </div>
    <div style="font-size: 0.95rem; color: #666; font-family: 'Open Sans', sans-serif; line-height: 1.6;">
      Xi'an Jiaotong University, Xi'an, China
    </div>
  </div>
</div>




<style>
  /* 基础框样式 */
  .section-box {
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 24px;
    margin-bottom: 20px;
    background-color: #ffffff;
    font-family: 'Open Sans', -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    box-shadow: 0 1px 3px rgba(0,0,0,0.04);
  }

  .session-block {
    margin-top: 20px;
    margin-bottom: 10px;
    border-left: 4px solid #0366d6;
    padding-left: 16px;
  }

  .session-time {
    font-weight: 700;
    color: #0366d6;
    font-size: 1.1rem;
    margin-bottom: 16px;
    border-bottom: 2px solid #f1f8ff;
    padding-bottom: 8px;
    display: inline-block;
  }

  /* 左右分栏的列表项 */
  .agenda-item {
    display: flex;
    flex-direction: row;
    gap: 20px;
    padding: 16px 0;
    border-bottom: 1px dashed #eaecef;
  }
  
  .agenda-item:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }

  /* 左侧时间块 */
  .item-time {
    min-width: 95px;
    flex-shrink: 0;
    font-weight: 600;
    color: #586069;
    font-size: 0.95rem;
    padding-top: 2px;
  }

  /* 右侧内容块 */
  .item-content {
    flex-grow: 1;
  }

  /* 统一所有标题的字体和大小 */
  .item-title {
    font-weight: 600;
    color: #24292e;
    font-size: 0.88rem;
    margin-bottom: 6px;
    line-height: 1.5;
  }

  .item-authors {
    color: #586069;
    font-size: 0.88rem;
    line-height: 1.5;
  }

  .author-label {
    font-weight: 600;
    color: #444;
  }

  /* 重置 summary 默认样式，保证字体大小不被覆盖 */
  details summary {
    font-size: inherit;
    font-weight: inherit;
    cursor: pointer;
    outline: none;
    list-style: none; /* 隐藏默认三角符号 */
    transition: color 0.2s ease;
  }
  
  /* 自定义折叠提示的小箭头 */
  details summary::-webkit-details-marker {
    display: none;
  }
  details summary::before {
    content: "▶ ";
    font-size: 0.75rem;
    color: #0366d6;
    margin-right: 4px;
    display: inline-block;
    transition: transform 0.2s ease;
  }
  details[open] summary::before {
    transform: rotate(90deg);
  }

  details summary:hover .item-title {
    color: #0366d6;
  }

  .overview-text {
    margin-top: 12px;
    padding: 16px;
    background-color: #f6f8fa;
    border-left: 3px solid #d1d5da;
    border-radius: 0 4px 4px 0;
    font-size: 0.9rem;
    line-height: 1.6;
    color: #444;
    text-align: justify;
  }
  
  .break-block {
    display: flex;
    align-items: center;
    gap: 15px;
    font-weight: 600;
    color: #d73a49;
    padding: 16px 0;
    margin: 20px 0;
    background-color: #fffbdd;
    border-radius: 6px;
    padding-left: 20px;
  }
  
  /* 手机端适配 */
  @media (max-width: 600px) {
    .agenda-item {
      flex-direction: column;
      gap: 6px;
    }
    .item-time {
      color: #0366d6;
      font-size: 0.9rem;
    }
  }
</style>

<div class="section-box">
  <h2 style="margin-top: 0; margin-bottom: 20px; border-bottom: 1px solid #eaecef; padding-bottom: 10px;">Workshop Program</h2>

  <!-- ================= Session 1 ================= -->
  <div class="session-block">
    <div class="session-time">09:50 – 11:10 | Technical Session 1 (Invited Talks)</div>
    
    <!-- Item 1 -->
    <div class="agenda-item">
      <div class="item-time">09:50 - 10:30</div>
      <div class="item-content">
        <div class="item-title">Keynote 1: (Title to be updated)</div>
        <div class="item-authors"><span class="author-label">Speaker:</span> Prof. Jinhong Yuan</div>
      </div>
    </div>

    <!-- Item 2 -->
    <div class="agenda-item">
      <div class="item-time">10:30 - 11:10</div>
      <div class="item-content">
        <details>
          <summary>
            <span class="item-title">Keynote: Rethinking Waveform for 6G Communications and Sensing: Delay-Doppler Alignment Modulation (DDAM)</span>
            <div class="item-authors" style="margin-top: 4px;">
              <span class="author-label">Speaker:</span> Prof. Yong Zeng
            </div>
          </summary>
          <div class="overview-text">
            <strong>Overview:</strong> Conventional multi-carrier waveforms based on time-frequency domain modulation face problems such as high peak-to-average power ratio (PAPR), serious out-of-band leakage, sensitivity to inter-carrier interference, and high cyclic prefix overhead. For future wireless systems, with the use of larger antenna arrays, higher frequency bands, and more powerful sensing capabilities, new opportunities arise for the design of wireless waveforms for 6G and beyond. To this end, this talk intends to explore the high spatial resolution of large antenna arrays and the multipath sparsity of high-frequency signals, and introduce the novel framework of Delay-Doppler alignment modulation (DDAM) based on joint processing in space-delay-Doppler domains. DDAM leverages path-based beamforming to distinguish multipath signals in the spatial domain, enabling per-path based delay and Doppler compensation and alignment. This will greatly reduce the delay Doppler spread of the channel and thus avoid the complicated channel equalization or large dimensional multi-carrier transmission. The talk will first introduce the background and motivation for proposing DDAM, and then introduce single-carrier and multi-carrier DDAM communications, followed by DDAM integrated sensing and communication (ISAC). Finally, preliminary experimental verification results are introduced.
          </div>
        </details>
      </div>
    </div>
  </div>

  <!-- ================= Tea Break ================= -->
  <div class="break-block">
    <span>☕</span> 11:10 – 11:30 | Tea Break
  </div>

  <!-- ================= Session 2 ================= -->
  <div class="session-block">
    <div class="session-time">11:30 – 12:50 | Technical Session 2 (Oral Presentation)</div>
    
    <div class="agenda-item">
      <div class="item-time">11:30 - 11:50</div>
      <div class="item-content">
        <div class="item-title">Low-PAPR OFDM-Based DFRC Waveform Design with Constant-Modulus Modulation</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Shide Wang (Yan Shan University, China); Xiuping Peng and Tao Zheng (Yanshan University, China)</div>
      </div>
    </div>
    
    <div class="agenda-item">
      <div class="item-time">11:50 - 12:10</div>
      <div class="item-content">
        <div class="item-title">Improved MRC Algorithm with Weighted Update Mechanism for Coded OTFS System</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Hui Chen, Jinhua Sun and Ke Dang (Xidian University, China)</div>
      </div>
    </div>

    <div class="agenda-item">
      <div class="item-time">12:10 - 12:30</div>
      <div class="item-content">
        <div class="item-title">A Universal Random Precoding Framework for MIMO Systems</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Jiazhen Dong and Lei Liu (Zhejiang University, China); Xiaojun Yuan (University of Electronic Science and Technology of China, China); Baoming Bai (Xidian University, China)</div>
      </div>
    </div>

    <div class="agenda-item">
      <div class="item-time">12:30 - 12:50</div>
      <div class="item-content">
        <div class="item-title">Non-Coherent Transmission Meets OFDM in Presence of CFO: TDS or FDS?</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Yiding Wang, Sirui Miao and Neng Ye (Beijing Institute of Technology, China)</div>
      </div>
    </div>
  </div>

  <!-- ================= Lunch Break ================= -->
  <div class="break-block" style="color: #28a745; background-color: #f0fdf4;">
    <span>🍽️</span> 12:50 – 14:00 | Lunch Break
  </div>

  <!-- ================= Session 3 ================= -->
  <div class="session-block">
    <div class="session-time">14:00 – 14:40 | Technical Session 3 (Invited Talks)</div>
    
    <div class="agenda-item">
      <div class="item-time">14:00 - 14:40</div>
      <div class="item-content">
        <details>
          <summary>
            <span class="item-title">Keynote: On Modulation Waveforms for 6G High-Mobility Communications: OFDM, OTFS, or DD-a-OFDM?</span>
            <div class="item-authors" style="margin-top: 4px;">
              <span class="author-label">Speaker:</span> Prof. Zhiqiang Wei
            </div>
          </summary>
          <div class="overview-text">
            <strong>Overview:</strong> This course focuses on modulation waveform design for 6G high-mobility communications, and systematically introduces the fundamental concepts and signal processing methods of representative waveform schemes, including orthogonal frequency-division multiplexing (OFDM), orthogonal time frequency space (OTFS) modulation, and delay-Doppler domain-aided OFDM (DD-a-OFDM). The course begins by reviewing the basic concepts, core design criteria, and candidate waveform classifications for 6G high-mobility communications. It then proceeds from the challenges faced by OFDM in high-mobility scenarios to introduce the fundamental theory and signal processing methods of delay-Doppler (DD) domain communications, including DD-domain channel estimation and DD-domain multi-antenna transceiver signal processing. To further promote the compatibility and integration of DD-domain modulation waveforms with existing OFDM-based systems, the course presents DD-a-OFDM technology, analyzing how it introduces DD-domain signal processing to assist OFDM transmission while remaining compatible with the 5G NR OFDM framework, thereby striking a balance among Doppler resilience, system compatibility, and implementation complexity. This course is expected to provide waveform design references for the technological development of future applications such as low altitude communications, satellite communications, and integrated sensing and communications.
          </div>
        </details>
      </div>
    </div>
  </div>

  <!-- ================= Session 4 ================= -->
  <div class="session-block">
    <div class="session-time">14:40 – 16:00 | Technical Session 4 (Oral Presentation)</div>
    
    <div class="agenda-item">
      <div class="item-time">14:40 - 15:00</div>
      <div class="item-content">
        <div class="item-title">Joint Iterative Detection and Decoding for LDPC-Coded Faster-than-Nyquist Systems</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Hong Wang, Tongzhou Yu, Jian Fang and Baoming Bai (Xidian University, China); Dan Feng (Xi'an University of Posts and Telecommunications, China)</div>
      </div>
    </div>
    
    <div class="agenda-item">
      <div class="item-time">15:00 - 15:20</div>
      <div class="item-content">
        <div class="item-title">Storage-Efficient and High-Reliability Interleaved Transform for Enhanced Random Multiplexing</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Ming Wang (Communication University of China, China); Lei Liu (Zhejiang University, China); Shufeng Li (Communication University of China, China); Yuhao Chi (Xidian University, China)</div>
      </div>
    </div>

    <div class="agenda-item">
      <div class="item-time">15:20 - 15:40</div>
      <div class="item-content">
        <div class="item-title">Neural Network-Based Hybrid Digital-Analog Beamformer Design for Wideband Massive MIMO Systems with Large-Scale Users</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Haojie Cheng (Southeast University, China); Beiyuan Liu (Northwestern Polytechnical University, China); Liquan Chen (Southeast University, China); Julian Cheng (University of British Columbia, Canada & Great Bay University, China)</div>
      </div>
    </div>

    <div class="agenda-item">
      <div class="item-time">15:40 - 16:00</div>
      <div class="item-content">
        <div class="item-title">Unified Analytical Model for Atomic Receivers Under Typical Quantum Interference Paths</div>
        <div class="item-authors"><span class="author-label">Authors:</span> Yiyue Xiang and Neng Ye (Beijing Institute of Technology), Qihao Peng and Pei Xiao (University of Surrey, United Kingdom), Jianping An (Beijing Institute of Technology, China)</div>
      </div>
    </div>
  </div>

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
