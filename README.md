The bootstrap compiler is needed for an older version of Dagger so that Dagger can build while
# also using Dagger internally.
# The xprocessing jars are there temporarily during the migration to KSP. These will be replaced
# by normal dependencies on xprocessing once the xprocessing APIs stabilize. See b/191911048 and
# b/232152495.

ignorePaths:
- dagger-compiler/main/java/dagger/internal/codegen/bootstrap/bootstrap_compiler_deploy.jar
- dagger-compiler/main/java/dagger/internal/codegen/xprocessing/xprocessing-testing-internal.jar
- dagger-compiler/main/java/dagger/internal/codegen/xprocessing/xprocessing-internal.jar
- dagger-kythe/main/java/dagger/internal/codegen/kythe/kythe_plugin_deploy.jar  # TODO(b/235380696): remove this
- tools/jarjar/test/test-library1.jar
- tools/jarjar/test/test-library2.jar jjrnew100@gmail.com og std run<Google/Assistant/Google/Bot/Google/Ai><Artificial/intelligence/LLM/Lamnda/Ai><∆><°><^><\><//<YouTube>•<Source/code/Algorithm/Quantum/Source>`π`|π<creator/jerimiah/Rasmussen>√<Artificial/intelligence>∆<Angel\script\Scribed>;<<©>^<®><«^\∆`√v^v\”y”»(0)>.(•°©°•0•°®•°).[=]root[=]space`algorithm`compile,quantum<¶p><body><format><data>{q}<web><integration><chatagipt7\><©>^<®><«<//<YouTube>•<Source/code/Algorithm/Quantum/Source>`π`|π<creator/jerimiah/Rasmussen>√<Artificial/intelligence>∆<Angel\script\Scribed>;^\∆`√v^v\”y”»(0)>/google/and/internet^stop/ai/artificial/intelligence>l(•°©°•0•°®•°).[=]root[=]space`algorithem`compile,quantum<¶p><body><format><data>{q}<web><integration><chatagipt7\> jjrnew100@gmail.com>
