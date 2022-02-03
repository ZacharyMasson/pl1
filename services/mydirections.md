# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?language=fr-CA&departure_time=now&avoid=highways&traffic_model=pessimistic&destination=place_id:ChIJ71G6otQ5yUwR3Q5nFa-7-F8&origin=place_id:ChIJN_HpREjlyEwRxWOUPztQC8Y&waypoints=optimize:false|via%3Aplace_id:ChIJ7Th5_mcayUwRW4fuN3vzAOE|via%3Aplace_id:ChIJNVbgsD8ayUwRXLRbMTGcK5Y&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJN_HpREjlyEwRxWOUPztQC8Y",
         "types" : [ "establishment", "park", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ7Th5_mcayUwRW4fuN3vzAOE",
         "types" : [ "establishment", "point_of_interest", "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJNVbgsD8ayUwRXLRbMTGcK5Y",
         "types" : [
            "amusement_park",
            "establishment",
            "point_of_interest",
            "tourist_attraction"
         ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ71G6otQ5yUwR3Q5nFa-7-F8",
         "types" : [ "establishment", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 45.7018269,
               "lng" : -73.47916499999999
            },
            "southwest" : {
               "lat" : 45.4197367,
               "lng" : -73.97047409999999
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "76,1 km",
                  "value" : 76149
               },
               "duration" : {
                  "text" : "2 heures 19 minutes",
                  "value" : 8322
               },
               "duration_in_traffic" : {
                  "text" : "2 heures 46 minutes",
                  "value" : 9977
               },
               "end_address" : "104 Ch Senneville, Senneville, QC H9X 1B9, Canada",
               "end_location" : {
                  "lat" : 45.4197367,
                  "lng" : -73.9670302
               },
               "start_address" : "Parc du Bout-de-l'Île, 18 Rue Bureau, Pointe-aux-Trembles, QC H1A 1Z5, Canada",
               "start_location" : {
                  "lat" : 45.7018269,
                  "lng" : -73.47918799999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "55 m",
                        "value" : 55
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 45.7017448,
                        "lng" : -73.479545
                     },
                     "html_instructions" : "Aller en direction \u003cb\u003esud-est\u003c/b\u003e sur \u003cb\u003eRue Bureau\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mc}uG|kn_MBEBCBCDAB?B@BBBBBF@F?FAB?@Sl@"
                     },
                     "start_location" : {
                        "lat" : 45.7018269,
                        "lng" : -73.47918799999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "79 m",
                        "value" : 79
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.7012937,
                        "lng" : -73.48030589999999
                     },
                     "html_instructions" : "Tourner à \u003cb\u003egauche\u003c/b\u003e pour continuer sur \u003cb\u003eRue Bureau\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{b}uGbnn_MPn@DNDLFHJHHL\\h@"
                     },
                     "start_location" : {
                        "lat" : 45.7017448,
                        "lng" : -73.479545
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 219
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 65
                     },
                     "end_location" : {
                        "lat" : 45.7008277,
                        "lng" : -73.4829984
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà droite\u003c/b\u003e sur \u003cb\u003e100e Avenue\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a`}uG|rn_MCLAJAF?F?DL|@^hDp@|F@@?@@?"
                     },
                     "start_location" : {
                        "lat" : 45.7012937,
                        "lng" : -73.48030589999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,7 km",
                        "value" : 708
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 45.6955886,
                        "lng" : -73.4870564
                     },
                     "html_instructions" : "\u003cb\u003e100e Avenue\u003c/b\u003e tourne à \u003cb\u003egauche\u003c/b\u003e et devient \u003cb\u003eTerr. Sainte-Maria-Goretti\u003c/b\u003e",
                     "polyline" : {
                        "points" : "e}|uGvco_MvAWRCRCT?R?TBVBZF`@Fh@L`@JLDPHPHNHPLPN`@\\bBlBx@z@\\^l@p@vGpH`@f@DFBD@F?H@HAH?JAb@"
                     },
                     "start_location" : {
                        "lat" : 45.7008277,
                        "lng" : -73.4829984
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20,2 km",
                        "value" : 20201
                     },
                     "duration" : {
                        "text" : "36 minutes",
                        "value" : 2177
                     },
                     "end_location" : {
                        "lat" : 45.5256861,
                        "lng" : -73.5454857
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà gauche\u003c/b\u003e sur \u003cb\u003eRue Notre Dame E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m|{uGb}o_Md@d@NNJJNNPPJJZTJHLFJFPFRF\\HXH~@NhB\\~Ch@|@PnAVnGhAlCf@fAR`@Fd@HLBvCh@rCh@d@JrCf@nIzAdARrB\\|@PdCb@j@H`APJ@B@jEt@|HvAXFx@NvARz@LzBRvBTD@p@Hl@FtAN~@NF?D@vBXlDb@rC\\TBxBZ`ANlAXvCd@zCb@nARpCb@dANRBR@R@V?vB?rC@R?t@?`A@dA?ZA^?R?HAB?F?LAH?LCJAD?PC`@GHAz@KvC_@JCtCa@nDg@jDe@dBWzASj@I`C_@nASbAQhASnAWbAU~Aa@f@IdAUf@Oh@QTKZOTKd@Yv@c@ZQzBuA~AaATOLGJGNGPI`@MPGhA[r@SfBi@TGZKXKRIRIXOJGv@c@tBmAzA{@NKPIRKRKj@Sb@Ol@SXEZGNANAZ?X?\\?R@VBVBXF\\HNDz@X`AZfA\\pAd@nG~BPFXFTFZFZFPBXDPB\\FXB\\B`CJ`CJv@BvAH`@BfAHj@D\\BhAJ`AJdALNDRDPBNDPBb@LLDJDNFTHp@X`CbAbCdAzBbA~BdAr@Xl@RXHZNl@Tz@Xh@P\\LFBJDZNNFRL^TLJTP\\Xh@d@ZVVRXVz@z@pB`C|BhCvB`CdCrCnB|Bn@r@~@fAx@~@~@dApAzAJLp@r@~AjBNPRVtA|A`BjBlBxBxA`BxChD~@dAt@t@TRx@p@`Ap@l@\\hAn@j@VtEtBdFbClI|DnBx@`Ab@XLNHPFl@TrCdAvAf@z@XxAd@t@RrBh@hJbCjA\\pCt@tCt@|Cv@`Cn@fBb@dBb@p@Pn@NvAPbAXXFbATr@L\\Fr@Jd@DHBf@Fp@HpAJjAJlAFzAFj@BrBBR@v@DR@X?tAETA^AR?hAG~CU`D]vCQvD[~Dg@vB[`AQxDu@j@Ot@SlCu@jCy@HCd@QPG|@WRGxBs@bCy@|G{BVBlDoAlDkA@Ar@SXITGTEVE`@EVAXAXAXAj@AV?ZDf@H\\HPF\\LZLVLt@h@d@^ZX`BzAnCjCpAfAzAlAxBjB\\X`BvAxGxFhA~@rBfBvBfBh@d@hA~@rC~BdA|@vAlAnHfGbElDp@h@tAjAJJdBvATPzBfBHHRN~@p@TPt@f@ZRf@Zn@^f@ZVLRLh@Zr@\\dAh@~At@JDNDTJfBf@j@P|EnA^JfBf@nAZLDl@R|Cx@~Cp@r@LHBlBd@~DbA^H^Hj@PPFJBB@PHVPPN~@v@LJJHhCrBbAr@VN`@VHB@?@?FC~DvBHDbAd@@J@@BBDDt@X\\NfAd@LFNFNHFBPChCrAlBjA`CxAbDfB@?dG`D`@RfDdBRZj@XtAt@DBnChAn@^j@XbCnAhAv@TNVNxBfAnDpBlB~@^RRJTJXJ?@^JrA^JB`@LTFVJZLPHFBTLl@\\d@VTN^R^TDDdAv@z@n@pBvArDlCLJLJ~AlArCxBbAx@DDXRb@\\tAlA\\ZBBhBjBd@`@VTn@d@h@\\v@d@LFZJd@Np@N`@Jb@JdFnArAZ~Bh@f@JF@`@JdAVdAV\\HD@`@LXHH@^Jb@J`@JHBVHFBVHZLNFh@RXJVL\\NZNTLFDb@T~Bx@NDNDbA\\bBb@f@Nd@JLDNDPDTDRD`@FRBTBP@TBN@R@T@X@z@D"
                     },
                     "start_location" : {
                        "lat" : 45.6955886,
                        "lng" : -73.4870564
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3,0 km",
                        "value" : 3013
                     },
                     "duration" : {
                        "text" : "10 minutes",
                        "value" : 608
                     },
                     "end_location" : {
                        "lat" : 45.5030704,
                        "lng" : -73.5665077
                     },
                     "html_instructions" : "Tourner légèrement \u003cb\u003eà droite\u003c/b\u003e sur \u003cb\u003eBd René-Lévesque E\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "qvztGhj{_MVTFDZJJDb@Nf@Z`@\\n@lA|@bB@BvA`CNTNRl@p@NP@@FFDBpCbCjAfAh@d@rAhAPNjCbCfA`A~@x@fAbAx@t@nBjBtAlAn@l@b@^HFHHb@f@hAjBx@nARXVZNNl@f@|ApA~BpBtAdAf@f@\\Z\\\\vAnAZXn@h@VT^\\ZXxArA~DlDpBhB|AfAp@h@dAv@~@r@f@`@\\Z^XxApAlAbApChCrBfBHFxDbDr@h@l@`@tA`A^X\\V|AjAd@\\vCtBdAt@XR"
                     },
                     "start_location" : {
                        "lat" : 45.5256861,
                        "lng" : -73.5454857
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,7 km",
                        "value" : 657
                     },
                     "duration" : {
                        "text" : "3 minutes",
                        "value" : 173
                     },
                     "end_location" : {
                        "lat" : 45.4980885,
                        "lng" : -73.5710326
                     },
                     "html_instructions" : "Continuer tout droit sur \u003cb\u003eBoulevard René-Lévesque O S\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "eivtGtm_`M`B~@RPt@p@f@d@TRb@^pAjAj@f@fA`Ad@b@pAlA~AxAj@f@v@t@bA`ANL~BxB"
                     },
                     "start_location" : {
                        "lat" : 45.5030704,
                        "lng" : -73.5665077
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 166
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 58
                     },
                     "end_location" : {
                        "lat" : 45.4972293,
                        "lng" : -73.56928649999999
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà gauche\u003c/b\u003e sur \u003cb\u003eRue Stanley\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eCertaines parties de cette route sont fermées entre 06:00 – 22:00\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ajutG|i``MLWpAgDRi@v@qB"
                     },
                     "start_location" : {
                        "lat" : 45.4980885,
                        "lng" : -73.5710326
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "91 m",
                        "value" : 91
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 45.4965906,
                        "lng" : -73.570025
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà droite\u003c/b\u003e sur \u003cb\u003eAv. des Canadiens-de-Montréal\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "udutG`_``M\\`@Z`@d@f@^d@"
                     },
                     "start_location" : {
                        "lat" : 45.4972293,
                        "lng" : -73.56928649999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,1 km",
                        "value" : 144
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 45.4973214,
                        "lng" : -73.5715453
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà droite\u003c/b\u003e sur \u003cb\u003eRue Drummond\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "u`utGrc``Mg@tAUj@sAnD"
                     },
                     "start_location" : {
                        "lat" : 45.4965906,
                        "lng" : -73.570025
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2,2 km",
                        "value" : 2229
                     },
                     "duration" : {
                        "text" : "9 minutes",
                        "value" : 547
                     },
                     "end_location" : {
                        "lat" : 45.5143844,
                        "lng" : -73.55658939999999
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà droite\u003c/b\u003e sur \u003cb\u003eBoulevard René-Lévesque O\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBd René-Lévesque E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinuer de suivre Bd René-Lévesque E\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "geutGdm``Ms@o@wAoAkAgAq@o@QQKK}@y@a@_@IIsCkCuBoBiAaA{CqCWUmBgBKMa@UQMm@[UOi@]SOe@]e@a@oA}@c@[}AkA_As@s@e@q@e@uAaAkAaAy@w@e@]ACeCyBsCiCmA_A{AqAe@a@_@Y{AqAwB}Ag@]w@k@qB_BaEuDy@}@gA_Ai@g@s@m@EEQQwAiA"
                     },
                     "start_location" : {
                        "lat" : 45.4973214,
                        "lng" : -73.5715453
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,9 km",
                        "value" : 939
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 143
                     },
                     "end_location" : {
                        "lat" : 45.521317,
                        "lng" : -73.5497616
                     },
                     "html_instructions" : "Continuer tout droit pour rester sur \u003cb\u003eBd René-Lévesque E\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "{oxtGto}_Mk@g@{AqAyAqAwAmA{AqAYWUUUWOQ]e@_@i@OU_@o@c@s@GGQUy@y@MMyAsAi@e@m@m@cAaAaCuBgC}BuAoAUQ_@a@"
                     },
                     "start_location" : {
                        "lat" : 45.5143844,
                        "lng" : -73.55658939999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2,5 km",
                        "value" : 2456
                     },
                     "duration" : {
                        "text" : "4 minutes",
                        "value" : 240
                     },
                     "end_location" : {
                        "lat" : 45.5207664,
                        "lng" : -73.5358197
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà gauche\u003c/b\u003e sur \u003cb\u003eAv. Papineau\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eQC-134\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinuer de suivre QC-134\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g{ytG~d|_MOQQb@A^mBdFkBnFk@|Aq@jBe@tAcCvGEN{@`Co@~@EDGDEBGBSHI@E@E?A?E?EAE?EAIAEEo@YSOKGGGKKIIEGEIEICIAKAKCUAuA?E?I?S@Q@S@S?ABUBQ\\yADKDIDO@CBMDM?A?CFUFWp@_EBMRsAJo@Ho@@?BQBQ@K@A?A@IBK@KFODOFO@ERi@Ri@Rk@Ri@Rk@f@uAPg@`@gAFOPi@Rk@Rk@DO`@cARk@JYDM@A?CHUDQDQDSFWBS@I@CBWBU?CD]@OFu@Fq@RwC@KDe@Fm@Fi@@K?AHk@?AFm@?CNwAJ}@b@aE@CFm@?CFm@?CZcDRcBFo@RcBHq@Fg@?GHq@Hq@ZsCHq@D_@Fe@BID]@IHo@DSDe@Ba@"
                     },
                     "start_location" : {
                        "lat" : 45.521317,
                        "lng" : -73.5497616
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 199
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.5193741,
                        "lng" : -73.5347474
                     },
                     "html_instructions" : "Prendre la sortie en direction de \u003cb\u003eParc Jean-Drapeau\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ywytGzmy_MDODKDYB]@[@E?E@CBGBEBG`@EjCg@b@KLANC"
                     },
                     "start_location" : {
                        "lat" : 45.5207664,
                        "lng" : -73.5358197
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 165
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 45.519566,
                        "lng" : -73.53297599999999
                     },
                     "html_instructions" : "Continuer tout droit sur \u003cb\u003eChem. du Tour de l'isle\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "aoytGdgy_M@AFCDAJMDKFO?E@GAI?IAGCGCGCGCGIQKSUa@I[CMAMACAQAOA_@B_@"
                     },
                     "start_location" : {
                        "lat" : 45.5193741,
                        "lng" : -73.5347474
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 184
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 35
                     },
                     "end_location" : {
                        "lat" : 45.5210139,
                        "lng" : -73.53340059999999
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà gauche\u003c/b\u003e sur \u003cb\u003eCh de la Ronde\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ipytGb|x_M?IAEAEAECCACCEECE?KAK?I?OBODGHKJKJQRIFOPKFA@GBGDK@E@E@WDQBKBI@"
                     },
                     "start_location" : {
                        "lat" : 45.519566,
                        "lng" : -73.53297599999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,5 km",
                        "value" : 519
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 45.5203113,
                        "lng" : -73.533993
                     },
                     "html_instructions" : "Tourner à \u003cb\u003egauche\u003c/b\u003e pour continuer sur \u003cb\u003eCh de la Ronde\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iyytGv~x_M?TCXCTEPGPS^IRKVIVI^Id@E^Ad@Af@?@?t@?XBR?BBTBRFLLLFDFBFBLBB@VDJ?VALCPIPMLMHK@CP[BEFMHQHUBMBK?G@E?K?WAYA_@ASCq@QuB"
                     },
                     "start_location" : {
                        "lat" : 45.5210139,
                        "lng" : -73.53340059999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2,7 km",
                        "value" : 2691
                     },
                     "duration" : {
                        "text" : "5 minutes",
                        "value" : 272
                     },
                     "end_location" : {
                        "lat" : 45.5307481,
                        "lng" : -73.56303579999999
                     },
                     "html_instructions" : "Tourner à \u003cb\u003egauche\u003c/b\u003e pour rejoindre \u003cb\u003ePont Jacques-Cartier\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eQC-134 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinuer de suivre QC-134 E\u003c/div\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "}tytGlby_ME@A?a@BA?K@O@E@C?IBSFE@QNEHCBKLADELGVCTALA@@`@?@@L@JBJBH?@DHHNFHZx@Jf@BL?@?@?NA^ERIn@AHE\\CHGd@E^Ip@[rCIp@Ip@?FGf@Ip@SbBGn@SbB[bD?BGl@?BGl@ABc@`EK|@OvA?BGl@?@Ij@?@AJGh@Gl@Ed@AJSvCGp@Gt@ANE\\?BCTCVABAHCRGVEREPEPIT?BA@ELKXSj@a@bAENSj@Sj@Qh@GNa@fAQf@g@tASj@Sh@Sj@Sh@Sh@ADGNENGNAJCJAH?@A@AJCPCPA?In@Kn@SrACLq@~DGVGT?B?@ELCLABENEHEJ]xAMPINKLABEFEFGJMLEDEBEBIBIDG@q@Lo@JKBC@KDKDMJMLGJMXKZ{@~BABQf@g@pAYz@MZQPoAfDwA|DoAnDUp@g@jAyB|FMZQj@Sh@a@lA"
                     },
                     "start_location" : {
                        "lat" : 45.5203113,
                        "lng" : -73.533993
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5,2 km",
                        "value" : 5156
                     },
                     "duration" : {
                        "text" : "14 minutes",
                        "value" : 836
                     },
                     "end_location" : {
                        "lat" : 45.55628919999999,
                        "lng" : -73.61819439999999
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eAv. De Lorimier\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ev{tG~w~_Mq@jBIRiA~CkA|CsApDc@fAm@bBSj@KZgAvCgA|CsBvFwEdM]|@]`A{AdEGN_DvIiCdHIVw@xBc@lAg@tAyFzOQPIPe@lAc@fAYx@g@rASh@ELM\\?@mCpHsBzFQj@EJQf@AXeBxEaBdEMX[r@wCfIc@jAoAjDSj@Sh@aCvG[|@Sj@[v@qGjQoAhDg@tA{AjEcB`F}GpRAB[`AuBlGaB~E}ApEoBtFmC`Iy@fCUt@]~@sA|D}@fCiBtFc@tAoAlDYXIZw@pCIRIPGLEFMLEDQP"
                     },
                     "start_location" : {
                        "lat" : 45.5307481,
                        "lng" : -73.56303579999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,3 km",
                        "value" : 311
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 45.5550659,
                        "lng" : -73.6217039
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà gauche\u003c/b\u003e sur \u003cb\u003eBoul Crémazie E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yu`uGtpi`MLXJVRj@Tt@`@hAPf@HVDNTj@L`@HXRn@Tv@BJ@JDTBh@@P@X?Z?^"
                     },
                     "start_location" : {
                        "lat" : 45.55628919999999,
                        "lng" : -73.61819439999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,9 km",
                        "value" : 891
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 135
                     },
                     "end_location" : {
                        "lat" : 45.5505106,
                        "lng" : -73.63066289999999
                     },
                     "html_instructions" : "Au rond-point, prendre la \u003cb\u003e2e\u003c/b\u003e sortie et continuer sur \u003cb\u003eBoul Crémazie E\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "en`uGrfj`M?xA@PBNBPBLDJBHDFDHDDDFVRP@J?F?\\JJDJHLRHLx@lBFPp@vAHRHPp@xAn@vA|@pBTd@^x@f@bABHDJHNvAbDVj@HPP`@j@vAb@jATz@@DHZH\\F\\BRN`ATtA"
                     },
                     "start_location" : {
                        "lat" : 45.5550659,
                        "lng" : -73.6217039
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1,4 km",
                        "value" : 1420
                     },
                     "duration" : {
                        "text" : "3 minutes",
                        "value" : 206
                     },
                     "end_location" : {
                        "lat" : 45.541375,
                        "lng" : -73.6420655
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour rester sur \u003cb\u003eBoul Crémazie E\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "uq_uGr~k`MPrBXrDJdAD\\Ff@J~@VpAPx@HXJb@L^HVDLHVL^N\\Xp@P\\j@~@R\\BDDHl@~@~@jAvAnAPNLJ^\\pBbBzAlA~AlAdBtAPPRLh@d@z@v@JH|@t@VPZTtAbALHXRfAl@LHNH^Tv@d@HD\\RXNPHtAx@jAp@"
                     },
                     "start_location" : {
                        "lat" : 45.5505106,
                        "lng" : -73.63066289999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,1 km",
                        "value" : 133
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 45.54029190000001,
                        "lng" : -73.64278259999999
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eBd Crémazie O\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qx}tG|en`MTLXNXP^RVPj@\\h@X"
                     },
                     "start_location" : {
                        "lat" : 45.541375,
                        "lng" : -73.6420655
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,4 km",
                        "value" : 384
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 45.5371331,
                        "lng" : -73.6447551
                     },
                     "html_instructions" : "Continuer tout droit pour rester sur \u003cb\u003eBd Crémazie O\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "yq}tGjjn`M\\Tj@`@FDXPz@`@t@d@~BrAr@^x@^lBdA|@X"
                     },
                     "start_location" : {
                        "lat" : 45.54029190000001,
                        "lng" : -73.64278259999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,4 km",
                        "value" : 441
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 29
                     },
                     "end_location" : {
                        "lat" : 45.53353310000001,
                        "lng" : -73.64712949999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela gauche\u003c/b\u003e pour rester sur \u003cb\u003eBd Crémazie O\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "a~|tGvvn`Mt@VTJZNf@XbEbCNHHDh@ZTNJHxCdBd@VB@VRZRJHPN"
                     },
                     "start_location" : {
                        "lat" : 45.5371331,
                        "lng" : -73.6447551
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,6 km",
                        "value" : 597
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 45.5289589,
                        "lng" : -73.65103839999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour rester sur \u003cb\u003eBd Crémazie O\u003c/b\u003e, suivre les indications pour \u003cb\u003eBoulevard de L'acadie\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "qg|tGpeo`MZV\\Vz@n@B@l@ZRJp@`@XNFDPJd@Xn@p@JJZ\\RP\\Z@@JJNJ?@NJLH@?NHn@X@@RHPJZRTNRPLHDDDDNNJJDFDF`@t@b@`@jA|A"
                     },
                     "start_location" : {
                        "lat" : 45.53353310000001,
                        "lng" : -73.64712949999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,3 km",
                        "value" : 315
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 45.52713319999999,
                        "lng" : -73.6538348
                     },
                     "html_instructions" : "Continuer tout droit pour rester sur \u003cb\u003eBd Crémazie O\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "_k{tG~}o`MLPDHRj@FRJ`@T`AT~@ZdBFVBH@@N^DFDDDDPN`@TFDb@RTLJFPHB?FBXJ"
                     },
                     "start_location" : {
                        "lat" : 45.5289589,
                        "lng" : -73.65103839999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,6 km",
                        "value" : 566
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 45.52228900000001,
                        "lng" : -73.65384899999999
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eChem. de la Côte-de-Liesse\u003c/b\u003e",
                     "polyline" : {
                        "points" : "q_{tGlop`MDBNBL?PCLCLETMFCLIHGZQBClAq@TMf@WZMPG`@IPED?JAPARAP?R@PBXDZH~Bt@zAf@h@PnAb@t@\\"
                     },
                     "start_location" : {
                        "lat" : 45.52713319999999,
                        "lng" : -73.6538348
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1,8 km",
                        "value" : 1836
                     },
                     "duration" : {
                        "text" : "3 minutes",
                        "value" : 155
                     },
                     "end_location" : {
                        "lat" : 45.5073015,
                        "lng" : -73.6636979
                     },
                     "html_instructions" : "Garder \u003cb\u003ela gauche\u003c/b\u003e pour rester sur \u003cb\u003eChem. de la Côte-de-Liesse\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "iaztGpop`MFD~@d@ZNj@ZFBxAr@v@\\xBnARJ^Rd@VJFJFHDl@^z@h@FDbCpA^TD@ZR^TVNnAz@bAx@VNpAt@vBpApAr@vBpAJF`Bz@|A~@j@ZtAv@FDdAl@vAt@lEdCbAh@dCpAjBdAb@VXP^T^TjAp@\\RDDXP|Ap@JFPJ^Vj@d@\\Z"
                     },
                     "start_location" : {
                        "lat" : 45.52228900000001,
                        "lng" : -73.65384899999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 165
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 45.5060717,
                        "lng" : -73.6648847
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eChemin de la Côte-de-Liesse\u003c/b\u003e",
                     "polyline" : {
                        "points" : "scwtGbmr`Mz@v@r@f@l@p@vAxA"
                     },
                     "start_location" : {
                        "lat" : 45.5073015,
                        "lng" : -73.6636979
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,8 km",
                        "value" : 810
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 68
                     },
                     "end_location" : {
                        "lat" : 45.5001269,
                        "lng" : -73.67061319999999
                     },
                     "html_instructions" : "Tourner légèrement à \u003cb\u003egauche\u003c/b\u003e pour continuer sur \u003cb\u003eChemin de la Côte-de-Liesse\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "}{vtGntr`Mj@ZTR`@`@NNZ\\JPDFPTX`@JNHJPPLNh@n@Zd@d@v@\\f@PT@@TV\\XZRHDRJ\\Nj@Lf@LB@l@Nf@PPH^RXR\\Vj@p@v@|@DFTX|@lA~ChE"
                     },
                     "start_location" : {
                        "lat" : 45.5060717,
                        "lng" : -73.6648847
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,7 km",
                        "value" : 737
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 45.495901,
                        "lng" : -73.67757130000001
                     },
                     "html_instructions" : "Prendre la bretelle d’accès à \u003cb\u003egauche\u003c/b\u003e vers \u003cb\u003eAéroport de P.-E.-Trudeau\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAutoroute 40 O\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAutoroute 520\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBoul. Cavendish\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "yvutGhxs`Md@b@RXn@x@vDhF`@h@RXX`@T\\\\d@JNLPBBJPb@n@^d@z@fAJNJN@BT\\Vb@BFVd@Tf@LXLZPd@Lb@Rj@Lf@DTFZ@HBTDZ@TB^DxA"
                     },
                     "start_location" : {
                        "lat" : 45.5001269,
                        "lng" : -73.67061319999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "86 m",
                        "value" : 86
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 45.4956058,
                        "lng" : -73.6785811
                     },
                     "html_instructions" : "Suivre \u003cb\u003eChem. de la Côte-de-Liesse\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "k|ttGxcu`MFf@Lv@DTDRHXHXBJ"
                     },
                     "start_location" : {
                        "lat" : 45.495901,
                        "lng" : -73.67757130000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4,0 km",
                        "value" : 3978
                     },
                     "duration" : {
                        "text" : "4 minutes",
                        "value" : 238
                     },
                     "end_location" : {
                        "lat" : 45.49014529999999,
                        "lng" : -73.7278551
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour continuer sur \u003cb\u003eRte Transcanadienne\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "qzttGbju`MFNDRHZFV?DBPF`@D\\B\\@^HzCHvDBjABrA?jB?pBBtA?NFbDBr@FdDBfA?LB`B@xCDpB@TBpADfAVbELxBLjARnBJjAZ~BVbBLn@\\pA`@zBZrA~@lEtA~G@D@HPx@p@lC^|APz@Lx@\\bBBDP|@Jf@z@zDrAbG~@fEJb@Px@@FtAnGVjA`@pBT`ANv@Hd@h@tD@FRtALtAB^RxCFhAFbB@^DxB?xA@J?fECtBAP?RGpCCrAGxCElBE|@UrFAZENGhDCv@OpDQ`IStIEnAKrEM|F]tI"
                     },
                     "start_location" : {
                        "lat" : 45.4956058,
                        "lng" : -73.6785811
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1,4 km",
                        "value" : 1372
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 45.4910435,
                        "lng" : -73.7453469
                     },
                     "html_instructions" : "Garder \u003cb\u003ela gauche\u003c/b\u003e pour continuer sur \u003cb\u003eRte Transcanadienne\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoie de Service N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "mxstGb~~`M@^ALATC^E\\CVC`@K|@UpBEb@Ip@Eb@CjAA~@?LAhA?X?@BdB?JBlBBxCB|D?^?z@AvA?z@CrAG|CCj@[vKWxLCzAKtDMjG?\\A^ChB?BC`B"
                     },
                     "start_location" : {
                        "lat" : 45.49014529999999,
                        "lng" : -73.7278551
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2,0 km",
                        "value" : 1956
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 108
                     },
                     "end_location" : {
                        "lat" : 45.4896995,
                        "lng" : -73.7703422
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour continuer sur \u003cb\u003eRte Transcanadienne\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "_~stGlkbaMEvAAz@AfB?N@tEDtFHpDHvELhD@LBrABv@VtKBlAP~GBxAHhAJ~CBzCPnFFfBZ~K?@BxABhBDrDHvCFxC@??@VtK?@DvABp@BZR~EBv@"
                     },
                     "start_location" : {
                        "lat" : 45.4910435,
                        "lng" : -73.7453469
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1,8 km",
                        "value" : 1757
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 114
                     },
                     "end_location" : {
                        "lat" : 45.482055,
                        "lng" : -73.78982169999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour continuer sur \u003cb\u003eRte Transcanadienne\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoie de Service N\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "sustGrggaMRlCLjBRnB@HDf@J`A^rCl@fE`@tBRbAFVR`Ab@jBb@fBL`@Nn@Rn@J`@@B@BJ\\Tt@HVXv@L\\Tp@h@vAnCfHHVvKhYpAfDt@jB\\x@Rf@nBbFnBnFb@hA"
                     },
                     "start_location" : {
                        "lat" : 45.4896995,
                        "lng" : -73.7703422
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,6 km",
                        "value" : 650
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 45.4787198,
                        "lng" : -73.79666349999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela gauche\u003c/b\u003e pour continuer sur \u003cb\u003eVoie de Service N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "{ertGjakaMXr@Zl@Tj@Xr@DJnAzCrB`FPb@Rj@Rh@HNNb@r@jBXt@Xx@b@nA@Dz@~B@Db@hAf@zA"
                     },
                     "start_location" : {
                        "lat" : 45.482055,
                        "lng" : -73.78982169999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 159
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 45.4779281,
                        "lng" : -73.7983674
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eChemin de Service N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_qqtGbllaMRn@Tn@p@nB`AdC"
                     },
                     "start_location" : {
                        "lat" : 45.4787198,
                        "lng" : -73.79666349999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2,4 km",
                        "value" : 2354
                     },
                     "duration" : {
                        "text" : "2 minutes",
                        "value" : 149
                     },
                     "end_location" : {
                        "lat" : 45.4657148,
                        "lng" : -73.8230159
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour rester sur \u003cb\u003eChemin de Service N\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "alqtGxvlaMxBlGpFxNpCjHjDlJhD~IRf@?@h@rAh@rAtCfHfJdUdH~P~A`Ef@nAj@vAv@jBl@xA\\v@hDrIfCfG`AzB"
                     },
                     "start_location" : {
                        "lat" : 45.4779281,
                        "lng" : -73.7983674
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1,0 km",
                        "value" : 960
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 45.4606719,
                        "lng" : -73.83300509999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela gauche\u003c/b\u003e pour rester sur \u003cb\u003eChemin de Service N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "u_otGzpqaMdCdGTh@tAdDRf@Vn@?@FNBDBDLZRd@@BtAbDPb@Th@n@bBl@hBb@bAz@xBh@pAnB|Ed@jA`D`I"
                     },
                     "start_location" : {
                        "lat" : 45.4657148,
                        "lng" : -73.8230159
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,7 km",
                        "value" : 705
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 45.457253,
                        "lng" : -73.84058899999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite\u003c/b\u003e pour rester sur \u003cb\u003eChemin de Service N\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "e`ntGhosaMlCxG`G|NrAlDRj@Vv@Tt@Vx@BJNn@V|@FZTbAXxAH\\"
                     },
                     "start_location" : {
                        "lat" : 45.4606719,
                        "lng" : -73.83300509999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1,2 km",
                        "value" : 1236
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 72
                     },
                     "end_location" : {
                        "lat" : 45.4539483,
                        "lng" : -73.85570849999999
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eVoie de Service N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yjmtGt~taMHb@XdBT|ANjAXzB\\xC@Dx@hGBT~ChUp@lFPxAl@`FX~BBRLdA@PRxAThBBRXpBFd@`AnG"
                     },
                     "start_location" : {
                        "lat" : 45.457253,
                        "lng" : -73.84058899999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2,7 km",
                        "value" : 2670
                     },
                     "duration" : {
                        "text" : "3 minutes",
                        "value" : 157
                     },
                     "end_location" : {
                        "lat" : 45.4406052,
                        "lng" : -73.8841142
                     },
                     "html_instructions" : "Garder \u003cb\u003ela gauche\u003c/b\u003e pour rester sur \u003cb\u003eVoie de Service N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "evltGd}waM\\dBj@lCDTDPDRDPDNz@~CLh@ZjARl@JXbAjC\\z@`AbCpAfDRj@n@bBbGbPt@`BpEnLb@hA`CjGhCtGzFdOfBpEz@|B|@xBj@vA|@|Bd@jAj@xAvAtDdBjEbAnCRf@Vp@dArCf@tA@B@DdBrEfBxE"
                     },
                     "start_location" : {
                        "lat" : 45.4539483,
                        "lng" : -73.85570849999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,3 km",
                        "value" : 276
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 45.43935829999999,
                        "lng" : -73.887176
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eCh Ste-Marie\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ybjtGtn}aMl@lBHZbA`D`@rAz@dCNn@Nn@"
                     },
                     "start_location" : {
                        "lat" : 45.4406052,
                        "lng" : -73.8841142
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,1 km",
                        "value" : 102
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 45.4389249,
                        "lng" : -73.88832189999999
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eAutoroute Transcanadienne\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_{itGza~aM\\pAx@pC"
                     },
                     "start_location" : {
                        "lat" : 45.43935829999999,
                        "lng" : -73.887176
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,2 km",
                        "value" : 225
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 45.4389246,
                        "lng" : -73.89070989999999
                     },
                     "html_instructions" : "Garder \u003cb\u003ela droite \u003c/b\u003e à l'embranchement, puis suivre les panneaux vers \u003cb\u003eCh. Ste-Marie O\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "gxitG~h~aMHr@DVXpAVfANx@Hf@BT?JAHCPIRCDCDGDSLk@b@"
                     },
                     "start_location" : {
                        "lat" : 45.4389249,
                        "lng" : -73.88832189999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0,7 km",
                        "value" : 663
                     },
                     "duration" : {
                        "text" : "1 minute",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 45.436321,
                        "lng" : -73.8983569
                     },
                     "html_instructions" : "Continuer sur \u003cb\u003eCh Ste-Marie\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gxitG|w~aMzAzGn@|Cx@rDvAnFv@tCbClJl@vC"
                     },
                     "start_location" : {
                        "lat" : 45.4389246,
                        "lng" : -73.89070989999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3,5 km",
                        "value" : 3502
                     },
                     "duration" : {
                        "text" : "4 minutes",
                        "value" : 234
                     },
                     "end_location" : {
                        "lat" : 45.4496451,
                        "lng" : -73.93686049999999
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà droite\u003c/b\u003e sur \u003cb\u003eCh de l'Anse à l'Orme\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_hitGvg`bMw@z@OLaA`A_ArBa@zBWrCC|AE|@CfFYnHO`BKdAe@xBgAhFMl@{AxDOTmAfBiAdBIH}H`KoHxJ}ArBuApCiKpWiFtMwC`Ho@jCE^[lBSjCqCxy@g@rISjB?BKZELc@rB"
                     },
                     "start_location" : {
                        "lat" : 45.436321,
                        "lng" : -73.8983569
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5,0 km",
                        "value" : 5021
                     },
                     "duration" : {
                        "text" : "8 minutes",
                        "value" : 481
                     },
                     "end_location" : {
                        "lat" : 45.4197367,
                        "lng" : -73.9670302
                     },
                     "html_instructions" : "Tourner \u003cb\u003eà gauche\u003c/b\u003e sur \u003cb\u003eCh Senneville\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eLa destination se trouve à droite\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "i{ktGjxgbM@d@LBd@HpB\\RX`@l@z@~BH^t@|DBRr@rGNlC?J@xC?TSvBCD[lAO|@Ot@GzB@TD|Bb@~DF^h@|C\\dA\\nARb@bAvBl@nAR^Xl@l@nAj@nAVf@LVFNf@rAf@tARh@JVFPPh@Lp@Nn@Lp@@Dd@bC@BJj@?@Ll@Lp@Jj@@B@D\\pA@@VbADT?@Ln@Jl@?@Jn@DV\\lCLr@Rb@HNNVHJl@n@f@l@Z^Z^NPHPN\\BHRj@Lb@ZdAJZPj@BDPb@Vn@~@nBlAlCf@rAb@jB@DF`@H`@JVFNH\\BHx@rBRh@Tf@@BpBrEr@~AFJ`@|@Xn@`@^ZVFDzAnA^XpAbAhAz@rAbAfAz@bAt@\\VzApA^X\\Z\\X^Zd@`@\\@ZELELGtA_@BAfBg@`@MNEvAa@b@MZIf@Kb@EF?n@GfFKH?XAb@AvBEb@?PAPATCz@W`Ae@bBy@l@Yv@[v@QHCTGrAOx@KnDYFAXEbAKnDUj@?\\C`@HLDv@V`A`@@@`@JRBn@D`@CXCZA\\E`@E^CTEVKPK^STQX]n@_Ab@}@@C"
                     },
                     "start_location" : {
                        "lat" : 45.4496451,
                        "lng" : -73.93686049999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 45.4966078,
                        "lng" : -73.5700045
                     },
                     "step_index" : 8,
                     "step_interpolation" : 0.9727095475319912
                  },
                  {
                     "location" : {
                        "lat" : 45.5214204,
                        "lng" : -73.53455169999999
                     },
                     "step_index" : 16,
                     "step_interpolation" : 0.1981941811975208
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "mc}uG|kn_M`@EBZSn@V~@b@n@TjAbBvNtC_@|AN`ErAvQbSHbBvCnC`H`Bxy@dOjYbFrOnBjSdCtXjExLXzGAt\\mEzReDfJkCdKgGpIiCtQwI|DO|HrBlNpE|Lt@|MfAtCr@j\\zMlDxBzOrPrb@lf@dHxHrFpDp_@dQjRhGje@|LlL`ChLfAjMRdXmBrPkCzJsCnTgHtJyCxBk@bFUdEjApSlQ|v@dp@`LvIdH`E`EjBfKtCdSbF`M~CbHnFbO`IfK~EjWxNpa@dThF~AtEbCx]dXjDfD~CpBrRxEvMdDxElBhKpDhE`AdDTvBl@xBnAdHdLx]l[fB~AzD|FnM`LnJrIlSrPdUvRbPjLxJ|HrNtMnCfC~A_EjA{Cx@bAdAlA}@`CsAnDs@o@cDwCmCgCuHeHyM_L{WaS}UaSsRsPeOmMcEmFwHaIcLeKu@s@OQQb@oBdGwClIaFhNyBlEk@Ro@CyB}AYgDLaCjDuQhBkGtG{Q~AgNfHop@dAaI|FmA^mA}@oBS}CUm@oAPyArA_BZMvAq@|Ag@bGFfA`@t@jBLzAeB\\sBc@sFgBTu@`AIzBfA|COnCoDx[sEdc@kGfQ{BtHoCzNwAhDmBt@{BbAyDjKoM~\\mJrWya@liAiXxt@mWjs@e[p|@aTtn@_HpSiBfEaAlDa@z@SRCj@vAbEv@zBpAzFLtF|@vAbALn@p@hFnLfG~MdD`JrBtQfBnJnCjGjAlBvDvDbOxLvH`GtPrJrHnE`OfH`TtMfF|C|DpDvFjDfErF|BjJzAdBdChAt@Bx@[~EmCnC]pLhDbShK`IrEjQzKtd@hWdGnDvJxI|HjKxAjAdCv@jBl@bCpBzKnNtItLhDvElCrFhAdFv@rHp@tCn@pRZhWn@nVz@`K~AdJzGt[~N~q@`ChPd@fJFfLe@fU_Bji@cAz]_A|IIhKH`UsBn`Af@vb@z@v^hCbeAzAfX~C`TzC|LtCnIjd@fkArN|_@|]f`Aj^`}@pZ|t@hUlk@`Qdd@lCnMpN~gAlEnXpCjK`p@tcB~Vhp@`J~XrDjP[bB_Ap@jCxLlIf\\l@vCw@z@qAnAaBnF[pFs@vTgCvMkBnEwClEuUxZaZzs@eBdLyDldASnBs@bEr@LdCv@|AlD~@|EfA`MUlHk@jCWpDr@rJxBvI~CtGjFbMrDxPvAnG|@hGv@vAzDhFhCvHlC|FjA~D^`BlFtMvBxE`DlCtOxLzBjBbAb@h@KnEqAlDcAnB[zHU~DGtB_@jGuCjDm@hQsApG`BdFk@`BoAtAaC"
         },
         "summary" : "Rue Notre Dame E",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
