# Color-Recognizing-and-Sequencing-Machine
A ladder diagram for Siemens PLC 
Consider a conveyor which has a single DC motor located at the drum of a conveyor
and a pneumatic linear lifting crane. This project aims to sort incoming products in two
different stations. Products are a (matte red), b (matte black) and c (metallic gray). These
products, which are coming from the conveyor band (with N rpm) without a specific order,
will be taken from the light barrier sensor dent which is located at the middle of the band and
be placed on the correct station in the correct order. The entries to the dent will be made by an
electric gate or an air pump. Product entries will be made only through the conveyor band
(through a detection module at the beginning of the band). Detection module has a diffuse
sensor, a fork light barrier and an inductive sensor. Order of each station will be made by the
position sensors.Priority will be given to the first station, and if the incoming product is in the
right order, then, it will be placed. Otherwise, the product will not be placed to the dent and be
dropped at the end of the conveyor line.After that conveyor will increase its speed until the
desired product is detected.The process will start by resetting the memory and the counters.
