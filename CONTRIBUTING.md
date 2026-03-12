1. At the main page: https://github.com/smolurl/smolurl.github.io
2. Click `Add file`, then click `create new file`
3. Create a folder with your desired slug: `yourslug/index.html` <- LEAVE THE index.html NAME - YOUR TRAILING SLASH/SLUG (WHICH IS WHATS AFTER THE / ) GOES HERE WHICH IS WHAT YOU WILL PUT/PASTE IN ANOTHER SITE AND USE.
4. After typing `index.html` at the top, add the following inside it and edit `https://example.com` and anything that says `/yourslug` aswell:
```
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="refresh" content="3; url=https://example.com"> <!-- << YOUR URL THAT YOU WANT TO REDIRECT TO GOES HERE -->
  <title>SmolURL - Provided By CosmosCraft</title>

  <!-- Discord/OpenGraph embed tags -->
  <meta property="og:title" content="SmolURL - Provided By CosmosCraft">
  <meta property="og:description" content="Thank you for using us, please consider donating!">
  <meta property="og:image" content="https://cdn.cosmoscraft.net/index.php/apps/files_sharing/publicpreview/assets?file=/Server_banner_final_3.png&fileId=9922&x=3440&y=1440&a=true&etag=d66c84262908c7d07f23e615589ebf6a">
  <meta property="og:url" content="https://smolurl.org/yourslug"> <!-- << YOUR TRAILING SLASH/SLUG (WHICH IS WHATS AFTER THE / ) GOES HERE -->

  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      background: #5865F2;
      color: white;
    }
    img {
      width: 200px;
      margin-bottom: 20px;
      border-radius: 12px;
    }
  </style>
</head>
<body>
  <img src="https://cdn.cosmoscraft.net/index.php/apps/files_sharing/publicpreview/assets?file=/Server_banner_final_3.png&fileId=9922&x=3440&y=1440&a=true&etag=d66c84262908c7d07f23e615589ebf6a" alt="SmolURL - Provided By CosmosCraft">
  <h1>SmolURL - Provided By CosmosCraft</h1>
  <p>Redirecting you in 3 seconds...</p>
</body>
</html>
```
4. Submit a Pull Request with the title(and edit the `/yourslug` to your slug/redirect name):
```
Add redirect: /yourslug
```

---

EXAMPLES:
1. https://github.com/smolurl/smolurl.github.io/pull/2
2. https://github.com/smolurl/smolurl.github.io/pull/3
