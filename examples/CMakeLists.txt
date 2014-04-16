add_executable (aa_demo aa_demo.cpp)
target_link_libraries (aa_demo agg-demo ${SDL_LIBRARY})

add_executable (aa_test aa_test.cpp)
target_link_libraries (aa_test agg-demo ${SDL_LIBRARY})

add_executable (alpha_gradient alpha_gradient.cpp)
target_link_libraries (alpha_gradient agg-demo ${SDL_LIBRARY})

add_executable (alpha_mask alpha_mask.cpp parse_lion.cpp)
target_link_libraries (alpha_mask agg-demo ${SDL_LIBRARY})

add_executable (alpha_mask2 alpha_mask2.cpp parse_lion.cpp)
target_link_libraries (alpha_mask2 agg-demo ${SDL_LIBRARY})

add_executable (alpha_mask3 alpha_mask3.cpp make_gb_poly.cpp make_arrows.cpp)
target_link_libraries (alpha_mask3 agg-demo ${SDL_LIBRARY})

add_executable (bezier_div bezier_div.cpp)
target_link_libraries (bezier_div agg-demo ${SDL_LIBRARY})

add_executable (blend_color blend_color.cpp)
target_link_libraries (blend_color agg-demo ${SDL_LIBRARY})

add_executable (blur blur.cpp)
target_link_libraries (blur agg-demo ${SDL_LIBRARY})

add_executable (bspline bspline.cpp interactive_polygon.cpp)
target_link_libraries (bspline agg-demo ${SDL_LIBRARY})

add_executable (circles circles.cpp)
target_link_libraries (circles agg-demo ${SDL_LIBRARY})

add_executable (component_rendering component_rendering.cpp)
target_link_libraries (component_rendering agg-demo ${SDL_LIBRARY})

add_executable (compositing compositing.cpp)
target_link_libraries (compositing agg-demo ${SDL_LIBRARY})

add_executable (compositing2 compositing2.cpp)
target_link_libraries (compositing2 agg-demo ${SDL_LIBRARY})

add_executable (conv_contour conv_contour.cpp)
target_link_libraries (conv_contour agg-demo ${SDL_LIBRARY})

add_executable (conv_dash_marker conv_dash_marker.cpp)
target_link_libraries (conv_dash_marker agg-demo ${SDL_LIBRARY})

add_executable (conv_stroke conv_stroke.cpp)
target_link_libraries (conv_stroke agg-demo ${SDL_LIBRARY})

add_executable (distortions distortions.cpp)
target_link_libraries (distortions agg-demo ${SDL_LIBRARY})

add_executable (flash_rasterizer flash_rasterizer.cpp)
target_link_libraries (flash_rasterizer agg-demo ${SDL_LIBRARY})

add_executable (flash_rasterizer2 flash_rasterizer2.cpp ../font_freetype/agg_font_freetype.cpp)
target_link_libraries (flash_rasterizer2 agg-demo ${SDL_LIBRARY} ${FREETYPE_LIBRARY})

add_executable (freetype_test freetype_test.cpp ../font_freetype/agg_font_freetype.cpp)
target_link_libraries (freetype_test agg-demo ${SDL_LIBRARY} ${FREETYPE_LIBRARY})

add_executable (gamma_correction gamma_correction.cpp)
target_link_libraries (gamma_correction agg-demo ${SDL_LIBRARY})

add_executable (gamma_ctrl gamma_ctrl.cpp)
target_link_libraries (gamma_ctrl agg-demo ${SDL_LIBRARY})

add_executable (gamma_tuner gamma_tuner.cpp)
target_link_libraries (gamma_tuner agg-demo ${SDL_LIBRARY})

add_executable (gouraud gouraud.cpp)
target_link_libraries (gouraud agg-demo ${SDL_LIBRARY})

add_executable (gouraud_mesh gouraud_mesh.cpp)
target_link_libraries (gouraud_mesh agg-demo ${SDL_LIBRARY})

add_executable (gpc_test gpc_test.cpp ../gpc/gpc.c make_arrows.cpp make_gb_poly.cpp)
target_link_libraries (gpc_test agg-demo ${SDL_LIBRARY})

add_executable (gradients gradients.cpp)
target_link_libraries (gradients agg-demo ${SDL_LIBRARY})

add_executable (gradient_focal gradient_focal.cpp)
target_link_libraries (gradient_focal agg-demo ${SDL_LIBRARY})

add_executable (graph_test graph_test.cpp)
target_link_libraries (graph_test agg-demo ${SDL_LIBRARY})

add_executable (idea idea.cpp)
target_link_libraries (idea agg-demo ${SDL_LIBRARY})

add_executable (image1 image1.cpp)
target_link_libraries (image1 agg-demo ${SDL_LIBRARY})

add_executable (image_alpha image_alpha.cpp)
target_link_libraries (image_alpha agg-demo ${SDL_LIBRARY})

add_executable (image_filters image_filters.cpp)
target_link_libraries (image_filters agg-demo ${SDL_LIBRARY})

add_executable (image_filters2 image_filters2.cpp)
target_link_libraries (image_filters2 agg-demo ${SDL_LIBRARY})

add_executable (image_fltr_graph image_fltr_graph.cpp)
target_link_libraries (image_fltr_graph agg-demo ${SDL_LIBRARY})

add_executable (image_perspective image_perspective.cpp interactive_polygon.cpp)
target_link_libraries (image_perspective agg-demo ${SDL_LIBRARY})

add_executable (image_resample image_resample.cpp interactive_polygon)
target_link_libraries (image_resample agg-demo ${SDL_LIBRARY})

add_executable (image_transforms image_transforms.cpp)
target_link_libraries (image_transforms agg-demo ${SDL_LIBRARY})

add_executable (line_patterns line_patterns.cpp)
target_link_libraries (line_patterns agg-demo ${SDL_LIBRARY})

add_executable (line_patterns_clip line_patterns_clip.cpp)
target_link_libraries (line_patterns_clip agg-demo ${SDL_LIBRARY})

add_executable (lion lion.cpp parse_lion.cpp)
target_link_libraries (lion agg-demo ${SDL_LIBRARY})

add_executable (lion_lens lion_lens.cpp parse_lion.cpp)
target_link_libraries (lion_lens agg-demo ${SDL_LIBRARY})

add_executable (lion_outline lion_outline.cpp parse_lion.cpp)
target_link_libraries (lion_outline agg-demo ${SDL_LIBRARY})

add_executable (mol_view mol_view.cpp)
target_link_libraries (mol_view agg-demo ${SDL_LIBRARY})

add_executable (multi_clip multi_clip.cpp parse_lion.cpp)
target_link_libraries (multi_clip agg-demo ${SDL_LIBRARY})

add_executable (pattern_fill pattern_fill.cpp)
target_link_libraries (pattern_fill agg-demo ${SDL_LIBRARY})

add_executable (pattern_perspective pattern_perspective.cpp interactive_polygon.cpp)
target_link_libraries (pattern_perspective agg-demo ${SDL_LIBRARY})

add_executable (pattern_resample pattern_resample.cpp interactive_polygon.cpp)
target_link_libraries (pattern_resample agg-demo ${SDL_LIBRARY})

add_executable (perspective perspective.cpp interactive_polygon.cpp parse_lion.cpp)
target_link_libraries (perspective agg-demo ${SDL_LIBRARY})

add_executable (polymorphic_renderer polymorphic_renderer.cpp)
target_link_libraries (polymorphic_renderer agg-demo ${SDL_LIBRARY})

add_executable (rasterizers rasterizers.cpp)
target_link_libraries (rasterizers agg-demo ${SDL_LIBRARY})

add_executable (rasterizers2 rasterizers2.cpp)
target_link_libraries (rasterizers2 agg-demo ${SDL_LIBRARY})

add_executable (rasterizer_compound rasterizer_compound.cpp)
target_link_libraries (rasterizer_compound agg-demo ${SDL_LIBRARY})

add_executable (raster_text raster_text.cpp)
target_link_libraries (raster_text agg-demo ${SDL_LIBRARY})

add_executable (rounded_rect rounded_rect.cpp)
target_link_libraries (rounded_rect agg-demo ${SDL_LIBRARY})

add_executable (scanline_boolean scanline_boolean.cpp interactive_polygon.cpp)
target_link_libraries (scanline_boolean agg-demo ${SDL_LIBRARY})

add_executable (scanline_boolean2 scanline_boolean2.cpp make_gb_poly.cpp make_arrows.cpp)
target_link_libraries (scanline_boolean2 agg-demo ${SDL_LIBRARY})

add_executable (simple_blur simple_blur.cpp parse_lion.cpp)
target_link_libraries (simple_blur agg-demo ${SDL_LIBRARY})

add_subdirectory (svg_viewer)

if (WIN32)
  add_executable (trans_curve1 trans_curve1.cpp)
  target_link_libraries (trans_curve1 agg-demo ${SDL_LIBRARY})
else ()
  add_executable (trans_curve1_ft trans_curve1_ft.cpp interactive_polygon.cpp ../font_freetype/agg_font_freetype.cpp)
  target_link_libraries (trans_curve1_ft agg-demo ${SDL_LIBRARY} ${FREETYPE_LIBRARY})
endif ()

if (WIN32)
  add_executable (trans_curve2 trans_curve2.cpp)
  target_link_libraries (trans_curve2 agg-demo ${SDL_LIBRARY})
else ()
  add_executable (trans_curve2_ft trans_curve2_ft.cpp interactive_polygon.cpp ../font_freetype/agg_font_freetype.cpp)
  target_link_libraries (trans_curve2_ft agg-demo ${SDL_LIBRARY} ${FREETYPE_LIBRARY})
endif ()

add_executable (trans_polar trans_polar.cpp)
target_link_libraries (trans_polar agg-demo ${SDL_LIBRARY})

if (WIN32)
  add_executable (truetype_test truetype_test.cpp)
  target_link_libraries (truetype_test agg-demo ${SDL_LIBRARY})
endif ()