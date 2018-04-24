CSCE 747 Homework 4

The model will assume that traffic lights in north/south and east/west direction will always be the same color
ped_light_NS is the crosswalk going north or south on either side
ped_light_EW is the crosswalk going east or west on either side

Assume that cars will yield to pedestrians when turning left or right

How to run model
$ NuSMV -int assignment4.smv
> go
> pick_state -r
> simulate -r -k 3
> show_traces -v

