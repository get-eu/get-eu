all: site_connectivity.png

site_connectivity.dot:
	(cd ..; bin/link_graph) > $@

site_connectivity.png: site_connectivity.dot
	dot -Tpng < $< > $@

clean:
	rm -f -- site_connectivity.png site_connectivity.dot

