examples_dep = dependency('elementary', required : true)

source_file = [
    'Arc.cpp',
    'Async.cpp',
    'Blending.cpp',
    'Boundary.cpp',
    'Capi.cpp',
    'CustomTransform.cpp',
    'DirectUpdate.cpp',
    'Duplicate.cpp',
    'FillRule.cpp',
    'GradientStroke.cpp',
    'GradientTransform.cpp',
    'LinearGradient.cpp',
    'MultiCanvas.cpp',
    'MultiShapes.cpp',
    'Opacity.cpp',
    'PathCopy.cpp',
    'Path.cpp',
    'PicturePng.cpp',
    'PictureRaw.cpp',
    'RadialGradient.cpp',
    'Scene.cpp',
    'SceneTransform.cpp',
    'Shape.cpp',
    'Stacking.cpp',
    'Stress.cpp',
    'Stroke.cpp',
    'StrokeLine.cpp',
    'Svg2.cpp',
    'Svg.cpp',
    'Transform.cpp',
    'Update.cpp',
    'ClipPath.cpp',
    'Masking.cpp',
    'InvMasking.cpp',
    'GradientMasking.cpp',
    'AnimateMasking.cpp',
]

foreach current_file : source_file
    name = current_file.split('.')[0]
    executable(name, current_file,
           include_directories : headers,
           link_with : thorvg_lib,
           dependencies : examples_dep)
endforeach
