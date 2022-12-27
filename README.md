# GO TEST

## Commands

`go test -v` 
Run all unit tests

`go tool cover -html=coverage.out`
Show in HTML elements have tests and which do not

`go test -bench=.`
Run all unit tests and brenchmark tests 

`go test -bench=. -run=^#`
Run only benchmark tests

`go test -bench=. -run=^# -benchmem`
Run only benchmark of memor3y too

`go test -fuzz=. -fuzztime=10s -run=^#`
Run Fuzzy tests, this testa run random input and verify the result 