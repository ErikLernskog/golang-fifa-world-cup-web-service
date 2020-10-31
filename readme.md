# test
go test -v ./handlers/

# module 1
go test -v ./handlers/handlers.go ./handlers/handlers_test_helpers.go ./handlers/01_get_handler_test.go
# module 2
go test -v ./handlers/handlers.go ./handlers/handlers_test_helpers.go ./handlers/02_post_handler_test.go
# module 3
go test -v ./handlers/handlers.go ./handlers/handlers_test_helpers.go ./handlers/03_dispatch_handler_test.go

# run 
go run server.go