# COUPE-BK1-comparing-against-current-COUPE-BK1-default

// canned tune https://rusefi.com/online/view.php?msq=1508

```
    // default "true"
    engineConfiguration->isForcedInduction = false;
    // default -154.0
    engineConfiguration->vvtOffsets[0] = -155;
    // default 335.0
    engineConfiguration->vvtOffsets[1] = 337;
    // default 354.19
    engineConfiguration->injector.flow = 440;
    // default 0.0
    engineConfiguration->cylinderBankSelect[4] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[5] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[6] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[7] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[8] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[9] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[10] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[11] = 1;
    // default "Aux Linear 1"
    engineConfiguration->ignBlends[0].blendParameter = GPPWM_Zero;
    // default "Ignition Load"
    engineConfiguration->ignBlends[3].blendParameter = GPPWM_Zero;
    // default "Aux Linear 1"
    engineConfiguration->veBlends[0].blendParameter = GPPWM_Zero;
    // default "GPPWM Output 3"
    engineConfiguration->veBlends[1].blendParameter = GPPWM_Zero;
    // default "Battery Voltage"
    engineConfiguration->veBlends[2].blendParameter = GPPWM_Zero;
    // default "INVALID"
    engineConfiguration->veBlends[3].blendParameter = GPPWM_Zero;
    // default "VVT 2 E"
    engineConfiguration->boostOpenLoopBlends[0].blendParameter = GPPWM_Zero;
    // default "TPS"
    engineConfiguration->boostOpenLoopBlends[1].blendParameter = GPPWM_Zero;
    // default 98.0
    engineConfiguration->tpsMin = 111;
    // default 926.0
    engineConfiguration->tpsMax = 923;
    // default 891.0
    engineConfiguration->tps1SecondaryMin = 874;
    // default 69.0
    engineConfiguration->tps1SecondaryMax = 63;
    // default "Normal"
    engineConfiguration->clutchDownPinInverted = false;
    // default "Normal"
    engineConfiguration->clutchUpPinInverted = false;
    // default 300.0
    engineConfiguration->idle.solenoidFrequency = 200;
    // default "false"
    engineConfiguration->stepperDcInvertedPins = true;
    // default 15.0
    engineConfiguration->etbIdleThrottleRange = 5;
    // default 15.0
    engineConfiguration->acIdleExtraOffset = 10;
    // default 2.0
    engineConfiguration->fan1ExtraIdle = 0;
    // default 2.0
    engineConfiguration->iacByTpsTaper = 0;
    // default 2.0
    engineConfiguration->iacByTpsHoldTime = 0;
    // default 3.0
    engineConfiguration->iacByTpsDecayTime = 0;
    // default 0.0
    engineConfiguration->idleTimingPid.dFactor = 5.0E-4;
    // default 80.0
    engineConfiguration->fanOnTemperature = 86;
    // default 75.0
    engineConfiguration->fanOffTemperature = 80;
    // default "false"
    engineConfiguration->enableFan1WithAc = true;
    // default 87.0
    engineConfiguration->fan2OnTemperature = 93;
    // default 82.0
    engineConfiguration->fan2OffTemperature = 87;
    // default "false"
    engineConfiguration->enableFan2WithAc = true;
    // default 0.5
    engineConfiguration->acDelay = 0;
    // default 20.0
    engineConfiguration->knockRetardAggression = 0;
    // default 3.0
    engineConfiguration->knockRetardReapplyRate = 0;
    // default 6000.0
    engineConfiguration->vvtActivationDelayMs = 3000;
    // default 0.1
    engineConfiguration->auxPid[0].dFactor = 0.2;
    // default "None"
    engineConfiguration->canNbcType = CAN_BUS_GENESIS_COUPE;
    // default "MAP"
    engineConfiguration->debugMode = DBG_22;
    // default 200.0
    engineConfiguration->rpmSoftLimitWindowSize = 0;
    // default 4.0
    engineConfiguration->rpmSoftLimitTimingRetard = 0;
    // default 250.0
    engineConfiguration->etbRevLimitRange = 0;
    // default 70.0
    engineConfiguration->crankingIACposition = 50;
    // default 100.0
    engineConfiguration->afterCrankingIACtaperDuration = 200;
    // default "true"
    engineConfiguration->overrideCrankingIacSetting = false;
    // default 0.5
    engineConfiguration->primingDelay = 0;
    // default 0.3
    engineConfiguration->tpsAccelLookback = 0;
    // default 12.0
    engineConfiguration->tpsAccelEnrichmentThreshold = 40;
    // default 7.0
    engineConfiguration->tpsDecelEnleanmentThreshold = 0;
    // default 3.0
    engineConfiguration->tpsAccelFractionPeriod = 0;
    // default 3.0
    engineConfiguration->tpsAccelFractionDivisor = 0;
    // default "false"
    engineConfiguration->isBoostControlEnabled = true;
    // default 2000.0
    engineConfiguration->boostControlMinRpm = 0;
    // default 30.0
    engineConfiguration->boostControlMinTps = 0;
    // default 110.0
    engineConfiguration->boostControlMinMap = 0;
    // default "Throttle 2"
    engineConfiguration->etbFunctions[1] = DC_Wastegate;
    // default 8.8944
    engineConfiguration->etb.pFactor = 7.213493;
    // default 70.2307
    engineConfiguration->etb.iFactor = 94.99006;
    // default 0.1855
    engineConfiguration->etb.dFactor = 0.0892407;


	coupleBK1cannedtpsTpsAccelTable();
	coupleBK1cannedboostTableOpenLoop();
	coupleBK1cannedvvtTable1();
	coupleBK1cannedvvtTable2();
	coupleBK1cannedscriptTable1();
	coupleBK1cannedscriptTable2();
	coupleBK1cannedscriptTable3();
	coupleBK1cannedscriptTable4();
	coupleBK1cannedALSTimingRetardTable();
	coupleBK1cannedALSFuelAdjustment();
	coupleBK1cannedALSIgnSkipTable();
	coupleBK1cannedignitionTable();
	coupleBK1cannedignitionIatCorrTable();
	coupleBK1cannedveTable();
	coupleBK1cannedmapEstimateTable();
	coupleBK1cannedinjectionPhase();
	coupleBK1cannedthrottle2TrimTable();
	coupleBK1cannedmaxKnockRetardTable();
	coupleBK1cannedlambdaTable();
	coupleBK1cannedhpfpCompensation();
	coupleBK1cannedpostCrankingFactor();
```
