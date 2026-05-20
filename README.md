# LFA
<!DOCTYPE html>
<html lang="ht">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LFAscore - Lig Foutbòl Ayiti</title>
    <link rel="manifest" href="manifest.json">
    <style>
        body { font-family: sans-serif; background: #f2f4f7; color: #2c3e50; text-align: center; padding: 20px; }
        .header { background: #002060; color: white; padding: 15px; font-size: 1.5rem; font-weight: bold; border-radius: 8px; }
        .card { background: white; margin-top: 20px; padding: 20px; border-radius: 8px; border: 1px solid #e1e6eb; }
    </style>
</head>
<body>
    <div class="header">🇭🇹 LFAscore Pro</div>
    <div class="card">
        <h2>Violette AC 0 - 0 Arcahaie FC</h2>
        <p style="color: red; font-weight: bold;">Match la ap kòmanse talè...</p>
    </div>
<script>
  if ('serviceWorker' in navigator) { navigator.serviceWorker.register('sw.js'); }
</script>
</body>
</html>
{
  "name": "Lig Foutbòl Ayiti - LFA",
  "short_name": "LFAscore",
  "start_url": "index.html",
  "display": "standalone",
  "background_color": "#002060",
  "theme_color": "#002060",
  "orientation": "portrait"
}
self.addEventListener('fetch', e => {});
