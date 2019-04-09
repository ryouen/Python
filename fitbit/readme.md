This is a fitbit-data reader enables you to extract a lot of .json file where you exported from the fitbit.com
You can aggregate json files into one daily csv files and/or you can make specific dataframe by selecting in/out via #comment in/out.

Fitbit.comから、ふつうにダウンロードできるやつではなく、Exportしたときに、1年間で500～1000個くらいに分かれた、jsonファイルがダウンロードできます。
そのjsonファイルを、所定のフォルダに安置していただくと、
1日毎に集計したデータか、あるいは、指定のデータ(Heart Rateとか、sleepとか)のデータフレームに読み出すものです。
日本語＆Windows環境下では、exerciseというカラムは動かないことがあるので、そちらはご留意ください。
