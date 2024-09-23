SOURCE_FOLDER ?= source

.PHONY: install
install::
	@echo "Running install target"
	@npm --prefix $(SOURCE_FOLDER) config set legacy-peer-deps true 
	@npm --prefix $(SOURCE_FOLDER) install

.PHONY: test
test::
	@echo "Running test target"
	@npm --prefix $(SOURCE_FOLDER) run test 

.PHONY: build
build::
	@echo "Running build target"
	@npm --prefix $(SOURCE_FOLDER) run build 

