# sna
g <- as.undirected(ba.game(1000, m=1))
l <- layout.drl(g, options=list(simmer.attraction=1))
plot(g, layout=l, vertex.size=3, vertex.label=NA)
