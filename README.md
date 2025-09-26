# chatbot-widget

```
    <script src="https://cdn.jsdelivr.net/gh/KarinWisoot/chatbot-widget@v1.0.2/dist/chatbot-widget.min.js"></script>
    <script>
      ChatBotWidget.init({
        ip: "127.0.0.1",
        apiBase: "/api/v1",
        model: "itmfec",
        prompt: "ตอนนี้ฉันอยู่หน้า {path} กรุณาช่วยแนะนำการทำงานด้วย", // {path} จะดึงค่า path ปัจจุบันมาใส่
        iconOpen: "MAI (3).png",
        iconNew: "MAI (4).png"
      });
    </script>
```
