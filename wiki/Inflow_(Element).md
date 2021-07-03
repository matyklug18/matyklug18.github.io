![Various types of Inflow.](https://static.wikia.nocookie.net/oecake/images/a/a4/Inflow.jpg/revision/latest/scale-to-width-down/180?cb=20090511162323)

**Inflow** creates particles from a source. Although the default material is set to Water, when mixed with another element it becomes a source for it. Inflow particles can be a liquid, a solid, or a wall.

Inflow only emits liquid when it touches something, including another Inflow particle. Any material will work, but a single point of Inflow does nothing. Once the reaction has started, the newly spawned particles often keep the reaction going. An Inflow source can be destroyed when combined with Powder or Fuel.

The only elements that cannot be inflowed are Rigid, Wall, Delete, and [Users](/wiki/User "User") . Inflow combined with Users will allow the source particles to be moved. A liquid form of [Axis](/wiki/Rigid_Axis "Rigid Axis") can be inflowed. There can be an Inflow for [Outflow](/wiki/Outflow "Outflow") , too.

###  Uses 

Pure Inflow (made in [Mix Mode](/wiki/Mix_Mode "Mix Mode") by pressing *esc+I+esc)* behaves like a liquid, and when shaken or hit hard enough it will create a very large amount of liquid almost like a bomb. Pure Inflow generates material \"N\", [Null](/wiki/Null "Null") liquid.

*standardDistance* in the Parameters strongly affects how Inflow works. Changing the density of the source Inflow section changes how aggressively it Inflows particles, independent of *standardDistance* . The actual inflow process itself is also controlled by *standardDistance* , which determines how close or far the particles are spawned from the source. Very high *standardDistance* values will actually make the Inflow happen far away from the Inflow particles themselves! Very low *standardDistance* values create a smoother, higher volume flow.
