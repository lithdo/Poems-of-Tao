# Poems-of-Tao

陶渊明诗集。

## 生成epub文件

Linux下用`zip`命令生成epub文件：

```bash
zip tao.zip epub-source/mimetype
zip -r tao.zip epub-source/{META-INF,OEBPS}
mv tao.{zip,epub}
```

Windows下，右键新建zip文件，然后依次将mimetype, META-INF, OEBPS添加
进zip文件（将文件拖放到zip文件即可）。注意：mimetype必须第一个添加。
