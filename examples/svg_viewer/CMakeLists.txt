add_executable (svg_test svg_test.cpp agg_svg_parser.cpp agg_svg_path_renderer.cpp agg_svg_path_tokenizer.cpp)
target_link_libraries (svg_test agg-demo ${SDL_LIBRARY} ${EXPAT_LIBRARIES})