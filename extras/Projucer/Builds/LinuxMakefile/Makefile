# Automatically generated makefile, created by the Projucer
# Don't edit this file! Your changes will be overwritten when you re-save the Projucer project!

# build with "V=1" for verbose builds
ifeq ($(V), 1)
V_AT =
else
V_AT = @
endif

# (this disables dependency generation if multiple architectures are set)
DEPFLAGS := $(if $(word 2, $(TARGET_ARCH)), , -MMD)

ifndef STRIP
  STRIP=strip
endif

ifndef AR
  AR=ar
endif

ifndef CONFIG
  CONFIG=Debug
endif

ifeq ($(CONFIG),Debug)
  JUCE_BINDIR := build
  JUCE_LIBDIR := build
  JUCE_OBJDIR := build/intermediate/Debug
  JUCE_OUTDIR := build

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := -march=native
  endif

  JUCE_CPPFLAGS := $(DEPFLAGS) -DLINUX=1 -DDEBUG=1 -D_DEBUG=1 -DJUCER_LINUX_MAKE_6D53C8B4=1 -DJUCE_APP_VERSION=5.0.2 -DJUCE_APP_VERSION_HEX=0x50002 $(shell pkg-config --cflags freetype2 libcurl x11 xext xinerama webkit2gtk-4.0 gtk+-x11-3.0) -pthread -I../../JuceLibraryCode -I../../../../modules $(CPPFLAGS)
  JUCE_CPPFLAGS_APP := -DJucePlugin_Build_VST=0 -DJucePlugin_Build_VST3=0 -DJucePlugin_Build_AU=0 -DJucePlugin_Build_AUv3=0 -DJucePlugin_Build_RTAS=0 -DJucePlugin_Build_AAX=0 -DJucePlugin_Build_Standalone=0
  JUCE_TARGET_APP := Projucer

  JUCE_CFLAGS += $(JUCE_CPPFLAGS) $(TARGET_ARCH) -g -ggdb -O0 -std=c++11 $(CFLAGS)
  JUCE_CXXFLAGS += $(CXXFLAGS) $(JUCE_CFLAGS) -std=c++11 $(CXXFLAGS)
  JUCE_LDFLAGS += $(TARGET_ARCH) -L$(JUCE_BINDIR) -L$(JUCE_LIBDIR) $(shell pkg-config --libs freetype2 libcurl x11 xext xinerama webkit2gtk-4.0 gtk+-x11-3.0) -ldl -lpthread -lrt  $(LDFLAGS)

  CLEANCMD = rm -rf $(JUCE_OUTDIR)/$(TARGET) $(JUCE_OBJDIR)
endif

ifeq ($(CONFIG),Release)
  JUCE_BINDIR := build
  JUCE_LIBDIR := build
  JUCE_OBJDIR := build/intermediate/Release
  JUCE_OUTDIR := build

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := -march=native
  endif

  JUCE_CPPFLAGS := $(DEPFLAGS) -DLINUX=1 -DNDEBUG=1 -DJUCER_LINUX_MAKE_6D53C8B4=1 -DJUCE_APP_VERSION=5.0.2 -DJUCE_APP_VERSION_HEX=0x50002 $(shell pkg-config --cflags freetype2 libcurl x11 xext xinerama webkit2gtk-4.0 gtk+-x11-3.0) -pthread -I../../JuceLibraryCode -I../../../../modules $(CPPFLAGS)
  JUCE_CPPFLAGS_APP := -DJucePlugin_Build_VST=0 -DJucePlugin_Build_VST3=0 -DJucePlugin_Build_AU=0 -DJucePlugin_Build_AUv3=0 -DJucePlugin_Build_RTAS=0 -DJucePlugin_Build_AAX=0 -DJucePlugin_Build_Standalone=0
  JUCE_TARGET_APP := Projucer

  JUCE_CFLAGS += $(JUCE_CPPFLAGS) $(TARGET_ARCH) -O3 -std=c++11 $(CFLAGS)
  JUCE_CXXFLAGS += $(CXXFLAGS) $(JUCE_CFLAGS) -std=c++11 $(CXXFLAGS)
  JUCE_LDFLAGS += $(TARGET_ARCH) -L$(JUCE_BINDIR) -L$(JUCE_LIBDIR) -fvisibility=hidden $(shell pkg-config --libs freetype2 libcurl x11 xext xinerama webkit2gtk-4.0 gtk+-x11-3.0) -ldl -lpthread -lrt  $(LDFLAGS)

  CLEANCMD = rm -rf $(JUCE_OUTDIR)/$(TARGET) $(JUCE_OBJDIR)
endif

OBJECTS_APP := \
  $(JUCE_OBJDIR)/jucer_AppearanceSettings_788d9889.o \
  $(JUCE_OBJDIR)/jucer_AutoUpdater_ca658dc2.o \
  $(JUCE_OBJDIR)/jucer_CommandLine_f35de107.o \
  $(JUCE_OBJDIR)/jucer_DocumentEditorComponent_695dff1d.o \
  $(JUCE_OBJDIR)/jucer_DownloadCompileEngineThread_8a38703f.o \
  $(JUCE_OBJDIR)/jucer_GlobalPreferences_b0f1bd3d.o \
  $(JUCE_OBJDIR)/jucer_Main_f8488f5b.o \
  $(JUCE_OBJDIR)/jucer_MainWindow_1e163aeb.o \
  $(JUCE_OBJDIR)/jucer_OpenDocumentManager_4c72d210.o \
  $(JUCE_OBJDIR)/jucer_LicenseController_9abff0cf.o \
  $(JUCE_OBJDIR)/projucer_CompileEngineClient_542e6b2d.o \
  $(JUCE_OBJDIR)/projucer_CompileEngineServer_a5a32aa5.o \
  $(JUCE_OBJDIR)/jucer_SourceCodeEditor_461f5487.o \
  $(JUCE_OBJDIR)/jucer_ComponentTypeHandler_6bec6262.o \
  $(JUCE_OBJDIR)/jucer_ButtonDocument_56c341cc.o \
  $(JUCE_OBJDIR)/jucer_ComponentDocument_92868083.o \
  $(JUCE_OBJDIR)/jucer_ColouredElement_70cbc839.o \
  $(JUCE_OBJDIR)/jucer_PaintElement_653460.o \
  $(JUCE_OBJDIR)/jucer_PaintElementPath_908894a5.o \
  $(JUCE_OBJDIR)/jucer_ComponentLayoutEditor_aeb44f8d.o \
  $(JUCE_OBJDIR)/jucer_ComponentOverlayComponent_fd508d63.o \
  $(JUCE_OBJDIR)/jucer_EditingPanelBase_6c2ed9ee.o \
  $(JUCE_OBJDIR)/jucer_JucerDocumentEditor_2c581e26.o \
  $(JUCE_OBJDIR)/jucer_PaintRoutineEditor_f6ac0344.o \
  $(JUCE_OBJDIR)/jucer_PaintRoutinePanel_c309a0d7.o \
  $(JUCE_OBJDIR)/jucer_ResourceEditorPanel_a558f2e2.o \
  $(JUCE_OBJDIR)/jucer_TestComponent_db757dc4.o \
  $(JUCE_OBJDIR)/jucer_BinaryResources_e0f99b46.o \
  $(JUCE_OBJDIR)/jucer_ComponentLayout_6ea00129.o \
  $(JUCE_OBJDIR)/jucer_GeneratedCode_9ca4ef7e.o \
  $(JUCE_OBJDIR)/jucer_JucerDocument_ff8afcc2.o \
  $(JUCE_OBJDIR)/jucer_ObjectTypes_4406f01c.o \
  $(JUCE_OBJDIR)/jucer_PaintRoutine_e1e891ee.o \
  $(JUCE_OBJDIR)/jucer_DependencyPathPropertyComponent_4d137229.o \
  $(JUCE_OBJDIR)/jucer_Module_3f7666a5.o \
  $(JUCE_OBJDIR)/jucer_Project_c131864a.o \
  $(JUCE_OBJDIR)/jucer_ProjectExporter_eefe2e5b.o \
  $(JUCE_OBJDIR)/jucer_ProjectSaver_38b16c25.o \
  $(JUCE_OBJDIR)/jucer_ResourceFile_6af120d3.o \
  $(JUCE_OBJDIR)/jucer_CodeHelpers_c317179c.o \
  $(JUCE_OBJDIR)/jucer_FileHelpers_f98ed0ad.o \
  $(JUCE_OBJDIR)/jucer_Icons_9db2f51e.o \
  $(JUCE_OBJDIR)/jucer_JucerTreeViewBase_d043309d.o \
  $(JUCE_OBJDIR)/jucer_MiscUtilities_25b68c82.o \
  $(JUCE_OBJDIR)/jucer_ProjucerLookAndFeel_d6c6b28a.o \
  $(JUCE_OBJDIR)/jucer_SlidingPanelComponent_9aa7a2ab.o \
  $(JUCE_OBJDIR)/jucer_StoredSettings_26078d2c.o \
  $(JUCE_OBJDIR)/jucer_NewFileWizard_fac97f47.o \
  $(JUCE_OBJDIR)/jucer_NewProjectWizardClasses_891f6fa2.o \
  $(JUCE_OBJDIR)/BinaryData_ce4232d4.o \
  $(JUCE_OBJDIR)/include_juce_core_f26d17db.o \
  $(JUCE_OBJDIR)/include_juce_cryptography_8cb807a8.o \
  $(JUCE_OBJDIR)/include_juce_data_structures_7471b1e3.o \
  $(JUCE_OBJDIR)/include_juce_events_fd7d695.o \
  $(JUCE_OBJDIR)/include_juce_graphics_f817e147.o \
  $(JUCE_OBJDIR)/include_juce_gui_basics_e3f79785.o \
  $(JUCE_OBJDIR)/include_juce_gui_extra_6dee1c1a.o \

.PHONY: clean all

$(JUCE_OUTDIR)/$(JUCE_TARGET_APP) : check-pkg-config $(OBJECTS_APP) $(RESOURCES)
	@echo Linking "Projucer - App"
	-$(V_AT)mkdir -p $(JUCE_BINDIR)
	-$(V_AT)mkdir -p $(JUCE_LIBDIR)
	-$(V_AT)mkdir -p $(JUCE_OUTDIR)
	$(V_AT)$(CXX) -o $(JUCE_OUTDIR)/$(JUCE_TARGET_APP) $(OBJECTS_APP) $(JUCE_LDFLAGS) $(RESOURCES) $(TARGET_ARCH)

$(JUCE_OBJDIR)/jucer_AppearanceSettings_788d9889.o: ../../Source/Application/jucer_AppearanceSettings.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_AppearanceSettings.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_AutoUpdater_ca658dc2.o: ../../Source/Application/jucer_AutoUpdater.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_AutoUpdater.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_CommandLine_f35de107.o: ../../Source/Application/jucer_CommandLine.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_CommandLine.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_DocumentEditorComponent_695dff1d.o: ../../Source/Application/jucer_DocumentEditorComponent.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_DocumentEditorComponent.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_DownloadCompileEngineThread_8a38703f.o: ../../Source/Application/jucer_DownloadCompileEngineThread.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_DownloadCompileEngineThread.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_GlobalPreferences_b0f1bd3d.o: ../../Source/Application/jucer_GlobalPreferences.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_GlobalPreferences.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_Main_f8488f5b.o: ../../Source/Application/jucer_Main.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_Main.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_MainWindow_1e163aeb.o: ../../Source/Application/jucer_MainWindow.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_MainWindow.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_OpenDocumentManager_4c72d210.o: ../../Source/Application/jucer_OpenDocumentManager.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_OpenDocumentManager.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_LicenseController_9abff0cf.o: ../../Source/Licenses/jucer_LicenseController.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_LicenseController.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/projucer_CompileEngineClient_542e6b2d.o: ../../Source/LiveBuildEngine/projucer_CompileEngineClient.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling projucer_CompileEngineClient.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/projucer_CompileEngineServer_a5a32aa5.o: ../../Source/LiveBuildEngine/projucer_CompileEngineServer.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling projucer_CompileEngineServer.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_SourceCodeEditor_461f5487.o: ../../Source/Code\ Editor/jucer_SourceCodeEditor.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_SourceCodeEditor.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ComponentTypeHandler_6bec6262.o: ../../Source/ComponentEditor/components/jucer_ComponentTypeHandler.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ComponentTypeHandler.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ButtonDocument_56c341cc.o: ../../Source/ComponentEditor/documents/jucer_ButtonDocument.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ButtonDocument.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ComponentDocument_92868083.o: ../../Source/ComponentEditor/documents/jucer_ComponentDocument.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ComponentDocument.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ColouredElement_70cbc839.o: ../../Source/ComponentEditor/paintelements/jucer_ColouredElement.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ColouredElement.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_PaintElement_653460.o: ../../Source/ComponentEditor/paintelements/jucer_PaintElement.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_PaintElement.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_PaintElementPath_908894a5.o: ../../Source/ComponentEditor/paintelements/jucer_PaintElementPath.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_PaintElementPath.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ComponentLayoutEditor_aeb44f8d.o: ../../Source/ComponentEditor/ui/jucer_ComponentLayoutEditor.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ComponentLayoutEditor.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ComponentOverlayComponent_fd508d63.o: ../../Source/ComponentEditor/ui/jucer_ComponentOverlayComponent.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ComponentOverlayComponent.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_EditingPanelBase_6c2ed9ee.o: ../../Source/ComponentEditor/ui/jucer_EditingPanelBase.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_EditingPanelBase.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_JucerDocumentEditor_2c581e26.o: ../../Source/ComponentEditor/ui/jucer_JucerDocumentEditor.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_JucerDocumentEditor.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_PaintRoutineEditor_f6ac0344.o: ../../Source/ComponentEditor/ui/jucer_PaintRoutineEditor.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_PaintRoutineEditor.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_PaintRoutinePanel_c309a0d7.o: ../../Source/ComponentEditor/ui/jucer_PaintRoutinePanel.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_PaintRoutinePanel.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ResourceEditorPanel_a558f2e2.o: ../../Source/ComponentEditor/ui/jucer_ResourceEditorPanel.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ResourceEditorPanel.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_TestComponent_db757dc4.o: ../../Source/ComponentEditor/ui/jucer_TestComponent.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_TestComponent.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_BinaryResources_e0f99b46.o: ../../Source/ComponentEditor/jucer_BinaryResources.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_BinaryResources.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ComponentLayout_6ea00129.o: ../../Source/ComponentEditor/jucer_ComponentLayout.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ComponentLayout.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_GeneratedCode_9ca4ef7e.o: ../../Source/ComponentEditor/jucer_GeneratedCode.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_GeneratedCode.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_JucerDocument_ff8afcc2.o: ../../Source/ComponentEditor/jucer_JucerDocument.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_JucerDocument.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ObjectTypes_4406f01c.o: ../../Source/ComponentEditor/jucer_ObjectTypes.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ObjectTypes.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_PaintRoutine_e1e891ee.o: ../../Source/ComponentEditor/jucer_PaintRoutine.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_PaintRoutine.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_DependencyPathPropertyComponent_4d137229.o: ../../Source/Project/jucer_DependencyPathPropertyComponent.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_DependencyPathPropertyComponent.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_Module_3f7666a5.o: ../../Source/Project/jucer_Module.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_Module.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_Project_c131864a.o: ../../Source/Project/jucer_Project.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_Project.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ProjectExporter_eefe2e5b.o: ../../Source/Project\ Saving/jucer_ProjectExporter.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ProjectExporter.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ProjectSaver_38b16c25.o: ../../Source/Project\ Saving/jucer_ProjectSaver.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ProjectSaver.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ResourceFile_6af120d3.o: ../../Source/Project\ Saving/jucer_ResourceFile.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ResourceFile.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_CodeHelpers_c317179c.o: ../../Source/Utility/jucer_CodeHelpers.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_CodeHelpers.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_FileHelpers_f98ed0ad.o: ../../Source/Utility/jucer_FileHelpers.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_FileHelpers.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_Icons_9db2f51e.o: ../../Source/Utility/jucer_Icons.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_Icons.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_JucerTreeViewBase_d043309d.o: ../../Source/Utility/jucer_JucerTreeViewBase.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_JucerTreeViewBase.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_MiscUtilities_25b68c82.o: ../../Source/Utility/jucer_MiscUtilities.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_MiscUtilities.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_ProjucerLookAndFeel_d6c6b28a.o: ../../Source/Utility/jucer_ProjucerLookAndFeel.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_ProjucerLookAndFeel.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_SlidingPanelComponent_9aa7a2ab.o: ../../Source/Utility/jucer_SlidingPanelComponent.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_SlidingPanelComponent.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_StoredSettings_26078d2c.o: ../../Source/Utility/jucer_StoredSettings.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_StoredSettings.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_NewFileWizard_fac97f47.o: ../../Source/Wizards/jucer_NewFileWizard.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_NewFileWizard.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jucer_NewProjectWizardClasses_891f6fa2.o: ../../Source/Wizards/jucer_NewProjectWizardClasses.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jucer_NewProjectWizardClasses.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/BinaryData_ce4232d4.o: ../../JuceLibraryCode/BinaryData.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling BinaryData.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_core_f26d17db.o: ../../JuceLibraryCode/include_juce_core.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_core.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_cryptography_8cb807a8.o: ../../JuceLibraryCode/include_juce_cryptography.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_cryptography.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_data_structures_7471b1e3.o: ../../JuceLibraryCode/include_juce_data_structures.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_data_structures.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_events_fd7d695.o: ../../JuceLibraryCode/include_juce_events.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_events.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_graphics_f817e147.o: ../../JuceLibraryCode/include_juce_graphics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_graphics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_gui_basics_e3f79785.o: ../../JuceLibraryCode/include_juce_gui_basics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_gui_basics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_gui_extra_6dee1c1a.o: ../../JuceLibraryCode/include_juce_gui_extra.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_gui_extra.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

check-pkg-config:
	@command -v pkg-config >/dev/null 2>&1 || { echo >&2 "pkg-config not installed. Please, install it."; exit 1; }
	@pkg-config --print-errors freetype2 libcurl x11 xext xinerama

clean:
	@echo Cleaning Projucer
	$(V_AT)$(CLEANCMD)

strip:
	@echo Stripping Projucer
	-$(V_AT)$(STRIP) --strip-unneeded $(JUCE_OUTDIR)/$(TARGET)

-include $(OBJECTS_APP:%.o=%.d)
