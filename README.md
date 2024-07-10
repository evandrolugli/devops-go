### DevOps

Technology: Go
Version: 1.22.4
Port: 8080
Database: Postgres

### Steps

Local:
    - prepare (installing dependencies)
    - execute (run application, using 'go run')

Production:
    - prepare (installing dependencies)
    - build
    - execute (run application, using binary from build)

### Commands

installing dependencies
>> go mod download && go mod verify

run application (from go run)
>> go run cmd/journey/journey.go

build application
>> go build cmd/journey/journey.go

run application (from binary)
>> ./journey

# GitHub
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/evandrolugli/devops-go.git
git push -u origin main