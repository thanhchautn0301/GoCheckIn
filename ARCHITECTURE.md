```bash
go-flutter-app/
├── backend/
│   ├── cmd/
│   │   └── server/
│   │       └── main.go
│   ├── internal/
│   │   ├── config/
│   │   ├── domain/
│   │   ├── repository/
│   │   ├── service/
│   │   ├── transport/
│   │   │   ├── http/
│   │   │   └── grpc/
│   │   └── utils/
│   ├── pkg/
│   ├── migrations/
│   ├── go.mod
│   └── go.sum
├── mobile/
│   ├── lib/
│   │   ├── main.dart
│   │   ├── models/
│   │   ├── services/
│   │   ├── screens/
│   │   └── widgets/
│   ├── pubspec.yaml
│   └── ios/
├── .env
├── docker-compose.yml      # optional - Không sử dụng
├── Makefile                # optional - Không sử dụng
└── README.md
