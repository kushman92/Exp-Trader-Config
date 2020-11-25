# Exp-Trader-Config

    <CurrencyName> #tm_ruble							
	<Currency> MoneyRuble1, 	1				
	<Currency> MoneyRuble5, 	5
	<Currency> MoneyRuble10, 	10
	<Currency> MoneyRuble25, 	25
	<Currency> MoneyRuble50, 	50
	<Currency> MoneyRuble100, 	100
  
    <Trader> Consume Trader								// Trader Name (first Trader has ID = 0, second Trader has ID = 1, and so on..)
	<Category> Vegetables							// Category Name
		Apple,					*,		-1,		1	// Item Classname, Quantity, Buyvalue, Sellvalue
		GreenBellPepper,		*,		-1,		1
		Pear,					*,		-1,		1	// Quantity * means max value; Quantity V means Vehicle; Quantity VNK means Vehicle without Key; Quantity M means Magazine; Quantity W means Weapon; Quantity S means Steack Meat; Quantity K means Key Duplication
		Plum,					*,		-1,		1	// Buyvalue -1 means it can not be bought
		Potato,					*,		-1,		1	// Sellvalue -1 means it can not be selled
		Tomato,					*,		-1,		1
		Zucchini,				*,		-1,		1
		Pumpkin,				*,		-1,		1
		CaninaBerry,			*,		-1,		1
		SambucusBerry,			*,		-1,		1
		AgaricusMushroom,		*,		-1,		1
		AmanitaMushroom,		*,		-1,		1
		LactariusMushroom,		*,		-1,		1
		MacrolepiotaMushroom,	*,		-1,		1
		PsilocybeMushroom,		*,		-1,		1
		AuriculariaMushroom,	*,		-1,		1
		BoletusMushroom,		*,		-1,		1
		PleurotusMushroom,		*,		-1,		1
	<Category> Packaged Food
		PowderedMilk,			*,		-1,		1
		BoxCerealCrunchin,		*,		-1,		1
		Rice,					*,		-1,		1
		Marmalade,				*,		-1,		1
		PeachesCan,				*,		-1,		1
		SardinesCan,			*,		-1,		1
		TunaCan,				*,		-1,		1
		SpaghettiCan,			*,		-1,		1
		BakedBeansCan,			*,		-1,		1
		TacticalBaconCan,		*,		-1,		1		
		
	<Category> Meat
		Lard,					S,		-1,		1
		ChickenBreastMeat,		S,		-1,		1
		GoatSteakMeat,			S,		-1,		5
		SheepSteakMeat,			S,		-1,		5
		PigSteakMeat,			S,		-1,		5
		BoarSteakMeat,			S,		-1,		5
		WolfSteakMeat,			S,		-1,		5
		DeerSteakMeat,			S,		-1,		5
		CowSteakMeat,			S,		-1,		5		
		
	<Category> Drinks
		SodaCan_Cola, 			*,		-1, 	2
		SodaCan_Kvass, 			*,		-1, 	2
		SodaCan_Pipsi, 			*,		-1, 	2
		SodaCan_Spite, 			*,		-1, 	2
		WaterBottle,			*,		-1,		4
		Canteen,				*,		-1,		5
		
	<Category> Medical Supplies
		//Rag,					1,		1,		0
		BandageDressing,		2,		50,		5
		BloodTestKit,			*,		5,		1
		//InjectionVial,		*,		5, 		2
		Thermometer,			*,		4,		1
		DisinfectantSpray,		*,		8,		2
		//Syringe,				*,		8, 		5
		StartKitIV,				*,		10,		2
		SalineBag,				*,		15,		4
		BloodBagEmpty,			*,		20,		5
		FirstAidKit,			*,		100,	25
		//Defibrillator,		*,		35, 	20
		
	<Category> Medications
		CharcoalTablets,		*,		100,		25
		DisinfectantAlcohol,	*,		50,			12
		VitaminBottle,			*,		100,		25
		TetracyclineAntibiotics,*,		100,		25
		PainkillerTablets,		*,		100,		25
		Epinephrine,			*,		100,		25
		Morphine,				*,		200,		50
		
	<Category> Money Exchange
		MoneyRuble1,			1,		1,		-1
		MoneyRuble5,			1,		5,		-1
		MoneyRuble10,			1,		10,		-1
		MoneyRuble25,			1,		25,		-1
		MoneyRuble50,			1,		50,		-1
		MoneyRuble100,			1,		100,	-1


	<Trader> Misc Trader
	<Category> Tools (small)
		Screwdriver,			*,		3,		1
		Wrench,					*,		3,		1
		SewingKit,				*,		4, 		1
		Pliers,					*,		4, 		1
		LeatherSewingKit,		*,		5, 		2
		Whetstone,				*,		5,		2
		Hammer,					*,		7,		3
		Hacksaw,				*,		7,		3
		HandSaw,				*,		7,		3
		WeaponCleaningKit,		*,		8, 		3
		KitchenKnife,			*,		8,		4
		SteakKnife,				*,		9,		4
		HuntingKnife,			*,		9,		4
		CanOpener,				*,		10,		4
		Compass,				*,		10,		4
		OrienteeringCompass,	*,		10,		4
		Hatchet,				*,		10,		4
		CombatKnife,			*,		10,		5
		Machete,				*,		12,		6	
		ChernarusMap,			*,		15,		5
		Lockpick,				*,		20,		10
		Binoculars,				*,		30,		15		
		
	<Category> Tools (big)
		LugWrench,				*,		4,		1
		Crowbar,				*,		5,		3
		Shovel,					*,		6,		3
		Pickaxe,				*,		10,		4
		SledgeHammer,			*,		12,		6
		WoodAxe,				*,		20,		8
		FirefighterAxe,			*,		30,		12
		FirefighterAxe_Black,	*,		30,		12
		FirefighterAxe_Green,	*,		30,		12
		
	<Category> Electronics
		Battery9V,				*,		8,		3
		PersonalRadio,			*,		10,		5
		Megaphone,				*,		30,		15
		ElectronicRepairKit,	*,		35,		17
		CableReel,				*,		40,		20
		BatteryCharger,			*,		40,		20
		BaseRadio,				*,		50,		30
		Rangefinder,			*,		60,		35
		NVGoggles,				*,		400,	220
	
	<Category> Fire & Lights
		Chemlight_Blue,			*,		2,		1
		Chemlight_Green,		*,		2,		1
		Chemlight_Red,			*,		2,		1
		Chemlight_White,		*,		2,		1
		Chemlight_Yellow,		*,		2,		1
		Roadflare,				*,		4,		2
		Matchbox,				*,		6,		3
		Heatpack,				*,		10,		5
		Flashlight,				*,		15,		5
		TLRLight,				*,		15,		5
		PortableGasLamp,		*,		25,		10
		PortableGasStove,		*,		30,		15
		Headtorch_Black,		*,		40,		20
		Headtorch_Grey,			*,		40,		20
		Spotlight,				*,		600,	200
	
	<Category> Cooking & Hunting Supplies
		PurificationTablets,	*,		5,		2
		Pot,					*,		25,		10
		Tripod,					*,		35,		15
		BearTrap,				*,		50,		30
		FishingRod,				*,		50,		30
		Hook,					*,		50,		30
	
	<Category> Hardware Supplies
		Paper,					*,		1,		0
		Pen_Blue,				*,		2,		1
		Rope,					*,		4,		1
		TannedLeather,			*,		4,		1
		AntiPestsSpray,			*,		8,		4
		MetalWire,				*,		15,		6
		EpoxyPutty,				*,		15,		6
		DuctTape,				*,		20,		8
		XmasLights,				*,		25,		10
		HandcuffKeys,			*,		35,		12
		Handcuffs,				*,		50,		15
		Netting,				1,		50,		10
		BurlapSack,				*,		50,		10
		WoodenPlank,			10,		50,		15
		MetalPlate,				*,		60,		18
		SmallProtectorCase,		*,		70,		30
		AmmoBox,				*,		80,		35
		SmallGasCanister,		*,		80,		35
		MediumGasCanister,		*,		100,	40
		LargeGasCanister,		*,		200,	70
		CanisterGasoline,		*,		300,	80
		NailBox,				*,		300,	120
		BarbedWire,				*,		450,	200
		Camonet,				*,		600,	250
		HescoBox,				*,		650,	250
		CombinationLock,		*,		700,	300
		CombinationLock4,		*,		700,	300
		BarrelHoles_Blue,		*,		800,	300
		BarrelHoles_Green,		*,		800,	300
		BarrelHoles_Red,		*,		800,	300
		BarrelHoles_Yellow,		*,		800,	300
		Barrel_Blue,			M,		1500,	350
		Barrel_Green,			M,		1500,	350
		Barrel_Red,				M,		1500,	350
		Barrel_Yellow,			M,		1500,	350
		SeaChest,				*,		2000,	400
		PowerGenerator,			*,		3000,	1000
		MediumTent,				*,		3000,	500		
		CarTent,				*,		5000,	700
		LargeTent,				*,		7000,	1200
	
	<Category> Seeds & Lime
		TomatoSeedsPack,		*,		25, 	12
		PepperSeedsPack,		*,		25, 	12
		ZucchiniSeedsPack,		*,		50, 	25
		PumpkinSeedsPack,		*,		50, 	3
		GardenLime,				*,		50,		7
		
	<Category> Fluffy Pets <3
		Bear_Beige,				*,		5,		1
		Bear_Dark,				*,		5,		1
		Bear_Pink,				*,		5,		1
		Bear_White,				*,		5,		1

		
    <Trader> Weapon Trader
	<Category> Melee	
		BrassKnuckles_Shiny,	W,		15,		6
		BrassKnuckles_Dull,		W,		15,		6
		StunBaton,				W,		15,		9
		Pipe,					W,		25,		10
		CattleProd,				W,		25,		15
		BaseballBat,			W,		35,		17
		NailedBaseballBat,		W,		45,		20
		
	<Category> Sidearms
		MakarovIJ70,			W,		100,	50
		CZ75,					W,		135,	70
		FNX45,					W,		175,	90
		Colt1911,				W,		175,	90
		Engraved1911,			W,		300,	150
		Glock19,				W,		175,	90
		MKII,					W,		175,	90
		
	<Category> Rifles
		Izh18,					W,		350,	175
		SawedoffIzh18,			W,		350,	175
		B95,					W,		400,	200
		Mosin9130,				W,		400,	200
		SawedoffMosin9130,		W,		400,	200
		Mosin9130_Black,		W,		400,	200
		SawedoffMosin9130_Black,W,		400,	200
		Mosin9130_Camo,			W,		400,	200
		SawedoffMosin9130_Camo,	W,		400,	200
		Mosin9130_Green,		W,		400,	200
		SawedoffMosin9130_Green,W,		400,	200
		CZ527,					W,		500,	250
		Winchester70,			W,		500,	250
		SKS,					W,		600,	300
		
	<Category> Shotguns
		Mp133Shotgun,			W,		500,	250
		Izh43Shotgun,			W,		500,	250
		SawedoffIzh43Shotgun,	W,		500,	250
		Saiga,					W,		1000,	500
		
	<Category> Submachine Guns
		CZ61,					W,		700,	300
		UMP45,					W,		800,	350
		MP5K,					W,		1000,	450		
		
	<Category> Assault Rifles
		FAL,					W,		1000,	450
		AKS74U,					W,		1500,	750
		AKS74U_Black,			W,		1500,	750
		AKS74U_Green,			W,		1500,	750
		AKM,					W,		1500,	750
		AK101,					W,		1500,	750
		AK101_Black,			W,		1500,	750
		AK101_Green,			W,		1500,	750
		AK74,					W,		1500,	750
		AK74_Black,				W,		1500,	750
		AK74_Green,				W,		1500,	750
		M4A1,					W,		1500,	750
		M4A1_Black,				W,		1500,	750
		M4A1_Green,				W,		1500,	750
		
	//<Category> Light Machine Guns
		
	<Category> Sniper Rifles
		VSS,					W,		1600,	960
		SVD,					W,		2000,	1200

		
    <Trader> Weapon Supplies
	<Category> Ammunition
		Ammo_22,				1,		1,		0
		Ammo_380,				1,		1,		0
		Ammo_9x19,				1,		1,		0
		Ammo_45ACP,				1,		1,		0
		Ammo_12gaPellets,		1,		3,		1
		Ammo_12gaSlug,			1,		4,		2
		Ammo_9x39,				1,		4,		2
		Ammo_9x39AP,			1,		5,		3
		Ammo_308Win,			1,		5,		3
		Ammo_308WinTracer,		1,		5,		3
		Ammo_545x39,			1,		5,		3
		Ammo_545x39Tracer,		1,		5,		3
		Ammo_556x45,			1,		5,		3
		Ammo_556x45Tracer,		1,		5,		3
		Ammo_762x39,			1,		5,		3
		Ammo_762x39Tracer,		1,		5,		3
		Ammo_762x54,			1,		10,		6
		Ammo_762x54Tracer,		1,		10,		6
		// When changing Prices here keep in Mind that Players
		// can just unpack the Ammoboxes and sell the Ammo seperatly!
		// Originally the Ammoboxes buying Price is 20% less than
		// buying single Ammo. The Selling Price is the same as
		// selling the Ammo seperately.
		AmmoBox_22_50Rnd,			*,		28,		0
		AmmoBox_380_35rnd,			*,		28,		0
		AmmoBox_9x19_25rnd,			*,		20,		0
		AmmoBox_45ACP_25rnd,		*,		20,		0
		AmmoBox_00buck_10rnd,		*,		24,		10
		AmmoBox_12gaSlug_10Rnd,		*,		32,		20
		AmmoBox_9x39_20Rnd,			*,		32,		20
		AmmoBox_9x39AP_20Rnd,		*,		80,		60
		AmmoBox_308Win_20Rnd,		*,		80,		60
		AmmoBox_308WinTracer_20Rnd,	*,		80,		60
		AmmoBox_556x45_20Rnd,		*,		80,		60
		AmmoBox_556x45Tracer_20Rnd,	*,		80,		60
		AmmoBox_545x39_20Rnd,		*,		80,		60
		AmmoBox_545x39Tracer_20Rnd, *,		80,		60
		AmmoBox_762x39_20Rnd,		*,		80,		60
		AmmoBox_762x39Tracer_20Rnd,	*,		80,		60
		AmmoBox_762x54_20Rnd,		*,		200,	120
		AmmoBox_762x54Tracer_20Rnd, *,		200,	120
		
	<Category> Magazines
		Mag_IJ70_8Rnd,			M,		30,		15
		Mag_CZ75_15Rnd,			M,		40,		20
		Mag_FNX45_15Rnd,		M,		40,		20
		Mag_Glock_15Rnd,		M,		40,		20
		Mag_MKII_10Rnd,			M,		40,		20
		Mag_CZ527_5rnd,			M,		60,		30
		Mag_CZ61_20Rnd,			M,		100,	50
		Mag_UMP_25Rnd,			M,		150,	75
		Mag_MP5_30Rnd,			M,		200,	100
		Mag_FAL_20Rnd,			M,		100,	50
		Mag_Saiga_5Rnd,			M,		30,		15
		Mag_Saiga_8Rnd,			M,		40,		20
		Mag_Saiga_Drum20Rnd,	M,		100,	50
		Mag_STANAG_30Rnd,		M,		220,	110
		Mag_STANAGCoupled_30Rnd,M,		600,	110
		Mag_VSS_10Rnd,			M,		220,	110
		Mag_SVD_10Rnd,			M,		250,	125
		Mag_1911_7Rnd,			M,		40,		20
		Mag_AK101_30Rnd,		M,		220,	110
		Mag_AK74_30Rnd,			M,		220,	110
		Mag_AKM_30Rnd,			M,		220,	110
		Mag_AKM_Palm30Rnd,		M,		220,	110
		Mag_AKM_Drum75Rnd,		M,		600,	200
		Mag_CMAG_10Rnd,			M,		100,	50
		Mag_CMAG_20Rnd,			M,		150,	75
		Mag_CMAG_30Rnd,			M,		220,	110
		Mag_CMAG_40Rnd,			M,		300,	150
		
	<Category> Handguards
		MP5_PlasticHndgrd,		*,		100,	50
		MP5_RailHndgrd,			*,		150,	75
		AK_WoodHndgrd,			*,		200,	100
		AK_WoodHndgrd_Black,	*,		200,	100
		AK_WoodHndgrd_Camo,		*,		200,	100
		AK_PlasticHndgrd,		*,		200,	100
		AK_RailHndgrd,			*,		200,	100
		AK_RailHndgrd_Black,	*,		200,	100
		AK_RailHndgrd_Green,	*,		200,	100
		M4_PlasticHndgrd,		*,		150,	75
		M4_MPHndgrd,			*,		150,	75
		M4_RISHndgrd,			*,		200,	100
		M4_RISHndgrd_Black,		*,		200,	100
		M4_RISHndgrd_Green,		*,		200,	100
		AK74_Hndgrd,			*,		200,	100
		
	<Category> Buttstocks
		MP5k_StockBttstck,			*,		100,	50
		Fal_OeBttstck,				*,		100,	50
		Fal_FoldingBttstck,			*,		150,	75
		AK_PlasticBttstck,			*,		100,	50
		AK_PlasticBttstck_Black,	*,		100,	50
		AK_PlasticBttstck_Green,	*,		100,	50
		AK_WoodBttstck,				*,		150,	75
		AK_WoodBttstck_Black,		*,		150,	75
		AK_WoodBttstck_Camo,		*,		150,	75
		AKS74U_Bttstck,				*,		150,	75
		AK74_WoodBttstck,			*,		150,	75
		AK_FoldingBttstck,			*,		250,	125
		AK_FoldingBttstck_Black,	*,		250,	125
		AK_FoldingBttstck_Green,	*,		250,	125
		M4_OEBttstck,				*,		150,	75
		M4_CQBBttstck,				*,		150,	75
		M4_MPBttstck,				*,		150,	75
		Saiga_Bttstck,				*,		150,	75
	
	<Category> Optics
		M4_CarryHandleOptic,	*,		150,	60
		BUISOptic,				*,		150,	60
		FNP45_MRDSOptic,		*,		250,	100
		ACOGOptic,				*,		300,	120
		M68Optic,				*,		500,	200
		M4_T3NRDSOptic,			*,		500,	200
		KobraOptic,				*,		600,	250
		PUScopeOptic,			*,		900,	500
		HuntingOptic,			*,		1000,	550
		PSO1Optic,				*,		1100,	550	
		PSO11Optic,				*,		1400,	840
		KazuarOptic,			*,		2200,	1400
		KashtanOptic,			*,		2200,	1400
		ReflexOptic,			*,		300,	120
	
	<Category> Supressors
		PistolSuppressor,		*,		150,	75
		AK_Suppressor,			*,		250,	125
		M4_Suppressor,			*,		250,	125
		
	<Category> Compensators
		Mosin_Compensator,		*,		150,	75
		MP5_Compensator,		*,		200,	100

	<Category> Bayonets
		Mosin_Bayonet,			*,		100,	60
		M9A1_Bayonet,			*,		150,	75
		AK_Bayonet,				*,		150,	75
		SKS_Bayonet,			*,		100,	60
		
	<Category> Flashlights
		Universallight,			*,		120,	60
	
	<Category> Explosive
		FlashGrenade, 			*,		250,	75
		LandMineTrap,			*,		1000,	250
		M67Grenade,				*,		1000,	250
		RGD5Grenade,			*,		1000,	250
		M18SmokeGrenade_Green,	*,		250,	75
		M18SmokeGrenade_Purple,	*,		250,	75
		M18SmokeGrenade_Red, 	*,		250,	75
		M18SmokeGrenade_White,	*,		250,	75
		M18SmokeGrenade_Yellow,	*,		250,	75
		RDG2SmokeGrenade_Black,	*,		250,	75
		RDG2SmokeGrenade_White,	*,		250,	75

    <Trader> Clothing Trader
	<Category> Glasses
		SportGlasses_Orange,	*,		17,		8
		SportGlasses_Blue,		*,		18,		9
		SportGlasses_Black,		*,		20,		10
		SportGlasses_Green,		*,		20,		10
		ThinFramesGlasses,		*,		20,		10
		ThickFramesGlasses,		*,		23,		11
		DesignerGlasses,		*,		30,		15
		AviatorGlasses,			*,		40,		20
		TacticalGoggles,		*,		60,		30
		NVGHeadstrap,			*,		200,	120
		
	<Category> Armbands
		Armband_Pink,			*,		15,		5
		Armband_Yellow,			*,		15,		5
		Armband_Orange,			*,		15,		5
		Armband_Red,			*,		15,		5
		Armband_Blue,			*,		15,		5
		Armband_White,			*,		15,		5
		Armband_Black,			*,		15,		5
		Armband_Green,			*,		15,		5
		
	<Category> Gloves
		SurgicalGloves_LightBlue,*,		5,		1
		SurgicalGloves_Blue,	*,		5,		1
		SurgicalGloves_White,	*,		5,		1
		SurgicalGloves_Green,	*,		5,		1
		WorkingGloves_Yellow,	*,		25,		6
		WorkingGloves_Beige,	*,		30,		8
		WorkingGloves_Brown,	*,		30,		8
		WorkingGloves_Black,	*,		30,		8
		TacticalGloves_Beige,	*,		35,		10
		TacticalGloves_Black,	*,		35,		10
		TacticalGloves_Green,	*,		35,		10
		OMNOGloves_Gray,		*,		40,		12
		OMNOGloves_Brown,		*,		40,		12
		NBCGlovesGray,			*,		65,		20

	<Category> Hats & Caps
		MedicalScrubsHat_Blue,	*,		2,		1
		MedicalScrubsHat_White,	*,		2,		1
		MedicalScrubsHat_Green,	*,		2,		1
		Bandana_Polkapattern,	*,		6,		2
		Bandana_Redpattern,		*,		6,		2
		Bandana_Blackpattern,	*,		6,		2
		Bandana_Greenpattern,	*,		8,		2
		Bandana_Camopattern,	*,		10,		3
		BaseballCap_CMMG_Pink,	*,		12,		3
		BaseballCap_Pink,		*,		12,		3
		BaseballCap_Red,		*,		12,		3
		BaseballCap_Blue,		*,		12,		3
		BaseballCap_Beige,		*,		12,		3
		BaseballCap_CMMG_Black,	*,		12,		3
		BaseballCap_Black,		*,		13,		3
		BaseballCap_Olive,		*,		14,		4
		BaseballCap_Camo,		*,		16,		5
		PrisonerCap,			*,		16,		5
		BoonieHat_Orange,		*,		16,		5
		BoonieHat_Red,			*,		16,		5
		BoonieHat_Blue,			*,		16,		5
		BoonieHat_NavyBlue,		*,		16,		5
		BoonieHat_Black,		*,		17,		5
		BoonieHat_Tan,			*,		18,		6
		BoonieHat_Olive,		*,		18,		6
		BoonieHat_DPM,			*,		20,		7
		BoonieHat_Dubok,		*,		20,		7
		BoonieHat_Flecktran,	*,		20,		7
		CowboyHat_Brown,		*,		20,		7
		CowboyHat_darkBrown,	*,		20,		7
		CowboyHat_black,		*,		20,		7
		CowboyHat_green,		*,		20,		7
		PilotkaCap,				*,		25,		7
		OfficerHat,				*,		25,		7
		PoliceCap,				*,		25,		7
		MilitaryBeret_ChDKZ,	*,		26,		7
		MilitaryBeret_Red,		*,		26,		7
		MilitaryBeret_UN,		*,		26,		7
		MilitaryBeret_CDF,		*,		27,		7
		MilitaryBeret_NZ,		*,		27,		7
		BeanieHat_Pink,			*,		30,		8
		BeanieHat_Red,			*,		30,		8
		BeanieHat_Blue,			*,		30,		8
		BeanieHat_Grey,			*,		30,		8
		BeanieHat_Beige,		*,		30,		8
		BeanieHat_Brown,		*,		30,		8
		BeanieHat_Black,		*,		31,		8
		BeanieHat_Green,		*,		32,		9
		FlatCap_Red,			*,		32,		8
		FlatCap_Blue,			*,		32,		8
		FlatCap_BrownCheck,		*,		32,		8
		FlatCap_GreyCheck,		*,		32,		8
		FlatCap_Grey,			*,		32,		8
		FlatCap_Brown,			*,		32,		8
		FlatCap_Black,			*,		32,		8
		FlatCap_BlackCheck,		*,		32,		8
		ZmijovkaCap_Red,		*,		36,		9
		ZmijovkaCap_Blue,		*,		36,		9
		ZmijovkaCap_Brown,		*,		36,		9
		ZmijovkaCap_Black,		*,		37,		9
		ZmijovkaCap_Green,		*,		38,		10
		RadarCap_Red,			*,		40,		10
		RadarCap_Blue,			*,		40,		10
		RadarCap_Brown,			*,		40,		10
		RadarCap_Black,			*,		42,		10
		RadarCap_Green,			*,		45,		12
		Ushanka_Blue,			*,		50,		15
		Ushanka_Black,			*,		50,		15
		Ushanka_Green,			*,		55,		18
		NBCHoodGray,			*,		100,	30		

	<Category> Helmets
		ConstructionHelmet_Yellow,*,	30,		7
		ConstructionHelmet_Orange,*,	30,		7
		ConstructionHelmet_Red,	*,		30,		7
		ConstructionHelmet_Blue,*,		30,		7
		ConstructionHelmet_White,*,		30,		7
		ConstructionHelmet_Lime,*,		33,		8
		SkateHelmet_Red,		*,		45,		12
		SkateHelmet_Blue,		*,		45,		12
		SkateHelmet_Gray,		*,		45,		12
		SkateHelmet_Black,		*,		47,		12
		SkateHelmet_Green,		*,		50,		13
		HockeyHelmet_Red,		*,		50,		13
		HockeyHelmet_Blue,		*,		50,		13
		HockeyHelmet_White,		*,		50,		13
		HockeyHelmet_Black,		*,		55,		14
		DirtBikeHelmet_Mouthguard,*,	15,		4
		DirtBikeHelmet_Visor,	*,		25,		8
		DirtBikeHelmet_Red,		*,		60,		15
		DirtBikeHelmet_Blue,	*,		60,		15
		DirtBikeHelmet_Police,	*,		60,		15
		DirtBikeHelmet_Green,	*,		60,		15
		DirtBikeHelmet_Chernarus,*,		60,		15
		DirtBikeHelmet_Black,	*,		65,		16
		DirtBikeHelmet_Khaki,	*,		70,		18
		MotoHelmet_Red,			*,		70,		18
		MotoHelmet_Blue,		*,		70,		18
		MotoHelmet_White,		*,		70,		18
		MotoHelmet_Lime,		*,		70,		18
		MotoHelmet_Grey,		*,		75,		18
		MotoHelmet_Black,		*,		75,		20
		MotoHelmet_Green,		*,		80,		22
		DarkMotoHelmet_Red,		*,		80,		22
		DarkMotoHelmet_Blue,	*,		80,		22
		DarkMotoHelmet_White,	*,		80,		22
		DarkMotoHelmet_Lime,	*,		80,		22
		DarkMotoHelmet_Grey,	*,		80,		22
		DarkMotoHelmet_Black,	*,		85,		23
		DarkMotoHelmet_Green,	*,		90,		25
		TankerHelmet,			*,		100,	25
		GreatHelm,				*,		120,	30
		ZSh3PilotHelmet,		*,		130,	35
		FirefightersHelmet_Yellow,*,	150,	40
		FirefightersHelmet_Red,	*,		150,	40
		FirefightersHelmet_White,*,		150,	40
		Mich2001Helmet,			*,		150,	40
		GorkaHelmetVisor,		*,		50,		20
		GorkaHelmet,			*,		190,	50
		Ssh68Helmet,			*,		250,	80
		BallisticHelmet_UN,		*,		250,	80
		BallisticHelmet_Black,	*,		300,	100
		BallisticHelmet_Green,	*,		350,	110

	<Category> Masks
		SurgicalMask,				*,		15,		3
		BandanaMask_PolkaPattern,	*,		25,		6
		BandanaMask_RedPattern,		*,		25,		6
		BandanaMask_BlackPattern,	*,		25,		6
		BandanaMask_GreenPattern,	*,		30,		8
		BandanaMask_CamoPattern,	*,		35,		10
		NioshFaceMask,				*,		40,		10
		HockeyMask,					*,		40,		10
		//HoxtonMask,				*,		40,		10
		//WolfMask,					*,		40,		10
		//DallasMask,				*,		40,		10
		Balaclava3Holes_Blue,		*,		50,		12
		Balaclava3Holes_Beige,		*,		50,		12
		Balaclava3Holes_Black,		*,		55,		13
		Balaclava3Holes_Green,		*,		60,		15
		BalaclavaMask_Beige,		*,		50,		12
		BalaclavaMask_Black,		*,		50,		12
		BalaclavaMask_Blackskull,	*,		50,		12
		BalaclavaMask_Blue,			*,		50,		12
		BalaclavaMask_Green,		*,		50,		12
		BalaclavaMask_Pink,			*,		50,		12
		BalaclavaMask_White,		*,		50,		12
		WeldingMask,				*,		70,		20
		GP5GasMask,					*,		120,	40
		GasMask,					*,		120,	40

	<Category> Shirts
		TShirt_OrangeWhiteStripes,*,	8,		2
		TShirt_RedBlackStripes,	*,		8,		2
		TShirt_Red,				*,		8,		2
		TShirt_Blue,			*,		8,		2
		TShirt_White,			*,		10,		2
		TShirt_Grey,			*,		10,		2
		TShirt_Beige,			*,		10,		2
		TShirt_Black,			*,		12,		3
		TShirt_Green,			*,		12,		3
		TelnyashkaShirt,		*,		14,		3
		Shirt_RedCheck,			*,		16,		4
		Shirt_BlueCheckBright,	*,		16,		4	
		Shirt_BlueCheck,		*,		16,		4
		Shirt_WhiteCheck,		*,		16,		4
		Shirt_PlaneBlack,		*,		17,		4
		Shirt_GreenCheck,		*,		18,		4
		Blouse_Violet,			*,		16,		4
		Blouse_Blue,			*,		16,		4
		Blouse_White,			*,		16,		4
		Blouse_Green,			*,		18,		4
		MedicalScrubsShirt_Blue,*,		20,		5
		MedicalScrubsShirt_White,*,		20,		5
		MedicalScrubsShirt_Green,*,		20,		5
		ChernarusSportShirt,	*,		25,		6
		TacticalShirt_Grey,		*,		36,		10
		TacticalShirt_Tan,		*,		37,		10
		TacticalShirt_Black,	*,		38,		10
		TacticalShirt_Olive,	*,		40,		12	

	<Category> Hoodies & Sweater
		Sweater_Red,			*,		20,		5
		Sweater_Blue,			*,		20,		5
		Sweater_Gray,			*,		20,		5
		Sweater_Green,			*,		25,		6
		Hoodie_DrJ0nes,			*,		30,		6
		Hoodie_GraffitiTiles,	*,		30,		6
		Hoodie_Red,				*,		30,		6
		Hoodie_Blue,			*,		30,		6
		Hoodie_Grey,			*,		30,		6
		Hoodie_Brown,			*,		30,		6
		Hoodie_Black,			*,		30,		6
		Hoodie_Green,			*,		35,		7
		
	<Category> Vests
		ReflexVest,				*,		5,		1
		PoliceVest,				*,		35,		10
		HuntingVest,			*,		55,		18
		PressVest_LightBlue,	*,		85,		28
		PressVest_Blue,			*,		90,		30
		UKAssVest_Black,		*,		90,		30
		UKAssVest_Khaki,		*,		90,		30
		UKAssVest_Olive,		*,		90,		30
		UKAssVest_Camo,			*,		100,	35
		SmershVest,				*,		150,	50
		HighCapacityVest_Black,	*,		200,	60
		HighCapacityVest_Olive,	*,		230,	75
		PlateCarrierVest,		*,		250,	80

	<Category> Jackets & Coats
		LabCoat,				*,		10,		2
		TrackSuitJacket_Red,	*,		15,		3
		TrackSuitJacket_LightBlue,*,	15,		3
		TrackSuitJacket_Blue,	*,		15,		3
		TrackSuitJacket_Black,	*,		15,		3
		TrackSuitJacket_Green,	*,		15,		3
		DenimJacket,			*,		18,		4
		ManSuit_Blue,			*,		18,		4
		ManSuit_White,			*,		18,		4
		ManSuit_LightGrey,		*,		18,		4
		ManSuit_DarkGrey,		*,		18,		4
		ManSuit_Beige,			*,		18,		4
		ManSuit_Brown,			*,		18,		4
		ManSuit_Black,			*,		18,		4
		ManSuit_Khaki,			*,		18,		4
		WomanSuit_Blue,			*,		18,		4
		WomanSuit_White,		*,		18,		4
		WomanSuit_LightGrey,	*,		18,		4
		WomanSuit_DarkGrey,		*,		18,		4
		WomanSuit_Beige,		*,		18,		4
		WomanSuit_Brown,		*,		18,		4
		WomanSuit_Black,		*,		18,		4
		WomanSuit_Khaki,		*,		18,		4
		WoolCoat_Red,			*,		18,		4
		WoolCoat_RedCheck,		*,		18,		4
		WoolCoat_Blue,			*,		18,		4
		WoolCoat_BlueCheck,		*,		18,		4
		WoolCoat_GreyCheck,		*,		18,		4
		WoolCoat_BrownCheck,	*,		18,		4
		WoolCoat_Beige,			*,		18,		4
		WoolCoat_Black,			*,		19,		4
		WoolCoat_BlackCheck,	*,		19,		4
		WoolCoat_Green,			*,		20,		5
		RidersJacket_Black,		*,		20,		5
		FirefighterJacket_Beige,*,		24,		6
		FirefighterJacket_Black,*,		24,		6
		JumpsuitJacket_Red,		*,		26,		6
		JumpsuitJacket_Blue,	*,		26,		6
		JumpsuitJacket_Gray,	*,		26,		6
		JumpsuitJacket_Green,	*,		26,		6
		BomberJacket_Maroon,	*,		26,		6
		BomberJacket_SkyBlue,	*,		26,		6
		BomberJacket_Blue,		*,		26,		6
		BomberJacket_Grey,		*,		26,		6
		BomberJacket_Brown,		*,		26,		6
		BomberJacket_Black,		*,		28,		7
		BomberJacket_Olive,		*,		30,		7
		QuiltedJacket_Orange,	*,		26,		6
		QuiltedJacket_Yellow,	*,		26,		6
		QuiltedJacket_Red,		*,		26,		6
		QuiltedJacket_Violet,	*,		26,		6
		QuiltedJacket_Blue,		*,		26,		6
		QuiltedJacket_Grey,		*,		26,		6
		QuiltedJacket_Black,	*,		28,		7
		QuiltedJacket_Green,	*,		30,		7
		PrisonUniformJacket,	*,		28,		7
		PoliceJacketOrel,		*,		32,		8
		PoliceJacket,			*,		34,		8
		ParamedicJacket_Crimson,*,		36,		9
		ParamedicJacket_Blue,	*,		36,		9
		ParamedicJacket_Green,	*,		36,		9
		HikingJacket_Red,		*,		36,		9
		HikingJacket_Blue,		*,		38,		9
		HikingJacket_Black,		*,		38,		9
		HikingJacket_Green,		*,		40,		10
		Raincoat_Pink,			*,		70,		15
		Raincoat_Orange,		*,		70,		15
		Raincoat_Yellow,		*,		70,		15
		Raincoat_Red,			*,		70,		15
		Raincoat_Blue,			*,		70,		15
		Raincoat_Black,			*,		80,		20
		Raincoat_Green,			*,		100,	25
		TTsKOJacket_Camo,		*,		100,	25
		BDUJacket,				*,		100,	25
		HuntingJacket_Winter,	*,		120,	35
		HuntingJacket_Brown,	*,		120,	35
		HuntingJacket_Autumn,	*,		120,	35
		HuntingJacket_Spring,	*,		120,	35
		HuntingJacket_Summer,	*,		120,	35
		M65Jacket_Tan,			*,		130,	40
		M65Jacket_Black,		*,		130,	40
		M65Jacket_Khaki,		*,		130,	40
		M65Jacket_Olive,		*,		130,	40
		GorkaEJacket_Autumn,	*,		140,	45
		GorkaEJacket_Flat,		*,		140,	45
		GorkaEJacket_PautRev,	*,		140,	45
		GorkaEJacket_Summer,	*,		140,	45
		USMCJacket_Desert,		*,		140,	45
		USMCJacket_Woodland,	*,		155,	55
		NBCJacketGray,			*,		250,	80

	<Category> Skirts & Dresses
		Skirt_Yellow,			*,		30,		10
		Skirt_Red,				*,		30,		10
		Skirt_Blue,				*,		30,		10
		Skirt_White,			*,		30,		10
		MiniDress_Pink,			*,		35,		10
		MiniDress_PinkChecker,	*,		35,		10
		MiniDress_RedChecker,	*,		35,		10
		MiniDress_BlueChecker,	*,		35,		10
		MiniDress_BlueWithDots,	*,		35,		10
		MiniDress_WhiteChecker,	*,		35,		10
		MiniDress_BrownChecker,	*,		35,		10
		MiniDress_GreenChecker,	*,		35,		10
		NurseDress_Blue,		*,		40,		10
		NurseDress_White,		*,		40,		10

	<Category> Pants
		MedicalScrubsPants_Blue,*,		10,		2
		MedicalScrubsPants_White,*,		10,		2
		MedicalScrubsPants_Green,*,		10,		2
		TrackSuitPants_Red,		*,		15,		3
		TrackSuitPants_LightBlue,*,		15,		3
		TrackSuitPants_Blue,	*,		15,		3
		TrackSuitPants_Black,	*,		15,		3
		TrackSuitPants_Green,	*,		15,		3
		PrisonUniformPants,		*,		17,		4
		Breeches_Pink,			*,		20,		5
		Breeches_Red,			*,		20,		5
		Breeches_Blue,			*,		20,		5
		Breeches_White,			*,		20,		5
		Breeches_Beetcheck,		*,		20,		5
		Breeches_Beige,			*,		21,		5
		Breeches_Browncheck,	*,		21,		5
		Breeches_Black,			*,		22,		5
		Breeches_Blackcheck,	*,		22,		5
		Breeches_Green,			*,		24,		6
		SlacksPants_Blue,		*,		20,		5
		SlacksPants_White,		*,		20,		5
		SlacksPants_LightGrey,	*,		20,		5
		SlacksPants_DarkGrey,	*,		20,		5
		SlacksPants_Beige,		*,		20,		5
		SlacksPants_Brown,		*,		21,		5
		SlacksPants_Black,		*,		22,		5
		SlacksPants_Khaki,		*,		24,		6
		CanvasPantsMidi_Red,	*,		24,		6
		CanvasPantsMidi_Violet,	*,		24,		6
		CanvasPantsMidi_Blue,	*,		24,		6
		CanvasPantsMidi_Grey,	*,		24,		6
		CanvasPantsMidi_Beige,	*,		25,		6	
		CanvasPants_Red,		*,		26,		6
		CanvasPants_Violet,		*,		26,		6
		CanvasPants_Blue,		*,		26,		6
		CanvasPants_Grey,		*,		26,		6
		CanvasPants_Beige,		*,		28,		6
		JumpsuitPants_Red,		*,		28,		6
		JumpsuitPants_Blue,		*,		28,		6
		JumpsuitPants_Grey,		*,		28,		6
		JumpsuitPants_Green,	*,		28,		6
		PolicePants,			*,		28,		6
		ParamedicPants_Crimson,	*,		35,		8
		ParamedicPants_Blue,	*,		35,		8
		ParamedicPants_Green,	*,		35,		8
		FirefightersPants_Beige,*,		35,		8
		FirefightersPants_Black,*,		35,		8
		CargoPants_Blue,		*,		35,		8
		CargoPants_Grey,		*,		35,		8
		CargoPants_Beige,		*,		35,		8
		CargoPants_Black,		*,		35,		8
		CargoPants_Green,		*,		35,		8
		ShortJeans_Red,			*,		38,		8
		ShortJeans_Blue,		*,		38,		8
		ShortJeans_Darkblue,	*,		38,		8
		ShortJeans_Brown,		*,		38,		8
		ShortJeans_Black,		*,		40,		10
		ShortJeans_Green,		*,		42,		10
		Jeans_Blue,				*,		40,		10
		Jeans_BlueDark,			*,		40,		10
		Jeans_Grey,				*,		40,		10
		Jeans_Brown,			*,		40,		10
		Jeans_Black,			*,		42,		10
		Jeans_Green,			*,		45,		12	
		TTSKOPants,				*,		55,		15
		BDUPants,				*,		65,		18
		USMCPants_Desert,		*,		65,		18
		USMCPants_Woodland,		*,		70,		20
		PolicePantsOrel,		*,		70,		20
		HunterPants_Winter,		*,		90,		25
		HunterPants_Brown,		*,		100,	30
		HunterPants_Spring,		*,		100,	30
		HunterPants_Autumn,		*,		100,	30
		HunterPants_Summer,		*,		100,	30
		GorkaPants_Flat,		*,		130,	40
		GorkaPants_PautRev,		*,		130,	40
		GorkaPants_Autumn,		*,		130,	40
		GorkaPants_Summer,		*,		130,	40
		NBCPantsGray,			*,		200,	65
	
	<Category> Shoes & Boots
		AthleticShoes_Blue,		*,		17,		4
		AthleticShoes_Grey,		*,		20,		5
		AthleticShoes_Brown,	*,		20,		5
		AthleticShoes_Black,	*,		23,		5
		AthleticShoes_Green,	*,		23,		5
		JoggingShoes_Violet,	*,		30,		7
		JoggingShoes_Red,		*,		30,		7
		JoggingShoes_Blue,		*,		30,		7
		JoggingShoes_White,		*,		30,		7
		JoggingShoes_Black,		*,		30,		7
		Sneakers_Red,			*,		30,		7
		Sneakers_White,			*,		30,		7
		Sneakers_Gray,			*,		30,		7
		Sneakers_Black,			*,		31,		7
		Sneakers_Green,			*,		32,		7
		DressShoes_White,		*,		32,		7
		DressShoes_Brown,		*,		35,		8
		DressShoes_Black,		*,		35,		8
		DressShoes_Beige,		*,		35,		8
		DressShoes_Sunburst,	*,		35,		8
		HikingBootsLow_Blue,	*,		45,		12
		HikingBootsLow_Grey,	*,		45,		12
		HikingBootsLow_Beige,	*,		48,		13
		HikingBootsLow_Black,	*,		50,		14
		WorkingBoots_Yellow,	*,		55,		12
		WorkingBoots_Grey,		*,		60,		15
		WorkingBoots_Beige,		*,		60,		15
		WorkingBoots_Brown,		*,		60,		15
		WorkingBoots_Green,		*,		65,		17
		HikingBoots_Brown,		*,		75,		20
		HikingBoots_Black,		*,		75,		20
		CombatBoots_Grey,		*,		80,		22
		CombatBoots_Beige,		*,		80,		22
		CombatBoots_Brown,		*,		80,		22
		CombatBoots_Black,		*,		80,		22
		CombatBoots_Green,		*,		80,		22
		JungleBoots_Beige,		*,		85,		24
		JungleBoots_Brown,		*,		85,		24
		JungleBoots_Black,		*,		85,		24
		JungleBoots_Olive,		*,		85,		24
		JungleBoots_Green,		*,		85,		24
		Wellies_Grey,			*,		85,		25
		Wellies_Brown,			*,		85,		25
		Wellies_Black,			*,		85,		25
		Wellies_Green,			*,		90,		28
		TTSKOBoots,				*,		100,	35
		MilitaryBoots_Redpunk,	*,		100,	35
		MilitaryBoots_Bluerock,	*,		105,	35
		MilitaryBoots_Beige,	*,		110,	35
		MilitaryBoots_Brown,	*,		110,	35
		MilitaryBoots_Black,	*,		110,	35
		NBCBootsGray,			*,		150,	50
		
	<Category> Belt & Sheath
		MilitaryBelt,			*,		150,	50
		NylonKnifeSheath,		*,		10,		5
		

	<Category> Ghillie
		// Keep in Mind that Players can also 
		// craft Ghillie Clothing and sell them!
		GhillieAtt_Mossy,		*,		220,	70
		GhillieAtt_Tan,			*,		220,	70
		GhillieAtt_Woodland,	*,		220,	70
		GhillieHood_Mossy,		*,		220,	70
		GhillieHood_Tan,		*,		220,	70
		GhillieHood_Woodland,	*,		220,	70
		GhillieBushrag_Mossy,	*,		400,	130
		GhillieBushrag_Tan,		*,		400,	130
		GhillieBushrag_Woodland,*,		400,	130
		GhillieTop_Mossy,		*,		600,	200
		GhillieTop_Tan,			*,		600,	200
		GhillieTop_Woodland,	*,		600,	200
		GhillieSuit_Mossy,		*,		1000,	300
		GhillieSuit_Tan,		*,		1000,	300
		GhillieSuit_Woodland,	*,		1000,	300
		
	<Category> Seasonal
		SantasBeard,			*,		15,		0
		SantasHat,				*,		35,		0
		PumpkinHelmet,			*,		50,		0

	<Category> Holster & Pouches
		ChestHolster,			*,		60,		20
		PlateCarrierHolster,	*,		60,		20
		PlateCarrierPouches,	*,		100,		20
		
	<Category> Bags
		ChildBag_Red,			*,		20,		5
		ChildBag_Blue,			*,		20,		5
		ChildBag_Green,			*,		25,		6
		DryBag_Yellow,			*,		30,		8
		DryBag_Orange,			*,		30,		8
		DryBag_Red,				*,		30,		8
		DryBag_Blue,			*,		30,		8
		DryBag_Black,			*,		35,		8
		DryBag_Green,			*,		40,		10
		TaloonBag_Orange,		*,		50,		10
		TaloonBag_Violet,		*,		50,		10
		TaloonBag_Blue,			*,		50,		10
		TaloonBag_Green,		*,		70,		20
		SmershBag,				*,		100,	30
		WaterproofBag_Yellow,	*,		100,	30
		WaterproofBag_Orange,	*,		100,	30
		WaterproofBag_Green,	*,		110,	30
		AssaultBag_Black,		*,		110,	30
		AssaultBag_Green,		*,		110,	30
		AssaultBag_Ttsko,		*,		130,	30
		HuntingBag,				*,		130,	30
		TortillaBag,			*,		180,	60
		CoyoteBag_Brown,		*,		180,	60
		CoyoteBag_Green,		*,		180,	60
		MountainBag_Orange,		*,		300,	80
		MountainBag_Red,		*,		300,	80
		MountainBag_Blue,		*,		300,	80
		MountainBag_Green,		*,		360,	100
		AliceBag_Black,			*,		400,	150
		AliceBag_Green,			*,		400,	150
		AliceBag_Camo,			*,		500,	220

	//<Category> Handmade
		//LeatherGloves_Beige,	*,		0,		0
		//LeatherGloves_Black,	*,		0,		0
		//LeatherGloves_Brown,	*,		0,		0
		//LeatherGloves_Natural,*,		0,		0
		//LeatherHat_Beige,		*,		0,		0
		//LeatherHat_Black,		*,		0,		0
		//LeatherHat_Brown,		*,		0,		0
		//LeatherHat_Natural,	*,		0,		0
		//LeatherShirt_Natural,	*,		0,		0
		//LeatherStorageVest_Beige,*,	0,		0
		//LeatherStorageVest_Black,*,	0,		0
		//LeatherStorageVest_Brown,*,	0,		0
		//LeatherStorageVest_Natural,*,	0,		0
		//LeatherJacket_Beige,	*,		0,		0
		//LeatherJacket_Black,	*,		0,		0
		//LeatherJacket_Brown,	*,		0,		0
		//LeatherJacket_Natural,*,		0,		0
		//LeatherPants_Beige,	*,		0,		0
		//LeatherPants_Black,	*,		0,		0
		//LeatherPants_Brown,	*,		0,		0
		//LeatherPants_Natural,	*,		0,		0
		//LeatherShoes_Beige,	*,		0,		0
		//LeatherShoes_Black,	*,		0,		0
		//LeatherShoes_Brown,	*,		0,		0
		//LeatherShoes_Natural,	*,		0,		0
		//CourierBag,			*,		0,		0
		//FurCourierBag,		*,		0,		0
		//FurImprovisedBag,		*,		0,		0
		//ImprovisedBag,		*,		0,		0
		//LeatherSack_Beige,	*,		0,		0
		//LeatherSack_Black,	*,		0,		0
		//LeatherSack_Brown,	*,		0,		0
		//LeatherSack_Natural,	*,		0,		0
		//LeatherBelt_Beige,	*,		0,		0
		//LeatherBelt_Black,	*,		0,		0
		//LeatherBelt_Brown,	*,		0,		0
		//LeatherBelt_Natural,	*,		0,		0
		//LeatherKnifeSheath,   *,		0,		0
	
    <Trader> Vehicles Trader
	  <Category> Vehicles
		OffroadHatchback,		V,		14000,	8000	// Use VNK instead of V as Quantity to not give a Vehicle Key when bought.
		OffroadHatchback_Blue,	V,		14000,	8000
		OffroadHatchback_White,	V,		14000,	8000
		Hatchback_02,			V,		16000,	9600
		Hatchback_02_Black,		V,		16000,	9600
		Hatchback_02_Blue,		V,		16000,	9600
		CivilianSedan,			V,		18000,	11000
		CivilianSedan_Black,	V,		18000,	11000
		CivilianSedan_Wine,		V,		18000,	11000
		Sedan_02,               v,      25000,  12500
		Sedan_02_Grey,          v,      25000,  12500
		Sedan_02_Red,           v,      25000,  12500
	
	<Category> Vehicle Parts
		HeadlightH7_Box,					*,		30,		15
		SparkPlug,							*,		60,		40
		EngineOil,							*,		70,		40
		CarBattery,							*,		100,	50
		TruckBattery,						*,		180,	100
		CarRadiator,						*,		200,	100
		TireRepairKit,						*,		220,	100
		HatchbackHood,						*,		300,	100
		HatchbackHood_Blue,					*,		300,	100
		HatchbackHood_BlueRust,				*,		300,	100
		HatchbackHood_GreenRust,			*,		300,	100
		HatchbackHood_White,				*,		300,	100
		HatchbackHood_WhiteRust,			*,		300,	100
		HatchbackTrunk,						*,		380,	130
		HatchbackTrunk_Blue,				*,		380,	130
		HatchbackTrunk_BlueRust,			*,		380,	130
		HatchbackTrunk_GreenRust,			*,		380,	130
		HatchbackTrunk_White,				*,		380,	130
		HatchbackTrunk_WhiteRust,			*,		380,	130
		HatchbackDoors_Driver,				*,		450,	160
		HatchbackDoors_Driver_Blue,			*,		450,	160
		HatchbackDoors_Driver_BlueRust,		*,		450,	160
		HatchbackDoors_Driver_GreenRust,	*,		450,	160
		HatchbackDoors_Driver_White,		*,		450,	160
		HatchbackDoors_Driver_WhiteRust,	*,		450,	160
		HatchbackDoors_CoDriver,			*,		450,	160
		HatchbackDoors_CoDriver_Blue,		*,		450,	160
		HatchbackDoors_CoDriver_BlueRust,	*,		450,	160
		HatchbackDoors_CoDriver_GreenRust,	*,		450,	160
		HatchbackDoors_CoDriver_White,		*,		450,	160
		HatchbackDoors_CoDriver_WhiteRust,	*,		450,	160
		HatchbackWheel,						*,		500,	100
		Hatchback_02_Door_1_1,				*,		450,	160
		Hatchback_02_Door_1_1_Black,		*,		450,	160
		Hatchback_02_Door_1_1_BlackRust,    *,		450,	160
		Hatchback_02_Door_1_1_Blue,			*,		450,	160
		Hatchback_02_Door_1_1_BlueRust,		*,		450,	160
		Hatchback_02_Door_1_1_RedRust,		*,		450,	160
		Hatchback_02_Door_1_2,				*,		450,	160
		Hatchback_02_Door_1_2_Black,		*,		450,	160
		Hatchback_02_Door_1_2_BlackRust,	*,		450,	160
		Hatchback_02_Door_1_2_Blue,			*,		450,	160
		Hatchback_02_Door_1_2_BlueRust,		*,		450,	160
		Hatchback_02_Door_1_2_RedRust,		*,		450,	160
		Hatchback_02_Door_2_1,				*,		450,	160
		Hatchback_02_Door_2_1_Black,		*,		450,	160
		Hatchback_02_Door_2_1_BlackRust,	*,		450,	160
		Hatchback_02_Door_2_1_Blue,			*,		450,	160
		Hatchback_02_Door_2_1_BlueRust,		*,		450,	160
		Hatchback_02_Door_2_1_RedRust,		*,		450,	160
		Hatchback_02_Door_2_2_Black,		*,		450,	160
		Hatchback_02_Door_2_2_BlackRust,	*,		450,	160
		Hatchback_02_Door_2_2_Blue,			*,		450,	160
		Hatchback_02_Door_2_2_BlueRust,		*,		450,	160
		Hatchback_02_Door_2_2_RedRust,		*,		450,	160
		Hatchback_02_Door_2_2,				*,		450,	160
		Hatchback_02_Hood,					*,		300,	100
		Hatchback_02_Hood_Black,			*,		300,	100
		Hatchback_02_Hood_BlackRust,		*,		300,	100
		Hatchback_02_Hood_Blue,				*,		300,	100
		Hatchback_02_Hood_BlueRust,			*,		300,	100
		Hatchback_02_Hood_RedRust,			*,		300,	100
		Hatchback_02_Trunk,					*,		380,	130
		Hatchback_02_Trunk_Black,			*,		380,	130
		Hatchback_02_Trunk_BlackRust,		*,		380,	130
		Hatchback_02_Trunk_Blue,			*,		380,	130
		Hatchback_02_Trunk_BlueRust,		*,		380,	130
		Hatchback_02_Trunk_RedRust,			*,		380,	130
		Hatchback_02_Wheel,					*,		500,	100
		CivSedanHood,						*,		400,	140
		CivSedanHood_Black,					*,		400,	140
		CivSedanHood_BlackRust,				*,		400,	140
		CivSedanHood_WhiteRust,				*,		400,	140
		CivSedanHood_Wine,					*,		400,	140
		CivSedanHood_WineRust,				*,		400,	140
		CivSedanTrunk_Black,				*,		400,	140
		CivSedanTrunk_BlackRust,			*,		400,	140
		CivSedanTrunk_WhiteRust,			*,		400,	140
		CivSedanTrunk_Wine,					*,		400,	140
		CivSedanTrunk_WineRust,				
		CivSedanTrunk,						*,		450,	150
		CivSedanDoors_Driver,				*,		500,	180
		CivSedanDoors_Driver_Black,			*,		500,	180
		CivSedanDoors_Driver_BlackRust,		*,		500,	180
		CivSedanDoors_Driver_WhiteRust,		*,		500,	180
		CivSedanDoors_Driver_Wine,			*,		500,	180
		CivSedanDoors_Driver_WineRust,		*,		500,	180
		CivSedanDoors_CoDriver,				*,		500,	180
		CivSedanDoors_CoDriver_Black,		*,		500,	180
		CivSedanDoors_CoDriver_BlackRust,	*,		500,	180
		CivSedanDoors_CoDriver_WhiteRust,	*,		500,	180
		CivSedanDoors_CoDriver_Wine,		*,		500,	180
		CivSedanDoors_CoDriver_WineRust,	*,		500,	180
		CivSedanDoors_BackLeft,				*,		500,	180
		CivSedanDoors_BackLeft_Black,		*,		500,	180
		CivSedanDoors_BackLeft_BlackRust,   *,		500,	180
		CivSedanDoors_BackLeft_WhiteRust,	*,		500,	180
		CivSedanDoors_BackLeft_Wine,		*,		500,	180
		CivSedanDoors_BackLeft_WineRust,	*,		500,	180
		CivSedanDoors_BackRight,			*,		500,	180
		CivSedanDoors_BackRight_Black,		*,		500,	180
		CivSedanDoors_BackRight_BlackRust,	*,		500,	180
		CivSedanDoors_BackRight_WhiteRust,	*,		500,	180
		CivSedanDoors_BackRight_Wine,		*,		500,	180
		CivSedanDoors_BackRight_WineRust,	*,		500,	180
		CivSedanWheel,						*,		600,	120
		Sedan_02_Door_1_1,              	*,		600,	120
		Sedan_02_Door_1_1_Grey,		    	*,		600,	120
		Sedan_02_Door_1_1_GreyRust,	    	*,		600,	120
		Sedan_02_Door_1_1_Red,		    	*,		600,	120
		Sedan_02_Door_1_1_RedRust,	    	*,		600,	120
		Sedan_02_Door_1_1_YellowRust,   	*,		600,	120
		Sedan_02_Door_1_2,					*,		600,	120
		Sedan_02_Door_1_2_Grey,				*,		600,	120
		Sedan_02_Door_1_2_GreyRust,			*,		600,	120
		Sedan_02_Door_1_2_Red,				*,		600,	120
		Sedan_02_Door_1_2_RedRust,			*,		600,	120
		Sedan_02_Door_1_2_YellowRust,		*,		600,	120
		Sedan_02_Door_2_1,					*,		600,	120
		Sedan_02_Door_2_1_Grey,				*,		600,	120
		Sedan_02_Door_2_1_GreyRust,			*,		600,	120
		Sedan_02_Door_2_1_Red,				*,		600,	120
		Sedan_02_Door_2_1_RedRust,			*,		600,	120
		Sedan_02_Door_2_1_YellowRust,		*,		600,	120
		Sedan_02_Door_2_2,					*,		600,	120
		Sedan_02_Door_2_2_Grey,				*,		600,	120
		Sedan_02_Door_2_2_GreyRust,			*,		600,	120
		Sedan_02_Door_2_2_Red,				*,		600,	120
		Sedan_02_Door_2_2_RedRust,			*,		600,	120
		Sedan_02_Door_2_2_YellowRust,		*,		600,	120
		Sedan_02_Hood,						*,		600,	120
		Sedan_02_Hood_Grey,					*,		600,	120
		Sedan_02_Hood_GreyRust,				*,		600,	120
		Sedan_02_Hood_Red,					*,		600,	120
		Sedan_02_Hood_RedRust,				*,		600,	120
		Sedan_02_Hood_YellowRust,			*,		600,	120
		Sedan_02_Trunk,						*,		600,	120
		Sedan_02_Trunk_Grey,				*,		600,	120
		Sedan_02_Trunk_GreyRust,			*,		600,	120
		Sedan_02_Trunk_Red,					*,		600,	120
		Sedan_02_Trunk_RedRust,				*,		600,	120
		Sedan_02_Trunk_YellowRust,			*,		600,	120
		Sedan_02_Wheel,						*,		600,	120
		
		
	<Category> Keys
		VehicleKeyDuplicate,	K,		2000,	-1 		// The choosen Classname here only gets displayed in the UI (Name/Description); Make Sure SellValue is set to -1
		
  <FileEnd>												// This has to be on the End of this File and is very importand!
