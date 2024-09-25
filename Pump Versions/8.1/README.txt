This is the folder containing the assembly of pump V8.1, as well as all of the associated files as of 9/24/2024.

-------------------------------------------------------------------

--Version Notes--

Labyrinth seal geometry has been semi finalized: Ok-ed by a sealing expert, have to review manufacturability of teeth

Added a flange with countersunk clearance hole to the labyrinth seal for preventing rotation of the seal

Added 4 4-48 flathead screws to assembly for labyrinth seal flange

Added a parts list section to README file

Added version notes section to README file

Added to do section to README file

Removed folder organization visual -> too large for the visual to be useful

-------------------------------------------------------------------

--To Do--

A final bearing span needs to be set by running rotor dynamic simulations (currently set to a temporary 1.5")

Wave spring needs to be added to assembly: part needs to be found and imported, compressed height needs to be finalized
	-thinking of adding the imported part to cad (won't be compressed), but having the distance between the top bearing and
	 bottom housing lip be the correct compressed spring distance

May increase inlet NPT Adapter size to 3/4" for better compatibility with the test stand, TBD

-------------------------------------------------------------------

--Folder Organization--

Pump X.X -> Rotational/Stationary Parts -> Custom/Imported Parts -> Part Types -> Part Attributes -> Part Files

*Part Attributes can mean part measurements, properties, materials, etc.

*Measurement numbers in file/folder names are in inches unless otherwise noted

Naming of part files does not strictly follow the folder sequence said file is located in; however, file names do contain identifying information of said part.

*Do not delete unused parts from folders, having a database of models for different part will save time in the future

-------------------------------------------------------------------

--Parts List--

Material:                 Type:                  Part:            Size:                   Number:

-Custom Parts-

304 Stainless Steel                              Housing Top                              (1)
304 Stainless Steel                              Housing Bottom                           (1)
304 Stainless Steel                              Bearing Cap                              (1)
304 Stainless Steel                              Impeller                                 (1)
304 Stainless Steel                              Shaft                                    (1)

Grade 621 PTFE                                   Labyrinth Seal                           (1)

-Imported Parts-

18-8 Stainless Steel      4-48 Flathead          Screw            3/8" Length             (4)
18-8 Stainless Steel      6-40 Partial Thread    Screw            1" Length 3/4" Thread   (1)
18-8 Stainless Steel      10-32 Full Thread      Screw            1/2" Length             (4)
18-8 Stainless Steel      10-32 Full Thread      Screw            1-1/3" Length           (12)

18-8 Stainless Steel      10-32                  Locknut                                  (12)

316 Stainless Steel       Size 6                 Washer                                   (1)

316 Stainless Steel       Male-Male Straight     NPT Adapter      1/8"-1/4" Pipe          (1)
316 Stainless Steel       Male-Male Straight     NPT Adapter      3/8"-3/8" Pipe          (1)
316 Stainless Steel       Male-Male Straight     NPT Adapter      1/2"-1/2" Pipe          (1)

440C Stainless Steel      Shielded Deep Groove   Ball Bearing     12mmID 37mmOD           (2)

15-7 PH Stainless Steel   Internal              Retaining Ring   7/8"ID 0.971"OD         (1)

PTFE                                             O-Ring           2-022                   (1)
PTFE                                             O-Ring           2-042                   (1)

Buna-N Rubber                                    Lip Seal         12mmID 22mmOD           (1)

-------------------------------------------------------------------

The pump V8.1 CAD was made by Charlie Pluth.

Email:
cpluth2@illinois.edu

Slack Username:
Charlie Pluth
