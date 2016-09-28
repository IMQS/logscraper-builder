# LogScraper builder

This is the top-level project for the LogScraper service.

This is basically just a bunch of git sub-module references and a build script.

To run the logscraper:

	env
	go run src/github.com/IMQS/logscraper/cmd/main.go

To debug the logscraper, open main.go, and change a line in there to read

	s.SendToLoggly = false

