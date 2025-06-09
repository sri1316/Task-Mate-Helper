# Trying to add an Image

This is an **spectacular** image of `Mount Fuji`


<img src="https://wallpaperaccess.com/full/48754.jpg" alt="My Diagram" width="300">

# Trying mermaid

```mermaid
graph TD  
  a[Start Car] --> b[Is fuel tank full]
  b--> |Yes| c[Is battery 100%?]
  b--> |No| d[Sound Alert Fuel Low]
  c--> |Yes| e[Is ETC Card inserted]
  c--> |No| f[Soun Alert Battery Low]
  e--> |Yes| g[Ok to Drive]
  e--> |No| h[Sound Alert Insert ETC Card]
  h--> e
