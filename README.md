# ibm_final_project

**Emotion Detection** – an AI-based web application that detects emotions (anger, disgust, fear, joy, sadness) in text using the Watson NLP library and Flask. Final project of the IBM AI Developer course.

Ứng dụng web phát hiện cảm xúc (Emotion Detection) dùng Watson NLP và Flask, final project khóa IBM AI Developer.

## File nộp theo từng task

| Task | Activity | Cách nộp | File | Trạng thái |
|------|----------|----------|------|------------|
| 2 | 1 | Dán code | `2a_emotion_detection` | ✅ |
| 2 | 2 | Dán output terminal | `2b_application_creation` | ✅ |
| 3 | 1 | Dán code | `3a_output_formatting` | ✅ |
| 3 | 2 | Dán output terminal | `3b_formatted_output_test` | ✅ |
| 4 | 1 | Nộp link GitHub | [EmotionDetection/\_\_init\_\_.py](https://github.com/luukhanhvinh1214/ibm_final_project/blob/main/EmotionDetection/__init__.py) | ✅ |
| 4 | 2 | Dán output terminal | `4b_packaging_test` | ✅ |
| 5 | 1 | Dán code | `5a_unit_testing` | ✅ |
| 5 | 2 | Dán output terminal | `5b_unit_testing_result` | ⏳ Chưa có: chạy `python3.11 test_emotion_detection.py` trong lab |
| 6 | 1 | Dán code | `6a_server` | ✅ |
| 6 | 2 | Upload ảnh | `6b_deployment_test.png` | ✅ |
| 7 | 1 | Dán code | `7a_error_handling_function` | ✅ |
| 7 | 2 | Dán code | `7b_error_handling_server` | ✅ |

"Dán code" / "Dán output terminal": mở file, copy toàn bộ nội dung, dán vào ô nộp bài.

## Cấu trúc dự án

```
├── EmotionDetection/
│   ├── __init__.py               # import module ứng dụng
│   └── emotion_detection.py      # hàm emotion_detector gọi Watson NLP
├── server.py                     # Flask server, route /emotionDetector
└── test_emotion_detection.py     # unit test 5 cảm xúc
```

Thư mục `templates/` và `static/` lấy từ repo khóa học
[oaqjp-final-project-emb-ai](https://github.com/ibm-developer-skills-network/oaqjp-final-project-emb-ai).

## Chạy trong lab IBM

Watson NLP chỉ truy cập được trong lab IBM Skills Network, không chạy được ở máy cá nhân.

```bash
python3.11 test_emotion_detection.py   # chạy unit test
python3.11 server.py                   # chạy web app ở port 5000
```
