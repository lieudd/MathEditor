# Needed due to
# http://stackoverflow.com/questions/33395675/cocoapods-file-reference-is-a-member-of-multiple-groups
install! 'cocoapods', :deterministic_uuids => false

target 'MathEditor_Example' do
  pod 'MathEditor', :path => './'
end
target 'MathEditor_Tests' do
  pod 'MathEditor', :path => './'
end
target 'MathEditor' do
    pod 'iosMath'
end
