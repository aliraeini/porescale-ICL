
msSrc ?= .

all:
	@printf "\n\033[34m Please run make from git root directory first time \033[0m\n\n"
	$(MAKE) -f  ${msSrc}/script/Makefile.in  recurseMake  USE_msRecurse=1
clean:; $(MAKE) -f  ${msSrc}/script/Makefile.in  recurseClean USE_msRecurse=1
test: ; $(MAKE) -f  ${msSrc}/script/Makefile.in  recurseTest  USE_msRecurse=1
