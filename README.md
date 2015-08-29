## Package Scanner - The missing scanner in Java world
扫描出指定包下所有的类名。

### Quick Start
指定包名:
```
	PkgScanner scanner = new PkgScanner("cn.fh.pkgscanner");
	List<String> list = scanner.scan();

	list.forEach( f -> System.out.println(f));

```
输出结果:
```
cn.fh.pkgscanner.PathUtils
cn.fh.pkgscanner.PkgScanner
cn.fh.pkgscanner.ResourceType
```

指定包名和注解名:
```
	PkgScanner scanner = new PkgScanner("cn.fh.pkgscanner", Component.class);
	List<String> list = scanner.scan();

	list.forEach( f -> System.out.println(f));
```
