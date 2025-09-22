# Go CI Sample Project

Run locally:

1. go mod download
2. go test ./... -v
3. go run main.go

Endpoints:
- GET /health -> {"status":"ok"}
- GET /add?a=1&b=2 -> {"result":3}

Assignment ideas for students:
- Create a CI pipeline (GitHub Actions/GitLab CI) that runs tests and linters and reports coverage.
- Add caching of Go modules between runs.
- Add a job matrix to test Go 1.20, 1.21, 1.22.
- Add artifact upload of coverage results.
