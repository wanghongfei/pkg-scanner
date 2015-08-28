## Package Scanner - 包扫描器
扫描出指定包下所有的类名。

### Quick Start
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
