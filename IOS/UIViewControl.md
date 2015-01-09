2015-01-09 19:15:49.555 TTTlabel[25082:246073] *** Terminating app due to uncaught exception 'NSInternalInconsistencyException', reason: 'Could not load NIB in bundle: 'NSBundle </Users/baidu/Library/Developer/CoreSimulator/Devices/0E47D310-E448-4E7B-A468-7CA2B1C03352/data/Containers/Bundle/Application/A7EF9745-2573-48C8-ABBF-5A324898218E/TTTlabel.app> (loaded)' with name 'Ypl-id-UY1-view-BfQ-oe-Nr2''
*** First throw call stack:
(
	0   CoreFoundation                      0x000000010a5abf35 __exceptionPreprocess + 165
	1   libobjc.A.dylib                     0x0000000109e9bbb7 objc_exception_throw + 45
	2   CoreFoundation                      0x000000010a5abe6d +[NSException raise:format:] + 205
	3   UIKit                               0x0000000108ea88c3 -[UINib instantiateWithOwner:options:] + 552
	4   UIKit                               0x0000000108d07f98 -[UIViewController _loadViewFromNibNamed:bundle:] + 242
	5   UIKit                               0x0000000108d08588 -[UIViewController loadView] + 109
	6   UIKit                               0x0000000108d087f9 -[UIViewController loadViewIfRequired] + 75
	7   UIKit                               0x0000000108d08c8e -[UIViewController view] + 27
	8   TTTlabel                            0x0000000107fae725 -[MyViewControl setUpView] + 69
	9   TTTlabel                            0x0000000107fae650 -[MyViewControl initWithCoder:] + 160
	10  UIKit                               0x0000000108ea99dd -[UIClassSwapper initWithCoder:] + 205
	11  UIKit                               0x000000010900e6c6 UINibDecoderDecodeObjectForValue + 705
	12  UIKit                               0x000000010900e3fc -[UINibDecoder decodeObjectForKey:] + 276
	13  UIKit                               0x0000000108ea95d6 -[UIRuntimeConnection initWithCoder:] + 153
	14  UIKit                               0x000000010900e6c6 UINibDecoderDecodeObjectForValue + 705
	15  UIKit                               0x000000010900e895 UINibDecoderDecodeObjectForValue + 1168
	16  UIKit                               0x000000010900e3fc -[UINibDecoder decodeObjectForKey:] + 276
	17  UIKit                               0x0000000108ea8a79 -[UINib instantiateWithOwner:options:] + 990
	18  UIKit                               0x0000000109132572 -[UIStoryboard instantiateViewControllerWithIdentifier:] + 181
	19  UIKit                               0x0000000108be2b92 -[UIApplication _loadMainStoryboardFileNamed:bundle:] + 65
	20  UIKit                               0x0000000108be1c19 -[UIApplication _runWithMainScene:transitionContext:completion:] + 1075
	21  UIKit                               0x0000000108be0bf2 -[UIApplication workspaceDidEndTransaction:] + 179
	22  FrontBoardServices                  0x000000010e2d22a3 __31-[FBSSerialQueue performAsync:]_block_invoke + 16
	23  CoreFoundation                      0x000000010a4e153c __CFRUNLOOP_IS_CALLING_OUT_TO_A_BLOCK__ + 12
	24  CoreFoundation                      0x000000010a4d7285 __CFRunLoopDoBlocks + 341
	25  CoreFoundation                      0x000000010a4d7045 __CFRunLoopRun + 2389
	26  CoreFoundation                      0x000000010a4d6486 CFRunLoopRunSpecific + 470
	27  UIKit                               0x0000000108be0669 -[UIApplication _run] + 413
	28  UIKit                               0x0000000108be3420 UIApplicationMain + 1282
	29  TTTlabel                            0x0000000107fae4d3 main + 115
	30  libdyld.dylib                       0x000000010abf1145 start + 1
	31  ???                                 0x0000000000000001 0x0 + 1
)
libc++abi.dylib: terminating with uncaught exception of type NSException