This is the folder containing the assembly of pump V8.1, as well as all of the associated files as of 9/24/2024.

-------------------------------------------------------------------

--Version Notes--

Labyrinth seal geometry has been semi finalized: Ok-ed by a sealing expert, have to review manufacturability of teeth

Added a flange with countersunk clearance hole to the labyrinth seal for preventing rotation of the seal

Added 4 4-48 flathead screws to assembly for labyrinth seal flange

Added a parts list section to README file

Added version notes section to README file

Added to do section to README file

-------------------------------------------------------------------

--To Do--

A final bearing span needs to be set by running rotor dynamic simulations (currently set to a temporary 1.5")

Wave spring needs to be added to assembly: part needs to be found and imported, compressed height needs to be finalized
	-thinking of adding the imported part to cad (won't be compressed), but having the distance between the top bearing and
	 bottom housing lip be the correct compressed spring distance

-------------------------------------------------------------------

--Folder Organization--

Pump X.X -> Rotational/Stationary Parts -> Custom/Imported Parts -> Part Types -> Part Attributes -> Part Files

*Part Attributes can mean part measurements, properties, materials, etc.

*Measurement numbers in file/folder names are in inches unless otherwise noted

Naming of part files does not strictly follow the folder sequence said file is located in; however, file names do contain identifying information of said part.

*Do not delete unused parts from folders, having a database of models for different part will save time in the future

-------------------------------------------------------------------

--Folder Organization Visual--

Pump 8.1
	Engineering Drawings

	Rotational Parts
		Custom Rotational Parts
			304 Stainless Steel
				PumpImpeller_8.1
				PumpShaft_8.1

		Imported Rotational Parts
			Bearings
				0.5ID 1.125OD
					440C Stainless Steel
						6138K25_Stainless Steel Ball Bearing.STEP
						BallBearing_Shielded_0.5ID_1.125OD

				12mmID 37mmOD
					440C Stainless Steel
						BallBearing_Shielded_0.5ID_1.125OD
						BallBearing_Shielded_12mmID_37mmOD
			Shaft Sleeve
				C954 Aluminum Bronze
					ShaftSleeve_8.1_temp

	Static Parts
		Custom Static Parts
			304 Stainless Steel
				PumpBearingCap_8.1
				PumpHousingBottom_8.1
				PumpHousingTop_8.1

			Grade 621 PTFE
				PumpLabyrinthSeal_8.1

		Imported Static Parts
			Lip Seals
				0.5ID 0.875OD
					Buna-N Rubber
						5154T11_Spring-Loaded Rotary Shaft Seal.STEP
						LipSeal_0.5ID_0.875OD

				12mmID 22mmOD
					Buna-N Rubber
						5154T63_Spring-Loaded Rotary Shaft Seal.STEP
						LipSeal_12mmID_22mmOD

			Locknuts
				10-32
					18-8 Stainless Steel
						91831A411_18-8 Stainless Steel Nylon-Insert Locknut.STEP
						Locknut_10-32

			NPT Adapters
				Straight Adapters
					Male-Male
						0.5-0.5
							316 Stainless Steel
								50715K802_37 Degree Flared Fitting for Stainless Steel Tubing.STEP
								NPTAdapter_Male_Male_0.5-0.5

						0.25-0.25
							316 Stainless Steel
								50715K795_37 Degree Flared Fitting for Stainless Steel Tubing.STEP
								NPTAdapter_Male-Male_0.25-0.25

						0.125-0.25
							316 Stainless Steel
								50715K794_37 Degree Flared Fitting for Stainless Steel Tubing.STEP
								NPTAdapter_Male-Male_0.125-0.25

						0.125-0.125
							316 Stainless Steel
								50715K793_37 Degree Flared Fitting for Stainless Steel Tubing.STEP
								NPTAdapter_Male-Male_0.125-0.125

						0.375-0.375
							316 Stainless Steel
								50715K799_37 Degree Flared Fitting for Stainless Steel Tubing.STEP
								NPTAdapter_Male-Male_0.375-0.375

			O-Rings
				2-022
					PTFE
						9559K116_Ultra-Chemical-Resistant Rigid PTFE O-Ring.STEP
						ORing_PTFE_2-022

				2-024
					PTFE
						9559K118_Ultra-Chemical-Resistant Rigid PTFE O-Ring.STEP
						ORing_PTFE_2-024

				2-042
					PTFE
						9559K338_Ultra-Chemical-Resistant Rigid PTFE O-Ring.STEP
						ORing_PTFE_2-042

			Retaining Rings
				0.875ID 0.971OD
					15-7 PH Stainless Steel
						91580A191_Internal Retaining Ring.STEP
						RetainingRing_Internal_0.875ID_0.971OD

				1.125ID 1.249OD
					15-7 PH Stainless Steel
						91580A221_Internal Retaining Ring.STEP
						RetainingRing_Internal_1.125ID_1.249OD

				1ID 1.111OD
					15-7 PH Stainless Steel
						91580A211_Internal Retaining Ring.STEP
						RetainingRing_Internal_1ID_1.111OD

			Screws
				4-48
					Fully Threaded
						Flat Head
							0.375Length
								18-8 Stainless Steel
									92210A024_18-8 Stainless Steel Hex Drive Flat Head Screw.STEP
									Screw_Flathead_4-48_0.375Length

				6-40
					Fully Threaded
					Partially Threaded
						1Length
							0.75Thread
								18-8 Stainless Steel
									92196A765_18-8 Stainless Steel Socket Head Screw.STEP
									Screw_PartialThread_6-40_1Length_0.75Thread

				8-36
					Fully Threaded
						0.5Length
							18-8 Stainless Steel
								92196A217_18-8 Stainless Steel Socket Head Screw.STEP
								Screw_8-36_0.5Length

					Partially Threaded
				10-32
					Fully Threaded
						0.5Length
							18-8 Stainless Steel
								92196A269_18-8 Stainless Steel Socket Head Screw.STEP
								Screw_10-32_0.5Length

					Partially Threaded
						1.25Length
							0.875Thread
								18-8 Stainless Steel
									92196A276_18-8 Stainless Steel Socket Head Screw.STEP
									Screw_PartialThread_10-32_1.25Length_0.875Thread

			Washers
				Size 6
					316 Stainless Steel
						90107A007_316 Stainless Steel Washer.STEP
						Washer_6

	PumpAssembly_8.1

	README

-------------------------------------------------------------------

--Parts List--

Material:                 Type:                 Part:            Size:                   Number:

-Custom Parts-

304 Stainless Steel                             Housing Top                              (1)
304 Stainless Steel                             Housing Bottom                           (1)
304 Stainless Steel                             Bearing Cap                              (1)
304 Stainless Steel                             Impeller                                 (1)
304 Stainless Steel                             Shaft                                    (1)

Grade 621 PTFE                                  Labyrinth Seal                           (1)

-Imported Parts-

18-8 Stainless Steel      4-48 Flathead         Screw            3/8" Length             (4)
18-8 Stainless Steel      6-40 Partial Thread   Screw            1" Length 3/4" Thread   (1)
18-8 Stainless Steel      10-32 Full Thread     Screw            1/2" Length             (4)
18-8 Stainless Steel      10-32 Full Thread     Screw            1-1/3" Length           (12)

18-8 Stainless Steel      10-32                 Locknut                                  (12)

316 Stainless Steel       Size 6                Washer                                   (1)

316 Stainless Steel       Male-Male Straight    NPT Adapter      1/8"-1/4" Pipe          (1)
316 Stainless Steel       Male-Male Straight    NPT Adapter      3/8"-3/8" Pipe          (1)
316 Stainless Steel       Male-Male Straight    NPT Adapter      1/2"-1/2" Pipe          (1)

440C Stainless Steel      Shielded              Ball Bearing     12mmID 37mmOD           (2)

15-7 PH Stainless Steel   Internal              Retaining Ring   7/8"ID 0.971"OD         (1)

PTFE                                            O-Ring           2-022                   (1)
PTFE                                            O-Ring           2-042                   (1)

Buna-N Rubber                                   Lip Seal         12mmID 22mmOD           (1)

-------------------------------------------------------------------

The pump V8.1 CAD was made by Charlie Pluth.

Email:
cpluth2@illinois.edu

Slack Username:
Charlie Pluth
