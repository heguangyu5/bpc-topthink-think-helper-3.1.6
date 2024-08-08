libthink-helper.so:
	./bpc-prepare.sh
	$(MAKE) -C ../think libthink-helper

libthink-helper:
	bpc -v \
	    -c ../think-helper-bpc.conf \
	    -l think-helper \
	    --input-file src.list

install-libthink-helper:
	cd ../think && bpc -l think-helper --install
