
mobile.html: inc/mobile.head.html index.html
	(cat $<; sed '/<!DOCTYPE html>/,/<\/head>/d' $^ | \
		grep -v -e 'script src="js/jquery-' -e 'script src="js/bootstrap') > $@

clean:
	rm -f mobile.html

.PHONY: clean
