### This is an in-progress, comprehensive guide for using _manim_.

## mobject Commands

| Command List | Description List |
|-------------|-------------|
| **Displaying Methods** | Description |
| `OBJECT.copy()` | TO-DO |
| ```OBJECT.deep_copy()``` | TO-DO |
| ```OBJECT.generate_target()``` | TO-DO |
| **Updating Methods** | Description |
| ```OBJECT.update()``` | TO-DO |
| ```OBJECT.get_time_based_updaters()``` | TO-DO |
| ```OBJECT.has_time_based_updater()``` | TO-DO |
| ```OBJECT.get_updaters()``` | TO-DO |
| ``` OBJECT.get_family_updaters()``` | TO-DO |
| ``` OBJECT.add_updater()``` | TO-DO |
| ``` OBJECT.remove_updater()``` | TO-DO |
| ``` OBJECT.clear_updaters()``` | TO-DO |
| ``` OBJECT.match_updaters()``` | TO-DO |
| ``` OBJECT.suspend_updaters()``` | TO-DO |
| ``` OBJECT.resume_updaters()``` | TO-DO |
| **Transforming Methods** | Description |
| ``` OBJECT.apply_to_family(function)``` | TO-DO |
| ``` OBJECT.shift(VECTOR)``` | Move `OBJECT` relative to current position by `VECTOR`  |
| ``` OBJECT.scale(DOUBLE)``` | Increase `OBJECT` size multiplicatively by `DOUBLE` |
| ``` OBJECT.rotate_about_origin(ANGLE)``` | Rotate `OBJECT` around `ORIGIN` by `ANGLE` |
| ``` OBJECT.rotate(about_point = VECTOR, ANGLE)``` | Rotate `OBJECT` around `about_point = POINT` by `ANGLE` |
| ``` OBJECT.flip()``` | TO-DO |
| ``` OBJECT.stretch()``` | TO-DO |
| ``` OBJECT.apply_function()``` | TO-DO |
| ``` OBJECT.apply_function_to_position()``` | TO-DO |
| ``` OBJECT.apply_function_to_submobject_positions()``` | TO-DO |
| ``` OBJECT.apply_matrix()``` | TO-DO |
| ``` OBJECT.apply_complex_function()``` | TO-DO |
| ``` OBJECT.wag()``` | TO-DO |
| ``` OBJECT.reverse_points()``` | TO-DO |
| ``` OBJECT.repeat()``` | TO-DO |
| **In-Place Operations** | Description |
| ``` OBJECT.apply_points_function_about_point()``` | TO-DO |
| ``` OBJECT.rotate_in_place(ANGLE)``` | Rotate `OBJECT` around `about_point = OBJECT.get_center()` by `ANGLE` |
| ``` OBJECT.scale_in_place(DOUBLE)``` | Increase `OBJECT` size multiplicatively by `DOUBLE` and keep in place |
| ``` OBJECT.scale_about_point()``` | TO-DO |
| ``` OBJECT.pose_at_angle()``` | TO-DO |
| **Positioning Methods** | Description |
| ``` OBJECT.center()``` | TO-DO |
| ``` OBJECT.align_on_border()``` | TO-DO |
| ``` OBJECT.to_corner(VECTOR)``` | Move `OBJECT` to the specified corner with buffer `buff = DOUBLE` |
| ``` OBJECT.to_edge(VECTOR)``` | Move `OBJECT` to the specified edge with buffer `buff = DOUBLE` |
| ``` OBJECT.next_to(OBJECT, VECTOR)``` | Move `OBJECT` to the another `OBJECT` with buffer `buff = DOUBLE` |
| ``` OBJECT.shift_onto_screen()``` | TO-DO |
| ``` OBJECT.is_off_screen()``` | TO-DO |
| ``` OBJECT.stretch_about_point()``` | TO-DO |
| ``` OBJECT.stretch_in_place()``` | TO-DO |
| ``` OBJECT.rescale_to_fit()``` | TO-DO |
| ``` OBJECT.stretch_to_fit_width()``` | TO-DO |
| ``` OBJECT.stretch_to_fit_height()``` | TO-DO |
| ``` OBJECT.stretch_to_fit_depth()``` | TO-DO |
| ``` OBJECT.set_width()``` | TO-DO |
| ``` OBJECT.set_width()``` | TO-DO |
| ``` OBJECT.set_depth()``` | TO-DO |
| ``` OBJECT.set_coord()``` | TO-DO |
| ``` OBJECT.set_x()``` | TO-DO |
| ``` OBJECT.set_y()``` | TO-DO |
| ``` OBJECT.set_z()``` | TO-DO |
| ``` OBJECT.space_out_submobjects()``` | TO-DO |
| ``` OBJECT.move_to()``` | TO-DO |
| ``` OBJECT.replace()``` | TO-DO |
| ``` OBJECT.surround()``` | TO-DO |
| ``` OBJECT.put_start_and_end_on()``` | TO-DO |
| **Background Rectangle Methods** | Description |
| ``` OBJECT.add_background_rectangle()``` | TO-DO |
| ``` OBJECT.add_background_rectangle_to_submobjects()``` | TO-DO |
| ``` OBJECT.add_background_rectangle_to_family_members_with_points()``` | TO-DO |
| **Coloring Methods** | Description |
| ``` OBJECT.set_color()``` | TO-DO |
| ``` OBJECT.set_color_by_gradient()``` | TO-DO |
| ``` OBJECT.set_colors_by_radial_gradient()``` | TO-DO |
| ``` OBJECT.set_submobject_colors_by_gradient()``` | TO-DO |
| ``` OBJECT.set_submobject_colors_by_radial_gradient()``` | TO-DO |
| ``` OBJECT.to_original_color()``` | TO-DO |
| ``` OBJECT.fade_to()``` | TO-DO |
| ``` OBJECT.fade()``` | TO-DO |
| ``` OBJECT.get_color()``` | TO-DO |
| **State Methods** | Description |
| ``` OBJECT.save_state()``` | TO-DO |
| ``` OBJECT.restore()``` | TO-DO |
| ``` OBJECT.reduce_across_dimension()``` | TO-DO |
| ``` OBJECT.nonempty_submobjects()``` | TO-DO |
| ``` OBJECT.get_merged_array()``` | TO-DO |
| **Getters** | Description |
| ``` OBJECT.get_all_points()``` | TO-DO |
| ``` OBJECT.get_points_defining_boundary()``` | TO-DO |
| ``` OBJECT.get_num_points()``` | TO-DO |
| ``` OBJECT.get_extremum_along_dim()``` | TO-DO |
| ``` OBJECT.get_critical_point()``` | TO-DO |
| ``` OBJECT.get_edge_center()``` | TO-DO |
| ``` OBJECT.get_corner()``` | TO-DO |
| ``` OBJECT.get_center()``` | TO-DO |
| ``` OBJECT.get_center_of_mass()``` | TO-DO |
| ``` OBJECT.get_boundary_point()``` | TO-DO |
| ``` OBJECT.get_top()``` | TO-DO |
| ``` OBJECT.get_bottom()``` | TO-DO |
| ``` OBJECT.get_left()``` | TO-DO |
| ``` OBJECT.get_right()``` | TO-DO |
| ``` OBJECT.get_zenith()``` | TO-DO |
| ``` OBJECT.get_nadir()``` | TO-DO |
| ``` OBJECT.length_over_dim()``` | TO-DO |
| ``` OBJECT.get_width()``` | TO-DO |
| ``` OBJECT.get_height()``` | TO-DO |
| ``` OBJECT.get_depth()``` | TO-DO |
| ``` OBJECT.get_coord()``` | TO-DO |
| ``` OBJECT.get_x()``` | TO-DO |
| ``` OBJECT.get_y()``` | TO-DO |
| ``` OBJECT.get_z()``` | TO-DO |
| ``` OBJECT.get_start()``` | TO-DO |
| ``` OBJECT.get_end()``` | TO-DO |
| ``` OBJECT.get_start_and_end()``` | TO-DO |
| ``` OBJECT.point_from_proportion()``` | TO-DO |
| ``` OBJECT.get_pieces()``` | TO-DO |
| ``` OBJECT.get_z_index_reference_point()``` | TO-DO |
| ``` OBJECT.has_points()``` | TO-DO |
| ``` OBJECT.has_no_points()``` | TO-DO |
| **Matching Methods** | Description |
| ``` OBJECT.match_color()``` | TO-DO |
| ``` OBJECT.match_dim_size()``` | TO-DO |
| ``` OBJECT.match_width()``` | TO-DO |
| ``` OBJECT.match_height()``` | TO-DO |
| ``` OBJECT.match_depth()``` | TO-DO |
| ``` OBJECT.match_coord()``` | TO-DO |
| ``` OBJECT.match_x()``` | TO-DO |
| ``` OBJECT.match_y()``` | TO-DO |
| ``` OBJECT.match_z()``` | TO-DO |
| ``` OBJECT.align_to()``` | TO-DO |
| **Family Methods** | Description |
| ``` OBJECT.get_group_class()``` | TO-DO |
| ``` OBJECT.split()``` | TO-DO |
| ``` OBJECT.get_family()``` | TO-DO |
| ``` OBJECT.family_members_with_points()``` | TO-DO |
| ``` OBJECT.arrange()``` | TO-DO |
| ``` OBJECT.arrange_in_grid()``` | TO-DO |
| ``` OBJECT.sort()``` | TO-DO |
| ``` OBJECT.shuffle()``` | TO-DO |
| **Aligning Methods** | Description |
| ``` OBJECT.align_data()``` | TO-DO |
| ``` OBJECT.get_point_mobject()``` | TO-DO |
| ``` OBJECT.align_points()``` | TO-DO |
| ``` OBJECT.align_points_with_larger()``` | TO-DO |
| ``` OBJECT.align_submobjects()``` | TO-DO |
| ``` OBJECT.null_point_align()``` | TO-DO |
| ``` OBJECT.push_self_into_submobjects()``` | TO-DO |
| ``` OBJECT.add_n_more_submobjects()``` | TO-DO |
| ``` OBJECT.repeat_submobject()``` | TO-DO |
| ``` OBJECT.interpolate()``` | TO-DO |
| ``` OBJECT.interpolate_color()``` | TO-DO |
| ``` OBJECT.become_partial()``` | TO-DO |
| ``` OBJECT.pointwise_become_partial()``` | TO-DO |
| ``` OBJECT.become()``` | TO-DO |
| **Error Methods** | Description |
| ``` OBJECT.throw_error_if_no_points()``` | TO-DO |

Full source code available in mobject.py

## constants

| Command List | Description List |
|-------------|-------------|
| **Camera Configurations** | Description |
| `PRODUCTION_QUALITY_CAMERA_CONFIG` | TO-DO |
| `HIGH_QUALITY_CAMERA_CONFIG` | TO-DO |
| `MEDIUM_QUALITY_CAMERA_CONFIG` | TO-DO |
| `LOW_QUALITY_CAMERA_CONFIG` | TO-DO |
| `DEFAULT_PIXEL_HEIGHT` | TO-DO |
| `DEFAULT_PIXEL_WIDTH` | TO-DO |
| `DEFAULT_FRAME_RATE` | TO-DO |
| `DEFAULT_POINT_DENSITY_2D` | TO-DO |
| `DEFAULT_POINT_DENSITY_1D` | TO-DO |
| `FRAME_HEIGHT` | TO-DO |
| `FRAME_WIDTH` | TO-DO |
| `FRAME_Y_RADIUS` | TO-DO |
| `FRAME_X_RADIUS` | TO-DO |
| **Buffers** | Description |
| `SMALL_BUFF` | TO-DO |
| `MED_SMALL_BUFF` | TO-DO |
| `MED_LARGE_BUFF` | TO-DO |
| `LARGE_BUFF` | TO-DO |
| `DEFAULT_MOBJECT_TO_EDGE_BUFFER` | TO-DO |
| `DEFAULT_MOBJECT_TO_MOBJECT_BUFFER` | TO-DO |
| **Times** | Description |
| `DEFAULT_POINTWISE_FUNCTION_RUN_TIME` | TO-DO |
| `DEFAULT_WAIT_TIME` | TO-DO |
| **Positions** | Description |
| `ORIGIN` | TO-DO |
| `UP` | TO-DO |
| `DOWN` | TO-DO |
| `LEFT` | TO-DO |
| `RIGHT` | TO-DO |
| `IN` | TO-DO |
| `OUT` | TO-DO |
| `X_AXIS` | TO-DO |
| `Y_AXIS` | TO-DO |
| `Z_AXIS` | TO-DO |
| `UL` | TO-DO |
| `UR` | TO-DO |
| `DL` | TO-DO |
| `DR` | TO-DO |
| `TOP` | TO-DO |
| `BOTTOM` | TO-DO |
| `LEFT_SIDE` | TO-DO |
| `RIGHT_SIDE` | TO-DO |
| `TAU` | TO-DO |
| `PI` | TO-DO |
| `DEGREES` | TO-DO |
| **Colors** | Description |
| `DARK_BLUE` | ![#236B8E](https://placehold.it/15/236b8e/000000?text=+) `#236B8E` |
| `DARK_BROWN` | ![#8B4513](https://placehold.it/15/8B4513/000000?text=+) `#236B8E` |
| `LIGHT_BROWN` | ![#CD853F](https://placehold.it/15/CD853F/000000?text=+) `#236B8E` |
| `BLUE_E` | ![#1C758A](https://placehold.it/15/1C758A/000000?text=+) `#236B8E` |
| `BLUE_D` | ![#29ABCA](https://placehold.it/15/29ABCA/000000?text=+) `#236B8E` |
| `BLUE_C` | ![#58C4DD](https://placehold.it/15/58C4DD/000000?text=+) `#236B8E` |
| `BLUE_B` | ![#9CDCEB](https://placehold.it/15/9CDCEB/000000?text=+) `#236B8E` |
| `BLUE_A` | ![#C7E9F1](https://placehold.it/15/C7E9F1/000000?text=+) `#236B8E` |
| `TEAL_E` | ![#49A88F](https://placehold.it/15/49A88F/000000?text=+) `#236B8E` |
| `TEAL_D` | ![#55C1A7](https://placehold.it/15/55C1A7/000000?text=+) `#236B8E` |
| `TEAL_C` | ![#5CD0B3](https://placehold.it/15/5CD0B3/000000?text=+) `#236B8E` |
| `TEAL_B` | ![#76DDC0](https://placehold.it/15/76DDC0/000000?text=+) `#236B8E` |
| `TEAL_A` | ![#ACEAD7](https://placehold.it/15/ACEAD7/000000?text=+) `#236B8E` |
| `GREEN_E` | ![#699C52](https://placehold.it/15/699C52/000000?text=+) `#236B8E` |
| `GREEN_D` | ![#77B05D](https://placehold.it/15/77B05D/000000?text=+) `#236B8E` |
| `GREEN_C` | ![#83C167](https://placehold.it/15/83C167/000000?text=+) `#236B8E` |
| `GREEN_B` | ![#A6CF8C](https://placehold.it/15/A6CF8C/000000?text=+) `#236B8E` |
| `GREEN_A` | ![#C9E2AE](https://placehold.it/15/C9E2AE/000000?text=+) `#236B8E` |
| `YELLOW_E` | ![#E8C11C](https://placehold.it/15/E8C11C/000000?text=+) `#236B8E` |
| `YELLOW_D` | ![#F4D345](https://placehold.it/15/F4D345/000000?text=+) `#236B8E` |
| `YELLOW_C` | ![#FFFF00](https://placehold.it/15/FFFF00/000000?text=+) `#236B8E` |
| `YELLOW_B` | ![#FFEA94](https://placehold.it/15/FFEA94/000000?text=+) `#236B8E` |
| `YELLOW_A` | ![#FFF1B6](https://placehold.it/15/FFF1B6/000000?text=+) `#236B8E` |
| `GOLD_E` | ![#C78D46](https://placehold.it/15/C78D46/000000?text=+) `#236B8E` |
| `GOLD_D` | ![#E1A158](https://placehold.it/15/E1A158/000000?text=+) `#236B8E` |
| `GOLD_C` | ![#F0AC5F](https://placehold.it/15/F0AC5F/000000?text=+) `#236B8E` |
| `GOLD_B` | ![#F9B775](https://placehold.it/15/F9B775/000000?text=+) `#236B8E` |
| `GOLD_A` | ![#F7C797](https://placehold.it/15/F7C797/000000?text=+) `#236B8E` |    
| `RED_E` | ![#CF5044](https://placehold.it/15/CF5044/000000?text=+) `#236B8E` |  
| `RED_D` | ![#E65A4C](https://placehold.it/15/E65A4C/000000?text=+) `#236B8E` |  
| `RED_C` | ![#FC6255](https://placehold.it/15/FC6255/000000?text=+) `#236B8E` |  
| `RED_B` | ![#FF8080](https://placehold.it/15/FF8080/000000?text=+) `#236B8E` |  
| `RED_A` | ![#F7A1A3](https://placehold.it/15/F7A1A3/000000?text=+) `#236B8E` |  
| `MAROON_E` | ![#94424F](https://placehold.it/15/94424F/000000?text=+) `#236B8E` |  
| `MAROON_D` | ![#A24D61](https://placehold.it/15/A24D61/000000?text=+) `#236B8E` |  
| `MAROON_C` | ![#C55F73](https://placehold.it/15/C55F73/000000?text=+) `#236B8E` |  
| `MAROON_B` | ![#EC92AB](https://placehold.it/15/EC92AB/000000?text=+) `#236B8E` |  
| `MAROON_A` | ![#ECABC1](https://placehold.it/15/ECABC1/000000?text=+) `#236B8E` |  
| `PURPLE_E` | ![#644172](https://placehold.it/15/644172/000000?text=+) `#236B8E` |  
| `PURPLE_D` | ![#715582](https://placehold.it/15/715582/000000?text=+) `#236B8E` |  
| `PURPLE_C` | ![#9A72AC](https://placehold.it/15/9A72AC/000000?text=+) `#236B8E` |  
| `PURPLE_B` | ![#B189C6](https://placehold.it/15/B189C6/000000?text=+) `#236B8E` |  
| `PURPLE_A` | ![#CAA3E8](https://placehold.it/15/CAA3E8/000000?text=+) `#236B8E` |  
| `WHITE` | ![#FFFFFF](https://placehold.it/15/CAA3E8/FFFFFF?text=+) `#236B8E` |  
| `BLACK` | ![#000000](https://placehold.it/15/CAA3E8/000000?text=+) `#236B8E` |  
| `LIGHT_GRAY` | ![#BBBBBB](https://placehold.it/15/CAA3E8/BBBBBB?text=+) `#236B8E` |  
| `LIGHT_GREY` | ![#BBBBBB](https://placehold.it/15/CAA3E8/BBBBBB?text=+) `#236B8E` |  
| `GRAY` | ![#888888](https://placehold.it/15/CAA3E8/888888?text=+) `#236B8E` |  
| `GREY` | ![#888888](https://placehold.it/15/CAA3E8/888888?text=+) `#236B8E` |  
| `DARK_GREY` | ![#444444](https://placehold.it/15/CAA3E8/444444?text=+) `#236B8E` |  
| `DARK_GRAY` | ![#444444](https://placehold.it/15/CAA3E8/444444?text=+) `#236B8E` |  
| `DARKER_GREY` | ![#222222](https://placehold.it/15/CAA3E8/222222?text=+) `#236B8E` |  
| `DARKER_GRAY` | ![#222222](https://placehold.it/15/CAA3E8/222222?text=+) `#236B8E` |  
| `GREY_BROWN` | ![#736357](https://placehold.it/15/736357/000000?text=+) `#236B8E` |  
| `PINK` | ![#D147BD](https://placehold.it/15/D147BD/000000?text=+) `#236B8E` |  
| `LIGHT_PINK` | ![#DC75CD](https://placehold.it/15/DC75CD/000000?text=+) `#236B8E` |  
| `GREEN_SCREEN` | ![#00FF00](https://placehold.it/15/00FF00/000000?text=+) `#236B8E` |  
| `ORANGE` | ![#FF862F](https://placehold.it/15/FF862F/000000?text=+) `#236B8E` |  
| `PALETTE` | TO-DO |
| **Livestream Configurations** | Description |
| `LIVE_STREAM_NAME` | TO-DO |
| `TWITCH_STREAM_KEY` | TO-DO |
| `STREAMING_PROTOCOL` | TO-DO |
| `STREAMING_IP` | TO-DO |
| `STREAMING_PORT` | TO-DO |
| `STREAMING_CLIENT` | TO-DO |
| `STREAMING_URL` | TO-DO |
| `STREAMING_CONSOLE_BANNER` | TO-DO |
| **Other** | Description |
| `DEFAULT_STROKE_WIDTH` | TO-DO |
| `FFMPEG_BIN` | TO-DO |

Full source code available in constants.py
