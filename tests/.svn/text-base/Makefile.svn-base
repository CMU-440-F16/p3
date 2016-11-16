all:
	go install github.com/cmu440/tribbler/tests/libtest
	go install github.com/cmu440/tribbler/tests/storagetest
	go install github.com/cmu440/tribbler/tests/tribtest
	go install github.com/cmu440/tribbler/tests/stresstest
	go install github.com/cmu440/tribbler/runners/crunner
	go install github.com/cmu440/tribbler/runners/trunner
	go install github.com/cmu440/tribbler/runners/lrunner
	go install github.com/cmu440/tribbler/runners/srunner
	cp ${GOPATH}/bin/crunner ${GOPATH}/sols/darwin_amd64/
	cp ${GOPATH}/bin/trunner ${GOPATH}/sols/darwin_amd64/
	cp ${GOPATH}/bin/lrunner ${GOPATH}/sols/darwin_amd64/
	cp ${GOPATH}/bin/srunner ${GOPATH}/sols/darwin_amd64/


