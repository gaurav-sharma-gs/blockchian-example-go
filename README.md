grab the following packages:

go get github.com/davecgh/go-spew/spew

Spew allows us to view structs and slices cleanly formatted in our console. This is nice to have.

go get github.com/gorilla/mux

Gorilla/mux is a popular package for writing web handlers. We’ll need this.

go get github.com/joho/godotenv

Godotenv lets us read from a .env file that we keep in the root of our directory so we don’t have to hardcode things like our http ports. We’ll need this too.