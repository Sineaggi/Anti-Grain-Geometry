set (CTRL
    agg_bezier_ctrl.cpp
    agg_cbox_ctrl.cpp
    agg_gamma_ctrl.cpp
    agg_gamma_spline.cpp
    agg_polygon_ctrl.cpp
    agg_rbox_ctrl.cpp
    agg_scale_ctrl.cpp
    agg_slider_ctrl.cpp
    agg_spline_ctrl.cpp)

add_library (agg-ctrl OBJECT ${CTRL})
