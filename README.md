## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Sprout - Welcome</title>
<style>
  body {
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #f4f4f2;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  }
</style>
</head>
<body>

<div style="width:300px; height:560px; background:#fff; border-radius:36px; border:1px solid #ddd; padding:14px; box-sizing:border-box; position:relative; overflow:hidden;">

  <div style="width:100%; height:100%; background:#faf9f6; border-radius:24px; position:relative; overflow:hidden; display:flex; flex-direction:column; align-items:center; justify-content:space-between; padding:36px 26px; box-sizing:border-box;">

    <!-- soft background blobs -->
    <div style="position:absolute; top:-30px; left:-30px; width:120px; height:120px; border-radius:50%; background:#EAF3DE;"></div>
    <div style="position:absolute; top:20px; right:-40px; width:100px; height:100px; border-radius:50%; background:#FBEAF0;"></div>

    <!-- top spacer -->
    <div></div>

    <!-- mascot illustration -->
    <div style="position:relative; z-index:1; display:flex; flex-direction:column; align-items:center;">
      <svg width="170" height="170" viewBox="0 0 170 170">
        <!-- pot -->
        <path d="M50 130 L120 130 L110 165 L60 165 Z" fill="#F0997B" />
        <rect x="44" y="118" width="82" height="16" rx="5" fill="#F5C4B3" />
        <!-- stem -->
        <line x1="85" y1="118" x2="85" y2="70" stroke="#97C459" stroke-width="5" stroke-linecap="round"/>
        <!-- leaves -->
        <ellipse cx="65" cy="80" rx="20" ry="11" fill="#97C459" transform="rotate(-20 65 80)"/>
        <ellipse cx="105" cy="88" rx="20" ry="11" fill="#97C459" transform="rotate(20 105 88)"/>
        <!-- face on flower -->
        <circle cx="85" cy="58" r="22" fill="#ED93B1"/>
        <circle cx="77" cy="55" r="2.5" fill="#4B1528"/>
        <circle cx="93" cy="55" r="2.5" fill="#4B1528"/>
        <path d="M77 64 Q85 70 93 64" stroke="#4B1528" stroke-width="2" fill="none" stroke-linecap="round"/>
        <!-- petals accent -->
        <circle cx="60" cy="45" r="9" fill="#F4C0D1"/>
        <circle cx="110" cy="45" r="9" fill="#F4C0D1"/>
        <circle cx="85" cy="30" r="9" fill="#F4C0D1"/>
      </svg>
    </div>

    <!-- text + cta -->
    <div style="position:relative; z-index:1; width:100%; text-align:center;">
      <p style="font-size:20px; font-weight:600; margin:0 0 8px; color:#222;">Welcome to Sprout</p>
      <p style="font-size:13px; color:#666; margin:0 0 20px; line-height:1.6;">Your little plant buddy that helps you water, track, and grow happier houseplants.</p>

      <div style="display:flex; gap:6px; justify-content:center; margin-bottom:20px;">
        <span style="width:6px; height:6px; border-radius:50%; background:#639922;"></span>
        <span style="width:6px; height:6px; border-radius:50%; background:#ddd;"></span>
        <span style="width:6px; height:6px; border-radius:50%; background:#ddd;"></span>
      </div>

      <button style="width:100%; background:#639922; color:#fff; border:none; font-weight:600; font-size:14px; padding:12px; border-radius:10px; margin-bottom:10px; cursor:pointer;">
        Get started
      </button>
      <button style="width:100%; background:transparent; color:#666; border:none; font-weight:400; font-size:13px; padding:6px; cursor:pointer;">
        I already have an account
      </button>
    </div>

  </div>
</div>

</body>
</html>
