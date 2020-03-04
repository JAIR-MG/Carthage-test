## Run carthage update

## Run the project:
- In the root of the project run:

- carthage update RxSwift --platform iOS --no-build
- sed -i -e 's/MACH_O_TYPE = mh_dylib/MACH_O_TYPE = staticlib/g' Carthage/Checkouts/RxSwift/Rx.xcodeproj/project.pbxproj
- carthage build RxSwift --platform iOS
