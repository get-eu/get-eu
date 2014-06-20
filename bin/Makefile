all: site_connectivity.png

site_connectivity.png:
	(cd ..; bin/link_graph | dot -Tpng > bin/$@)
