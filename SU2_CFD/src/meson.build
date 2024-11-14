su2_cfd_include = include_directories('./')
su2_cfd_src = files(['definition_structure.cpp',
                     'python_wrapper_structure.cpp',
                     'CMarkerProfileReaderFVM.cpp'])

su2_cfd_src += files(['fluid/CFluidModel.cpp',
                      'fluid/CIdealGas.cpp',
                      'fluid/CFluidScalar.cpp',
                      'fluid/CFluidFlamelet.cpp',
                      'fluid/CPengRobinson.cpp',
                      'fluid/CVanDerWaalsGas.cpp',
                      'fluid/CCoolProp.cpp',
                      'fluid/CNEMOGas.cpp',
                      'fluid/CMutationTCLib.cpp',
                      'fluid/CSU2TCLib.cpp',
                      'fluid/CDataDrivenFluid.cpp'])

su2_cfd_src += files(['output/COutputFactory.cpp',
                      'output/CAdjElasticityOutput.cpp',
                      'output/CAdjFlowOutput.cpp',
                      'output/CAdjFlowCompOutput.cpp',
                      'output/CAdjFlowIncOutput.cpp',
                      'output/CAdjHeatOutput.cpp',
                      'output/CBaselineOutput.cpp',
                      'output/CMultizoneOutput.cpp',
                      'output/CElasticityOutput.cpp',
                      'output/CFlowCompOutput.cpp',
                      'output/CFlowCompFEMOutput.cpp',
                      'output/CFVMOutput.cpp',
                      'output/CFlowOutput.cpp',
                      'output/CFlowIncOutput.cpp',
                      'output/CHeatOutput.cpp',
                      'output/CMeshOutput.cpp',
                      'output/CNEMOCompOutput.cpp',
                      'output/CTurboOutput.cpp' ,
                      'output/COutput.cpp',
                      'output/filewriter/CParallelDataSorter.cpp',
                      'output/filewriter/CFVMDataSorter.cpp',
                      'output/filewriter/CFEMDataSorter.cpp',
                      'output/filewriter/CSurfaceFEMDataSorter.cpp',
                      'output/filewriter/CSurfaceFVMDataSorter.cpp',
                      'output/filewriter/CParallelFileWriter.cpp',
                      'output/filewriter/CParaviewFileWriter.cpp',
                      'output/filewriter/CParaviewBinaryFileWriter.cpp',
                      'output/filewriter/CTecplotFileWriter.cpp',
                      'output/filewriter/CTecplotBinaryFileWriter.cpp',
                      'output/filewriter/CCSVFileWriter.cpp',
                      'output/filewriter/CSTLFileWriter.cpp',
                      'output/filewriter/CSU2FileWriter.cpp',
                      'output/filewriter/CSU2BinaryFileWriter.cpp',
                      'output/filewriter/CParaviewXMLFileWriter.cpp',
                      'output/filewriter/CParaviewVTMFileWriter.cpp',
                      'output/filewriter/CSU2MeshFileWriter.cpp',
                      'output/filewriter/CCGNSFileWriter.cpp',
                      'output/tools/CWindowingTools.cpp'])

su2_cfd_src += files(['variables/CIncNSVariable.cpp',
                      'variables/CTransLMVariable.cpp',
                      'variables/CAdjEulerVariable.cpp',
                      'variables/CHeatVariable.cpp',
                      'variables/CTurbVariable.cpp',
                      'variables/CScalarVariable.cpp',
                      'variables/CSpeciesVariable.cpp',
                      'variables/CSpeciesFlameletVariable.cpp',
                      'variables/CAdjNSVariable.cpp',
                      'variables/CBaselineVariable.cpp',
                      'variables/CDiscAdjFEABoundVariable.cpp',
                      'variables/CDiscAdjMeshBoundVariable.cpp',
                      'variables/CFEABoundVariable.cpp',
                      'variables/CDiscAdjVariable.cpp',
                      'variables/CTurbSAVariable.cpp',
                      'variables/CFEAVariable.cpp',
                      'variables/CMeshVariable.cpp',
                      'variables/CMeshBoundVariable.cpp',
                      'variables/CMeshElement.cpp',
                      'variables/CRadVariable.cpp',
                      'variables/CRadP1Variable.cpp',
                      'variables/CTurbSSTVariable.cpp',
                      'variables/CVariable.cpp',
                      'variables/CNSVariable.cpp',
                      'variables/CAdjTurbVariable.cpp',
                      'variables/CFlowVariable.cpp',
                      'variables/CIncEulerVariable.cpp',
                      'variables/CEulerVariable.cpp',
                      'variables/CNEMOEulerVariable.cpp',
                      'variables/CNEMONSVariable.cpp',
                      'variables/CSobolevSmoothingVariable.cpp'])

su2_cfd_src += files(['solvers/CSolverFactory.cpp',
                      'solvers/CAdjEulerSolver.cpp',
                      'solvers/CAdjNSSolver.cpp',
                      'solvers/CAdjTurbSolver.cpp',
                      'solvers/CBaselineSolver.cpp',
                      'solvers/CBaselineSolver_FEM.cpp',
                      'solvers/CDiscAdjFEASolver.cpp',
                      'solvers/CDiscAdjMeshSolver.cpp',
                      'solvers/CRadSolver.cpp',
                      'solvers/CRadP1Solver.cpp',
                      'solvers/CDiscAdjSolver.cpp',
                      'solvers/CEulerSolver.cpp',
                      'solvers/CFEASolver.cpp',
                      'solvers/CFEM_DG_EulerSolver.cpp',
                      'solvers/CFEM_DG_NSSolver.cpp',
                      'solvers/CHeatSolver.cpp',
                      'solvers/CIncEulerSolver.cpp',
                      'solvers/CIncNSSolver.cpp',
                      'solvers/CMeshSolver.cpp',
                      'solvers/CNEMOEulerSolver.cpp',
                      'solvers/CNEMONSSolver.cpp',
                      'solvers/CNSSolver.cpp',
                      'solvers/CSolver.cpp',
                      'solvers/CTemplateSolver.cpp',
                      'solvers/CSpeciesSolver.cpp',
                      'solvers/CSpeciesFlameletSolver.cpp',
                      'solvers/CTransLMSolver.cpp',
                      'solvers/CTurbSolver.cpp',
                      'solvers/CTurbSASolver.cpp',
                      'solvers/CTurbSSTSolver.cpp',
                      'solvers/CFEASolverBase.cpp',
                      'solvers/CGradientSmoothingSolver.cpp'])

su2_cfd_src += files(['numerics/CNumerics.cpp',
                      'numerics/template.cpp',
                      'numerics/radiation.cpp',
                      'numerics/flow/convection/roe.cpp',
                      'numerics/flow/convection/fds.cpp',
                      'numerics/flow/convection/fvs.cpp',
                      'numerics/flow/convection/hllc.cpp',
                      'numerics/flow/convection/ausm_slau.cpp',
                      'numerics/flow/convection/centered.cpp',
                      'numerics/flow/flow_diffusion.cpp',
                      'numerics/flow/flow_sources.cpp',
                      'numerics/NEMO/CNEMONumerics.cpp',
                      'numerics/NEMO/convection/lax.cpp',
                      'numerics/NEMO/convection/roe.cpp',
                      'numerics/NEMO/convection/ausm_slau.cpp',
                      'numerics/NEMO/convection/msw.cpp',
                      'numerics/NEMO/NEMO_diffusion.cpp',
                      'numerics/NEMO/NEMO_sources.cpp',
                      'numerics/continuous_adjoint/adj_convection.cpp',
                      'numerics/continuous_adjoint/adj_diffusion.cpp',
                      'numerics/continuous_adjoint/adj_sources.cpp',
                      'numerics/scalar/scalar_sources.cpp',
                      'numerics/species/species_sources.cpp',
                      'numerics/elasticity/CFEAElasticity.cpp',
                      'numerics/elasticity/CFEALinearElasticity.cpp',
                      'numerics/elasticity/CFEANonlinearElasticity.cpp',
                      'numerics/elasticity/nonlinear_models.cpp',
                      'numerics/CGradSmoothing.cpp'])

su2_cfd_src += files(['../include/numerics_simd/CNumericsSIMD.cpp'])

su2_cfd_src += files(['interfaces/CInterface.cpp',
                      'interfaces/cfd/CConservativeVarsInterface.cpp',
                      'interfaces/cfd/CMixingPlaneInterface.cpp',
                      'interfaces/cfd/CSlidingInterface.cpp',
                      'interfaces/cht/CConjugateHeatInterface.cpp',
                      'interfaces/fsi/CDisplacementsInterface.cpp',
                      'interfaces/fsi/CFlowTractionInterface.cpp',
                      'interfaces/fsi/CDiscAdjFlowTractionInterface.cpp'])

su2_cfd_src += files(['drivers/CDriver.cpp',
                      'drivers/CMultizoneDriver.cpp',
                      'drivers/CSinglezoneDriver.cpp',
                      'drivers/CDiscAdjMultizoneDriver.cpp',
                      'drivers/CDiscAdjSinglezoneDriver.cpp',
                      'drivers/CDummyDriver.cpp',
                      'drivers/CDriverBase.cpp'])

su2_cfd_src += files(['integration/CIntegration.cpp',
                      'integration/CIntegrationFactory.cpp',
                      'integration/CSingleGridIntegration.cpp',
                      'integration/CMultiGridIntegration.cpp',
                      'integration/CNewtonIntegration.cpp',
                      'integration/CStructuralIntegration.cpp',
                      'integration/CFEM_DG_Integration.cpp'])

su2_cfd_src += files(['iteration/CIteration.cpp',
                      'iteration/CIterationFactory.cpp',
                      'iteration/CAdjFluidIteration.cpp',
                      'iteration/CDiscAdjFluidIteration.cpp',
                      'iteration/CDiscAdjHeatIteration.cpp',
                      'iteration/CDiscAdjFEAIteration.cpp',
                      'iteration/CFEAIteration.cpp',
                      'iteration/CFEMFluidIteration.cpp',
                      'iteration/CFluidIteration.cpp',
                      'iteration/CHeatIteration.cpp',
                      'iteration/CTurboIteration.cpp'])

su2_cfd_src += files(['limiters/CLimiterDetails.cpp'])

profiling_args = []
if get_option('enable-gprof')
  profiling_args = ['-pg','-no-pie']
endif

if get_option('enable-normal')
  su2_cfd_lib = static_library('SU2core',
                               su2_cfd_src,
                               install : false,
		               dependencies : [su2_deps, common_dep],
		               cpp_args:  [default_warning_flags, su2_cpp_args])
  su2_cfd_dep = declare_dependency(link_with: su2_cfd_lib,
                                   include_directories: su2_cfd_include)
  su2_cfd = executable('SU2_CFD',
                       'SU2_CFD.cpp',
                       install : true,
                       dependencies : [su2_cfd_dep, su2_deps, common_dep],
                       cpp_args:  ['-fPIC'] + [default_warning_flags, su2_cpp_args] + profiling_args,
                       link_args: profiling_args)
endif

if get_option('enable-autodiff')
  su2_cfd_lib_ad = static_library('SU2core_AD',
                               su2_cfd_src,
                               install : false,
		               dependencies : [su2_deps, codi_dep, commonAD_dep],
                               cpp_args: [default_warning_flags, su2_cpp_args, codi_rev_args])
  su2_cfd_dep_ad = declare_dependency(link_with: su2_cfd_lib_ad,
                                   include_directories: su2_cfd_include)
  su2_cfd_ad = executable('SU2_CFD_AD',
                          'SU2_CFD.cpp',
                          install : true,
                          dependencies : [su2_cfd_dep_ad, su2_deps, codi_dep, commonAD_dep],
                          cpp_args: ['-fPIC'] + [default_warning_flags, su2_cpp_args, codi_rev_args] + profiling_args,
                          link_args: profiling_args)
endif

#if get_option('enable-enzyme-ad')
#
#  enzyme_include_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/Enzyme/enzyme/build/Enzyme/'  # Adjust this path
#  enzyme_plugin_path = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/Enzyme/enzyme/build/Enzyme/LLVMEnzyme-15.so'  # Adjust this path
#  
#  # Extract CLI11 include path manually
#  cli11_include_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/externals/CLI11'
#  medi_include_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/externals/medi/include'
#  mel_include_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/externals/mel'
#  catch2_include_dir= '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/externals/catch2/'
#  su2_cfd_src_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/SU2_CFD/src/'
#  su2_cfd_include_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/SU2_CFD/include'
#
#  common_include_dir = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/src'
#  common_src_graph = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/src/graph_coloring_structure.cpp'
#  common_src_config = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/src/CConfig.cpp'
#  common_src_ad_structure = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/src/basic_types/ad_structure.cpp'
#  common_src_wall_model = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/src/wall_model.cpp'
#  common_src_mpi_structure = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/include/parallelization/mpi_structure.cpp'
#  common_src_omp_structure = '/home/martin/CMS/MasterThesis/Combined_SU2_Enzyme/SU2_Main/Common/include/parallelization/omp_structure.cpp'
#
#  # Step 1: Generate the intermediate LLVM IR file SU2_CFD.ll from SU2_CFD.cpp
#  su2_cfd_ir = custom_target('SU2_CFD_LLVM_IR',
#                              input: 'SU2_CFD.cpp',
#                              output: 'SU2_CFD_IR.ll',
#                             command: [
#                               'clang++', '@INPUT@', '-S', '-emit-llvm', '-o', '@OUTPUT@',
#                               '-DENABLE_ENZYME_AD',
#                               '-I', enzyme_include_dir,
#                               '-I', su2_cfd_src_dir,
#                               '-I', su2_cfd_include_dir,
#                               '-I', cli11_include_dir,
#                               '-I', mel_include_dir
#                             ],
#                             build_by_default: true,
#                             )
#  
#  # Step 2: Apply Enzyme's AD transformation on SU2_CFD.ll to produce SU2_CFD_opt.ll
#  su2_cfd_opt_ir = custom_target('SU2_CFD_Optimized_IR',
#                                  input: su2_cfd_ir,
#                                  output: 'SU2_CFD_OPT.ll',
#                                 command: [
#                                   'opt-15', '@INPUT@', '--load-pass-plugin=' + enzyme_plugin_path,
#                                   '-passes=enzyme', '-o', '@OUTPUT@', '-S'
#                                 ],
#                                 build_by_default: true,
#                                 depends: su2_cfd_ir
#                                 )
#  
#  # Step 3: Compile SU2_CFD_opt.ll to an object file SU2_CFD_opt.o
#  su2_cfd_opt_obj = custom_target('SU2_CFD_Opt_Obj',
#                              input: su2_cfd_opt_ir,
#                              output: 'SU2_CFD_opt.o',
#                              command: [
#                                'clang++', '-c', '@INPUT@', '-o', '@OUTPUT@',
#                                '-fPIC', '-DENABLE_ENZYME_AD'
#                              ],
#                              build_by_default: true,
#                              depends: su2_cfd_opt_ir
#                              )
#
#  
#    # Link object files and create the executable
#  su2_cfd_lib_enzyme = static_library(
#    'SU2core_Enzyme',
#    su2_cfd_src,
#    install: false,
#    dependencies: [su2_deps, common_dep],
#    cpp_args: [default_warning_flags, su2_cpp_args, '-DENABLE_ENZYME_AD']
#  )
#
#  su2_cfd_dep_enzyme = declare_dependency(
#    link_with: su2_cfd_lib_enzyme,
#    include_directories: su2_cfd_include
#  )
#
#  su2_cfd_enzyme = executable(
#    'SU2_CFD_Enzyme',
#    su2_cfd_opt_obj,
#    install: true,
#    dependencies: [su2_cfd_dep_enzyme, su2_deps, common_dep],
#    cpp_args: ['-fPIC'] + [default_warning_flags, su2_cpp_args, '-DENABLE_ENZYME_AD'] + profiling_args,
#    link_args: profiling_args,
#    link_with: [su2_cfd_lib_enzyme]
#  )
#endif

#Enzyme autodiff build option (without additional optimization steps)
if get_option('enable-enzyme-ad')
  su2_cfd_lib_enzyme = static_library(
    'SU2core_Enzyme',
    su2_cfd_src,
    install: false,
    dependencies: [su2_deps, common_dep],
    cpp_args: [default_warning_flags, su2_cpp_args, '-DENABLE_ENZYME_AD']
  )

  su2_cfd_dep_enzyme = declare_dependency(
    link_with: su2_cfd_lib_enzyme,
    include_directories: su2_cfd_include
  )

  su2_cfd_enzyme = executable(
    'SU2_CFD_Enzyme',
    'SU2_CFD.cpp',
    install: true,
    dependencies: [su2_cfd_dep_enzyme, su2_deps, common_dep],
    cpp_args: ['-fPIC'] + [default_warning_flags, su2_cpp_args, '-DENABLE_ENZYME_AD'] + profiling_args,
    link_args: profiling_args,
    link_with: [su2_cfd_lib_enzyme]
  )
endif

if get_option('enable-directdiff')
  su2_cfd_lib_dd = static_library('SU2core_DIRECTDIFF',
                               su2_cfd_src,
                               install : false,
		               dependencies : [su2_deps, codi_dep, commonDD_dep],
                               cpp_args: [default_warning_flags, su2_cpp_args, codi_for_args])
  su2_cfd_dep_dd = declare_dependency(link_with: su2_cfd_lib_dd,
                                   include_directories: su2_cfd_include)
  su2_cfd_dd = executable('SU2_CFD_DIRECTDIFF',
                          'SU2_CFD.cpp',
                          install : true,
                          dependencies : [su2_cfd_dep_dd, su2_deps, codi_dep, commonDD_dep],
                          cpp_args: ['-fPIC'] + [default_warning_flags, su2_cpp_args, codi_for_args] + profiling_args,
                          link_args: profiling_args)
endif

