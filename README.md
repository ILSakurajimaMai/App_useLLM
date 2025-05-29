# AI ChatBot 🤖

Ứng dụng AI ChatBot đa nền tảng được xây dựng với React Native và Expo, hỗ trợ nhiều mô hình AI khác nhau.

## ✨ Tính năng

- 🤖 Chat với nhiều AI models: OpenAI, Grok, Gemini
- 🔄 So sánh phản hồi từ các AI models khác nhau
- 📱 Hỗ trợ đa nền tảng: iOS, Android, Web
- 🎨 Giao diện hiện đại với Material Design (React Native Paper)
- 💾 Lưu trữ lịch sử chat cục bộ
- 🔐 Quản lý API keys an toàn
- 🌙 Hỗ trợ Dark/Light mode tự động

## 🛠️ Công nghệ sử dụng

- **Framework**: React Native + Expo (SDK 53)
- **Navigation**: Expo Router với typed routes
- **UI Library**: React Native Paper
- **Language**: TypeScript
- **State Management**: React Context
- **Storage**: AsyncStorage
- **Animation**: React Native Reanimated

## 📱 Screenshots

_Thêm screenshots của app tại đây_

## 🚀 Cài đặt và chạy

### Yêu cầu hệ thống

- Node.js >= 18
- npm hoặc yarn
- Expo CLI
- Android Studio (cho Android development)
- Xcode (cho iOS development - chỉ trên macOS)

### Cài đặt

1. Clone repository:

```bash
git clone https://github.com/your-username/ai-chatbot.git
cd ai-chatbot
```

2. Cài đặt dependencies:

```bash
npm install
```

3. Thiết lập API keys:
   - Mở app và vào phần "API Key Settings"
   - Nhập API keys cho các service bạn muốn sử dụng:
     - OpenAI API Key
     - Grok API Key (X.AI)
     - Gemini API Key (Google AI)

### Chạy ứng dụng

```bash
# Chạy trên tất cả platforms
npm start

# Chỉ chạy trên Android
npm run android

# Chỉ chạy trên iOS
npm run ios

# Chạy trên web
npm run web

# Chạy ở chế độ development
npm run dev
```

## 🔧 Scripts có sẵn

```bash
npm start              # Khởi động Expo dev server (offline mode)
npm run start-local    # Khởi động với localhost only
npm run start-tunnel   # Khởi động với tunnel (online mode)
npm run android        # Chạy trên Android emulator/device
npm run ios            # Chạy trên iOS simulator/device
npm run web            # Chạy trên web browser
npm test               # Chạy tests
npm run lint           # Kiểm tra code style
npm run build:android  # Build APK/AAB cho Android
npm run build:ios      # Build IPA cho iOS
npm run clean          # Xóa cache
npm run prebuild       # Prebuild native code
```

## 📁 Cấu trúc project

```
├── app/                    # Expo Router pages
│   ├── _layout.tsx        # Root layout
│   ├── index.tsx          # Trang chủ
│   ├── chat-openai.tsx    # Chat với OpenAI
│   ├── chat-grok.tsx      # Chat với Grok
│   ├── chat-gemini.tsx    # Chat với Gemini
│   ├── chat-compare.tsx   # So sánh AI responses
│   └── api-key.tsx        # Quản lý API keys
├── src/
│   ├── components/        # Reusable components
│   ├── screens/          # Screen components
│   ├── contexts/         # React contexts
│   ├── hooks/            # Custom hooks
│   ├── api/              # API services
│   └── constants/        # Constants và configs
├── assets/               # Images, fonts, etc.
├── android/              # Native Android code
└── scripts/              # Build scripts
```

## 🔑 Cấu hình API Keys

App hỗ trợ các AI services sau:

1. **OpenAI**

   - Đăng ký tại: https://platform.openai.com/
   - Models: GPT-3.5, GPT-4, GPT-4-turbo

2. **Grok (X.AI)**

   - Đăng ký tại: https://x.ai/
   - Models: Grok-1, Grok-2

3. **Google Gemini**
   - Đăng ký tại: https://ai.google.dev/
   - Models: Gemini Pro, Gemini Pro Vision

## 🔒 Bảo mật

- API keys được lưu trữ cục bộ trên device
- Không gửi data về server central
- Tất cả requests được thực hiện trực tiếp với AI providers

## 🚧 Build cho Production

### Android

```bash
npm run build:android
```

### iOS

```bash
npm run build:ios
```

Sử dụng EAS Build service của Expo để build production apps.

## 🤝 Đóng góp

1. Fork repository
2. Tạo feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Liên hệ

- Email: hieuyvtqw@gmail.com
- Or this Github.

## 🙏 Acknowledgments

- [Expo](https://expo.dev/) - Amazing React Native framework
- [React Native Paper](https://reactnativepaper.com/) - Material Design components
- [OpenAI](https://openai.com/) - AI API services
- [Google AI](https://ai.google.dev/) - Gemini AI models
- [X.AI](https://x.ai/) - Grok AI models
