# Lab-03 Submission - 411177003

## 1) Invoke URL
- （先留空，等你 deploy prod 後再填）


## 3) curl Commands + Full Outputs（一定要「指令＋完整輸出」）
## 1) /health

```bash
# apiId = yff963l50b
# region = ap-southeast-2
curl -i https://yff963l50b.execute-api.ap-southeast-2.amazonaws.com/prod/api/v1/health

# --- OUTPUT ---
HTTP/2 200 
content-type: application/json
content-length: 15
date: Fri, 19 Dec 2025 17:30:41 GMT

{"status":"ok"}
