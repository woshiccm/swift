target_sources(swiftSILOptimizer PRIVATE
  CapturePromotion.cpp
  CapturePropagation.cpp
  ClosureSpecializer.cpp
  CrossModuleSerializationSetup.cpp
  DeadFunctionElimination.cpp
  EagerSpecializer.cpp
  GlobalOpt.cpp
  GlobalPropertyOpt.cpp
  LetPropertiesOpts.cpp
  UsePrespecialized.cpp)
