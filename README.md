# PDFForest (Android)

Offline Android version of the PDFForest tools. Files never leave the phone.

Tools: Merge, Split, Extract Pages, Remove Pages, Rotate, Add Watermark, Add Page Numbers, Images to PDF, PDF to JPG, Image Compressor.
Output is saved to Downloads/PDFForest.

## Build
1. Install Android Studio (Ladybug or newer).
2. File > Open > select this PDFForest folder. Let Gradle sync finish.
3. Plug in a phone (USB debugging on) or start an emulator, then press Run.
4. For an installable APK: Build > Build Bundle(s)/APK(s) > Build APK(s).

Requires Android 10 (API 29) or newer.

## Stack
Kotlin, Jetpack Compose, PdfBox-Android (merge/split/rotate/pages), Android PdfRenderer + PdfDocument (PDF<->image).

## Not included yet
OCR, signing, Word/Excel conversions (these need extra libraries or a server).
