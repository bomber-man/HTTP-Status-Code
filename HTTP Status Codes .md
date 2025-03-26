# 🌐 HTTP Status Codes - A Comprehensive Guide 🚀

HTTP status codes are **server responses** to browser requests. They help developers and testers **understand what’s happening between the client and server**.  

📌 **This guide covers**:  
✅ What HTTP Status Codes are & why they matter  
✅ Explanation of each category (1xx - 5xx)  
✅ Common status codes with examples  
✅ Troubleshooting tips  

---

## 🔹 **What Are HTTP Status Codes?**
HTTP status codes are **three-digit numbers** returned by a web server in response to a request. They indicate whether the request was successful, redirected, caused an error, or encountered a server issue.

🚀 **Example:**  
When you visit a webpage and see **"404 Not Found"**, it means the requested page does not exist.

---

## 📊 **Categories of HTTP Status Codes**
HTTP Status Codes are divided into **five main categories**:

| Category | Code Range | Description |
|----------|-----------|-------------|
| 🔵 **1xx** | `100-199` | **Informational** responses (Request received, processing continues) |
| 🟢 **2xx** | `200-299` | **Success** (The request was successfully received, understood, and accepted) |
| 🟠 **3xx** | `300-399` | **Redirection** (Further action is required to complete the request) |
| 🔴 **4xx** | `400-499` | **Client Errors** (The request contains bad syntax or cannot be fulfilled) |
| ⚫ **5xx** | `500-599` | **Server Errors** (The server failed to fulfill a valid request) |

---

## ✅ **1xx - Informational Responses**
These codes indicate that the **server has received the request** and is processing it.

| Status Code | Meaning | Description |
|-------------|---------|-------------|
| **100 Continue** | ✅ Success | Server received the request and asks the client to proceed. |
| **101 Switching Protocols** | 🔄 Transition | Server switches to a different protocol as requested. |
| **103 Early Hints** | 🔍 Optimization | Provides response headers before the final response. |

---

## 🎯 **2xx - Success Codes**
These codes mean **the request was successfully processed**.

| Status Code | Meaning | Description |
|-------------|---------|-------------|
| **200 OK** | ✅ Success | The request was successful (standard response for GET requests). |
| **201 Created** | 🆕 Resource Created | The request was successful, and a new resource was created. |
| **202 Accepted** | 📌 Processing | The request has been accepted but is still being processed. |
| **204 No Content** | 🚫 No Response | The request was successful, but there is no content to return. |

---

## 🔄 **3xx - Redirection Codes**
These codes mean **further action is needed** to complete the request.

| Status Code | Meaning | Description |
|-------------|---------|-------------|
| **301 Moved Permanently** | 🔀 Permanent Redirect | The resource has been permanently moved. |
| **302 Found (Temporary Redirect)** | 🔀 Temporary Redirect | The resource is temporarily moved. |
| **304 Not Modified** | 🗂️ Cached Response | The requested resource hasn't changed since the last request. |

---

## ❌ **4xx - Client Errors**
These indicate **issues with the client’s request**.

| Status Code | Meaning | Description |
|-------------|---------|-------------|
| **400 Bad Request** | ⚠️ Invalid Request | The server cannot process the request due to client error. |
| **401 Unauthorized** | 🔑 Authentication Needed | Authentication is required to access the resource. |
| **403 Forbidden** | 🚫 Access Denied | The server understands the request but refuses to authorize it. |
| **404 Not Found** | ❌ Resource Missing | The requested page does not exist. |
| **429 Too Many Requests** | ⏳ Rate Limit Exceeded | The client has sent too many requests in a short period. |

---

## 💥 **5xx - Server Errors**
These indicate **problems on the server side**.

| Status Code | Meaning | Description |
|-------------|---------|-------------|
| **500 Internal Server Error** | ⚠️ Server Crash | A general error occurred on the server. |
| **502 Bad Gateway** | 🔄 Upstream Error | The server received an invalid response from another server. |
| **503 Service Unavailable** | 🚧 Server Overloaded | The server is temporarily unable to handle requests. |
| **504 Gateway Timeout** | ⏳ Request Timeout | The upstream server failed to respond in time. |

---

## 🛠 **Troubleshooting HTTP Errors**
**🔹 Steps to Fix Client Errors (4xx):**  
✔ **Check URL** for typos in the request.  
✔ **Verify API Keys** if you receive a **401 Unauthorized** error.  
✔ **Review Request Headers** for missing required fields.  

**🔹 Steps to Fix Server Errors (5xx):**  
✔ **Check Server Logs** for crash reports or configuration issues.  
✔ **Increase Server Capacity** to prevent **503 Service Unavailable** errors.  
✔ **Verify Upstream Services** if facing **502 Bad Gateway** issues.  

---

## 📚 **More Resources**
📖 [MDN Web Docs - HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) 
📖 [REST API Best Practices](https://restfulapi.net/)  

---

## 📌 **Contribute to This Repository**
Want to improve this guide? 🚀  
1. **Fork the repository** 🍴  
2. **Make your changes** and commit them  
3. **Create a pull request** 🔥  

---

## 💬 **Connect with Me**
💼 **LinkedIn:** [Ashish Kumar Bhai](https://linkedin.com/in/ashish-kumar-bhai-948911176)  
🐦 **Twitter:** [@AshishKumarBhai](https://twitter.com/AshishKumarBhai)  
💻 **GitHub:** [bomber-man](https://github.com/bomber-man)  

---

⭐ **If you found this guide helpful, don’t forget to give it a star!** ⭐  
