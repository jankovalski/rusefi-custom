# Honda-OBD1-comparing-against-current-Honda-OBD1-default

// canned tune https://rusefi.com/online/view.php?msq=1621

```
    // default 1.645
    engineConfiguration->displacement = 1.493;
    // default "12crank/24cam"
    engineConfiguration->trigger.type = TT_TOOTHED_WHEEL;
    // default 0.0
    engineConfiguration->trigger.customTotalToothCount = 24;
    // default "On crankshaft"
    engineConfiguration->skippedWheelOnCam = On camshaft;
    // default 450.0
    engineConfiguration->vvtOffsets[0] = 0;
    // default 248.0
    engineConfiguration->injector.flow = 240;
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
    // default "Lua Gauge 2"
    engineConfiguration->ignBlends[0].yAxisOverride = GPPWM_Zero;
    // default "INVALID"
    engineConfiguration->ignBlends[3].blendParameter = GPPWM_Zero;
    // default "TPS"
    engineConfiguration->ignBlends[3].yAxisOverride = GPPWM_Zero;
    // default "Aux Linear 2"
    engineConfiguration->veBlends[0].blendParameter = GPPWM_Zero;
    // default "TPS"
    engineConfiguration->veBlends[0].yAxisOverride = GPPWM_Zero;
    // default "GPPWM Output 3"
    engineConfiguration->veBlends[1].blendParameter = GPPWM_Zero;
    // default "TPS"
    engineConfiguration->veBlends[1].yAxisOverride = GPPWM_Zero;
    // default "INVALID"
    engineConfiguration->veBlends[2].blendParameter = GPPWM_Zero;
    // default "MAP"
    engineConfiguration->veBlends[2].yAxisOverride = GPPWM_Zero;
    // default "GPPWM Output 1"
    engineConfiguration->veBlends[3].blendParameter = GPPWM_Zero;
    // default "CLT"
    engineConfiguration->veBlends[3].yAxisOverride = GPPWM_Zero;
    // default "VVT 2 E"
    engineConfiguration->boostOpenLoopBlends[0].blendParameter = GPPWM_Zero;
    // default "TPS"
    engineConfiguration->boostOpenLoopBlends[1].blendParameter = GPPWM_Zero;
    // default "TPS"
    engineConfiguration->boostOpenLoopBlends[1].yAxisOverride = GPPWM_Zero;
    // default "Normal"
    engineConfiguration->clutchDownPinInverted = false;
    // default "Normal"
    engineConfiguration->clutchUpPinInverted = false;
    // default "Normal"
    engineConfiguration->flexSensorInverted = false;
    // default 0.0
    engineConfiguration->mapLowValueVoltage = 2.91;
    // default "false"
    engineConfiguration->enableAemXSeries = true;
    // default 92.0
    engineConfiguration->fanOnTemperature = 95;
    // default 88.0
    engineConfiguration->fanOffTemperature = 91;
    // default "false"
    engineConfiguration->enableSoftwareKnock = true;
    // default 500.0
    engineConfiguration->vvtControlMinRpm = 550;
    // default "false"
    engineConfiguration->enableVerboseCanTx = true;
    // default 200.0
    engineConfiguration->rpmSoftLimitWindowSize = 0;
    // default 4.0
    engineConfiguration->rpmSoftLimitTimingRetard = 0;
    // default 1.0
    engineConfiguration->tpsAccelFractionDivisor = 0;
    // default 60.0
    engineConfiguration->gppwm[0].onAboveDuty = 80;
    // default 50.0
    engineConfiguration->gppwm[0].offBelowDuty = 10;


	cannedtpsTpsAccelTable();
	cannedboostTableOpenLoop();
	cannedscriptTable1();
	cannedscriptTable2();
	cannedscriptTable3();
	cannedscriptTable4();
	cannedALSTimingRetardTable();
	cannedALSFuelAdjustment();
	cannedALSIgnSkipTable();
	cannedignitionTable();
	cannedignitionIatCorrTable();
	cannedveTable();
	cannedmapEstimateTable();
	cannedinjectionPhase();
	cannedthrottle2TrimTable();
	cannedmaxKnockRetardTable();
	cannedlambdaTable();
	cannedhpfpCompensation();
```
