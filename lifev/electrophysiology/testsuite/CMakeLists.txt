INCLUDE(TribitsAddExecutableAndTest)
INCLUDE(AddSubdirectories)

ADD_SUBDIRECTORIES(
	test_0DAlievPanfilovModel
	test_0DHodgkinHuxley
	test_0DFitzHughNagumoModel
	test_0DFoxModel
	test_0DGoldbeterModel
	test_0DLuoRudyIModel
	test_0DMinimalModel
	test_0DMitchellSchaefferModel
	test_0DNoblePurkinje
	test_0DTenTusscher06Model
	test_benchmark 
	test_fibers
	test_pacing
	test_restart
	test_ventricle
)
