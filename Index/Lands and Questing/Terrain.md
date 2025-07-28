
This page is a Work In Progress and needs to be expanded on. Major aspects of this note are outdated and missing important context. #WIP #Outdated 

We have two main options on how terrain may be generated.

# Marching Cubes

One option is to use a cube grid around the entire universe (or perhaps many small local grids) and the marching cubes algorithm to smooth out hard corners. I think this is what they do in No Man's Sky.

However, this might not be very usable for things that fall off-grid or are too small to fit on the grid, and having too big of a grid might consume too much RAM.

# Triangle Mesh

The other option is to forego a grid entirely and operate directly on mesh data. This might be more usable for SBURB since you can alter orientation and length however you might need to. This also has the benefit of allowing objects to be physics-compatible, since they don't need to adhere to a grid.

However, this is known for being very slow... unless we can find a way around that.![[Untitled Diagram.svg]]
```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.7.19 - 18.07pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```
