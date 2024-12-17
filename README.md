# HTTP Complete Guide  

This repository contains concise and structured notes on HTTP, covering essential concepts such as headers, methods, status codes, CORS, and security policies. It is designed for beginners and professionals who want a quick reference or to enhance their understanding of HTTP.

---

## **Table of Contents**  
1. [What is HTTP?](#what-is-http)  
2. [HTTP Headers](#http-headers)  
3. [CORS (Cross-Origin Resource Sharing)](#cors-cross-origin-resource-sharing)  
4. [HTTP Methods](#http-methods)  
5. [HTTP Status Codes](#http-status-codes)  
6. [Security Policies](#security-policies)  

---

## **What is HTTP?**  
**HTTP** stands for **Hypertext Transfer Protocol**, which is the foundation of data communication on the web.

---

## **HTTP Headers**  
HTTP headers are metadata sent as key-value pairs with requests and responses. They are essential for caching, authentication, and state management.

### **Types of Headers**  
1. **Request Headers**: Sent from the client to the server.  
2. **Response Headers**: Sent from the server to the client.  
3. **Representation Headers**: Used for encoding or compression.  
4. **Payload Headers**: Related to the transmitted data.

### **Common Headers**  
- `Accept`: Specifies the content type, e.g., `application/json`.  
- `User-Agent`: Identifies the client making the request.  
- `Authorization`: Handles authentication tokens.  
- `Content-Type`: Specifies the media type of the resource.  
- `Cookie`: Includes stored data for client-server communication.  
- `Cache-Control`: Defines caching policies.

---

## **CORS (Cross-Origin Resource Sharing)**  
CORS policies manage access across different origins. Important headers include:  
- `Access-Control-Allow-Origin`  
- `Access-Control-Allow-Credentials`  
- `Access-Control-Allow-Methods`  

---

## **HTTP Methods**  
HTTP methods define operations that can be performed on a resource:  

| **Method** | **Description**                            |  
|------------|--------------------------------------------|  
| `GET`      | Retrieve a resource.                      |  
| `HEAD`     | Retrieve headers without the body.        |  
| `OPTIONS`  | Discover available operations.            |  
| `TRACE`    | Perform a loop-back test.                 |  
| `DELETE`   | Remove a resource.                        |  
| `PUT`      | Replace a resource.                       |  
| `POST`     | Add or interact with a resource.          |  
| `PATCH`    | Modify part of a resource.                |  

---

## **HTTP Status Codes (Commonly Used)**  
Status codes indicate the outcome of an HTTP request.  

### **Categories**  
1. **1xx (Informational)**  
   - `100`: Continue  
   - `102`: Processing  

2. **2xx (Success)**  
   - `200`: OK  
   - `201`: Created  
   - `202`: Accepted  

3. **3xx (Redirection)**  
   - `307`: Temporary Redirect  
   - `308`: Permanent Redirect  

4. **4xx (Client Errors)**  
   - `400`: Bad Request  
   - `401`: Unauthorized  
   - `402`: Payment Required  
   - `403`: Forbidden  
   - `404`: Not Found  

5. **5xx (Server Errors)**  
   - `500`: Internal Server Error  
   - `504`: Gateway Timeout  

---

## **Security Policies**  
Security headers help protect applications against common vulnerabilities.  

### **Common Security Headers**  
- `Content-Security-Policy`: Controls resources the browser is allowed to load.  
- `X-XSS-Protection`: Protects against cross-site scripting attacks.  
- `Cors-Origin-Embedder-Policy`: Prevents resource embedding.  
- `Cors-Origin-Opener-Policy`: Controls opener access.

---

