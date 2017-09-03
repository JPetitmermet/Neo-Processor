# Neo-Processor
Neo-Processor is an alternative optimization heuristic designed for use with FIA BioSum projects (biosum.info). Neo-Processor is Python based and includes both a forward-reaching optimal bucking module for processing cut trees and a landscape level heuristic utilizing a modified Great Deluge algorithm.

Full program documentation can be found in NPDoc.pdf

Python scripts and necessary parameter files can be found in NeoProcessor.zip

Sample prescription inputs can be found in their individual zip files.

Neo-Processor was designed for use with tethered cut-to-length harvesting systems in the Klamath Basin and WILL NOT provide valid outputs for other harvest systems or regions without significant modifications.

Changelog:

8/26/17 - Updated RxEvaluator.py and NPDoc.pdf to reflect significant changes in cost modeling methodology.
9/3/17 - Updated RxEvaluator.py to better reflect Eastside log scaling methods: 24' and 28' logs are now disabled by default and top diameter is now rounded for log pricing (where previously it was truncated). Updated NPDoc.pdf to reflect changes and correct an erroneous reference.
