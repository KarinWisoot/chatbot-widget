# chatbot-widget

```
    <script src="https://cdn.jsdelivr.net/gh/KarinWisoot/chatbot-widget@main/dist/chatbot-widget.min.js?v=2"></script>
    <script>
      ChatBotWidget.init({
        ip: "127.0.0.1",
        apiBase: "/api/v1",
        model: "itmfec",
        prompt: "ตอนนี้ฉันอยู่หน้า {path} กรุณาช่วยแนะนำการทำงานด้วย", // {path} จะดึงค่า path ปัจจุบันมาใส่
        iconOpen: "https://vcnewprod.mfec.co.th/storage/v1/object/public/assets/mai/openchat.png",
        iconNew: "https://vcnewprod.mfec.co.th/storage/v1/object/public/assets/mai/iconnewchat.png",
        iconNewDark: "https://vcnewprod.mfec.co.th/storage/v1/object/public/assets/mai/openchat.png",
      });
    </script>
```
