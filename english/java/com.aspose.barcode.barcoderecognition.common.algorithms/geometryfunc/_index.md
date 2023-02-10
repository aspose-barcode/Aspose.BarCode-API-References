---
title: GeometryFunc
second_title: Aspose.BarCode for Java API Reference
description: 2D geometrical functions implementation
type: docs
weight: 24
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/geometryfunc/
---
**Inheritance:**
java.lang.Object
```
public class GeometryFunc
```

2D geometrical functions implementation
## Constructors

| Constructor | Description |
| --- | --- |
| [GeometryFunc()](#GeometryFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [absAngleBetweenTwoVectors(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt)](#absAngleBetweenTwoVectors-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculates absolute angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2))) |
| [absAngleBetweenTwoVectors(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt)](#absAngleBetweenTwoVectors-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calculates absolute angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2))) |
| [absPointFsToLineDistance(List<System.Drawing.PointF> aPoints, LineCoefs aLine)](#absPointFsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.PointF--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [absPointToLineDistance(System.Drawing.Point aPoint, LineCoefs aLine)](#absPointToLineDistance-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | Calculate unsigned distance from current point to line |
| [absPointToLineDistance(System.Drawing.PointF aPoint, LineCoefs aLine)](#absPointToLineDistance-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | Calculate unsigned distance from current point to line |
| [absPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)](#absPointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [angleBetweenTwoVectors(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt)](#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculates angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2))) |
| [angleBetweenTwoVectors(System.Drawing.Point aFirstStartPt, System.Drawing.Point aFirstEndPt, System.Drawing.Point aSecondStartPt, System.Drawing.Point aSecondEndPt)](#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculates absolute angle value between two vectors http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2))) |
| [angleBetweenTwoVectors(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt)](#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calculates angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2))) |
| [angleBetweenTwoVectors(System.Drawing.PointF aFirstStartPt, System.Drawing.PointF aFirstEndPt, System.Drawing.PointF aSecondStartPt, System.Drawing.PointF aSecondEndPt)](#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calculates absolute angle value between two vectors http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2))) |
| [avgAbsPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)](#avgAbsPointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [calculateDistance(System.Drawing.Point p1, System.Drawing.Point p2)](#calculateDistance-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculates a distance between 2 points |
| [calculateDistance(System.Drawing.PointF p1, System.Drawing.PointF p2)](#calculateDistance-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calculates a distance between 2 points |
| [checkSegmentWithQuadIntersection(DoublePoints aSegment, QuadPoints aQuad, double aMaxShift)](#checkSegmentWithQuadIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-double-) | Checks is segment(line) intersect quad |
| [checkSegmentsIntersection(DoublePoints SegmentF, DoublePoints SegmentS)](#checkSegmentsIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-) | Checks inersection distance between two segments(0) or max distance between parallel segments |
| [clockWiseInPCCoordAngleDir(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt)](#clockWiseInPCCoordAngleDir-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Function calculate direction of angle rotation in PC coordinates where Y coord grows down |
| [clockWiseInPCCoordAngleDir(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt)](#clockWiseInPCCoordAngleDir-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Function calculate direction of angle rotation in PC coordinates where Y coord grows down |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findMostDistantPointsFromList(List<System.Drawing.Point> aPointList)](#findMostDistantPointsFromList-java.util.List-com.aspose.ms.System.Drawing.Point--) | Calculates most distant points from the list of points on the same line O(N) complexity |
| [getAbsAngleBetweenLinesWithAngles(double FirstAngle, double SecondAngle)](#getAbsAngleBetweenLinesWithAngles-double-double-) | Calculate Abs intersect angle between lines with angles http://pipec8.narod.ru/mat/vec/11.htm L1: y=k1x+b1 L2: y=k2x+b2 tga=tg(a2-a1)=(k2-k1)/(1+k2\*k1) |
| [getAngleBetweenLinesWithAngles(double FirstAngle, double SecondAngle)](#getAngleBetweenLinesWithAngles-double-double-) | Calculate intersect angle between lines with angles http://pipec8.narod.ru/mat/vec/11.htm L1: y=k1x+b1 L2: y=k2x+b2 tga=tg(a2-a1)=(k2-k1)/(1+k2\*k1) |
| [getAugmentedPoint(LineCoefs aLine, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF TestingOppositePoint, boolean isCloserToTesting)](#getAugmentedPoint-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) |  |
| [getAugmentedPoint(double aAngle, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF TestingOppositePoint, boolean isCloserToTesting)](#getAugmentedPoint-double-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) |  |
| [getAugmentedPointClockWise(LineCoefs aLine, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF IntersectLinePoint, boolean isClockWise)](#getAugmentedPointClockWise-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) | Function calculates augmented point from the line |
| [getAugmentedPointClockWise(double aAngle, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF IntersectLinePoint, boolean isClockWise)](#getAugmentedPointClockWise-double-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) | Function calculates augmented point from the line |
| [getBalancedQuad(DoublePointFs StartPoints, DoublePointFs EndPoints)](#getBalancedQuad-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-) | Creates balanced Quad form the start and stop points list with correct or incorrect order |
| [getBalancedQuad(DoublePoints StartPoints, DoublePoints EndPoints)](#getBalancedQuad-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-) | Creates balanced Quad form the start and stop points list with correct or incorrect order |
| [getBiggestQuad(QuadPoints aFirst, QuadPoints aSecond)](#getBiggestQuad-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) | Get biggest quad by the area |
| [getCentralPointByCentroid(List aList)](#getCentralPointByCentroid-java.util.List-) |  |
| [getClass()](#getClass--) |  |
| [getHeightPointToLine(System.Drawing.Point aFrom, LineCoefs aLine)](#getHeightPointToLine-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [getHeightPointToLine(System.Drawing.PointF aFrom, LineCoefs aLine)](#getHeightPointToLine-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | Function calculates point where height(shortest distance) from the aFrom point intersects Line |
| [getNextPointOnPiece(double aRad, LineCoefs aLine, System.Drawing.Point aFrom, System.Drawing.Point aSecond, boolean aOutline)](#getNextPointOnPiece-double-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-boolean-) |  |
| [getNextPointOnPiece(double aRad, LineCoefs aLine, System.Drawing.PointF aFrom, System.Drawing.PointF aSecond, boolean aOutline)](#getNextPointOnPiece-double-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) | dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY); |
| [getNextPointOnPiece(double aRad, System.Drawing.PointF aFrom, System.Drawing.PointF aSecond, boolean aOutline)](#getNextPointOnPiece-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) | dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY); |
| [getNextPointsFromCurrent(double aRad, LineCoefs aLine, System.Drawing.PointF aFrom)](#getNextPointsFromCurrent-double-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.PointF-) | dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY); |
| [getNextPointsFromCurrent(double aRad, double aAngle, System.Drawing.PointF aFrom)](#getNextPointsFromCurrent-double-double-com.aspose.ms.System.Drawing.PointF-) | dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY); |
| [getOppositeTriangleSide(double FirstSide, double SecondSide, double Angle)](#getOppositeTriangleSide-double-double-double-) |  |
| [getProjectedLine(System.Drawing.Point FirstLinePoint, System.Drawing.Point SecondLinePoint, System.Drawing.Point[] ProjPts)](#getProjectedLine-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point---) | Project points on line. |
| [hashCode()](#hashCode--) |  |
| [isAnyPointOfQuadInsideOther(QuadPoints CheckedQuad, QuadPoints aQuad)](#isAnyPointOfQuadInsideOther-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) | Checks is any point of the quad inside this |
| [isPointInsideQuadPoints(QuadPointFs aQuad, System.Drawing.PointF CheckedPoint)](#isPointInsideQuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.ms.System.Drawing.PointF-) | Function checks if point is inside convex quad. |
| [isPointInsideQuadPoints(QuadPoints aQuad, System.Drawing.Point CheckedPoint)](#isPointInsideQuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.ms.System.Drawing.Point-) | Function checks if point is inside convex quad. |
| [isPointInsideTriangle(System.Drawing.Point Vertex1, System.Drawing.Point Vertex2, System.Drawing.Point Vertex3, System.Drawing.Point CheckedPoint)](#isPointInsideTriangle-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Function checks if point is inside triangle |
| [isPointInsideTriangle(System.Drawing.PointF Vertex1, System.Drawing.PointF Vertex2, System.Drawing.PointF Vertex3, System.Drawing.PointF CheckedPoint)](#isPointInsideTriangle-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Function checks if point is inside triangle |
| [isQuadIntersectOrConsistOtherQuad(QuadPoints First, QuadPoints Second, double aMaxShift)](#isQuadIntersectOrConsistOtherQuad-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-double-) | Checks is two quads intersected or touched one to other |
| [lineAnglesDifference(double aFAngle, double aSAngle)](#lineAnglesDifference-double-double-) |  |
| [lineEquationData(System.Drawing.Point aFrom, System.Drawing.Point aTo, double[] aK, double[] aB)](#lineEquationData-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-double---double---) | Calculate line equation in slope form http://en.wikipedia.org/wiki/Linear\_equation y = k\*x + b; |
| [lineEquationData(System.Drawing.PointF aFrom, System.Drawing.PointF aTo, double[] aK, double[] aB)](#lineEquationData-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double---double---) | Calculate line equation in slope form http://en.wikipedia.org/wiki/Linear\_equation y = k\*x + b; |
| [lineFromAngleAndPoint(double aAngle, System.Drawing.Point aPoint)](#lineFromAngleAndPoint-double-com.aspose.ms.System.Drawing.Point-) |  |
| [lineFromAngleAndPoint(double aAngle, System.Drawing.PointF aPoint)](#lineFromAngleAndPoint-double-com.aspose.ms.System.Drawing.PointF-) |  |
| [lineLength(System.Drawing.Point aFrom, System.Drawing.Point aTo)](#lineLength-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculate line length between two point |
| [lineLength(System.Drawing.PointF aFrom, System.Drawing.PointF aTo)](#lineLength-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calculate line length between two point |
| [linePerpendicularFromPoint(double aAngle, System.Drawing.Point aPoint)](#linePerpendicularFromPoint-double-com.aspose.ms.System.Drawing.Point-) |  |
| [linePerpendicularFromPoint(double aAngle, System.Drawing.PointF aPoint)](#linePerpendicularFromPoint-double-com.aspose.ms.System.Drawing.PointF-) |  |
| [linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine)](#linesIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | From G.Korn, T.Korn http://sci-lib.com/book000575.html Px = (b1-b2)/(k2 - k1); Py = (k2\*b1 - k1\*b2)/(k2 - k1); |
| [linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine, System.Drawing.Point aDef)](#linesIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.Point-) | Return point of the intersection |
| [linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine, System.Drawing.PointF aDef)](#linesIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.PointF-) | Return point of the intersection |
| [linesIntersection(System.Drawing.Point a1, System.Drawing.Point a2, System.Drawing.Point b1, System.Drawing.Point b2)](#linesIntersection-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculate a point of lines intersection. |
| [linesIntersection(System.Drawing.Point a1, System.Drawing.Point a2, System.Drawing.Point b1, System.Drawing.Point b2, System.Drawing.Point aDef)](#linesIntersection-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Calculate a point of lines intersection. |
| [linesIntersection(System.Drawing.PointF a1, System.Drawing.PointF a2, System.Drawing.PointF b1, System.Drawing.PointF b2, System.Drawing.PointF aDef)](#linesIntersection-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calculate a point of lines intersection. |
| [manhattanDistanceBetweenPoints(System.Drawing.PointF a, System.Drawing.PointF b)](#manhattanDistanceBetweenPoints-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Calucalte distance between two point in Manhattan metrics (taxicab distance). |
| [maxAbsPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)](#maxAbsPointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [mergeRectangles(System.Drawing.Rectangle first, System.Drawing.Rectangle second)](#mergeRectangles-com.aspose.ms.System.Drawing.Rectangle-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [minDistanceBetweenTwoPieces(System.Drawing.Point A1, System.Drawing.Point A2, System.Drawing.Point B1, System.Drawing.Point B2)](#minDistanceBetweenTwoPieces-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [minDistanceBetweenTwoPieces(System.Drawing.PointF A1, System.Drawing.PointF A2, System.Drawing.PointF B1, System.Drawing.PointF B2)](#minDistanceBetweenTwoPieces-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [perpendicularAngle(double aAngle)](#perpendicularAngle-double-) |  |
| [pointDistanceToPiece(System.Drawing.Point aAPoint, System.Drawing.Point A1, System.Drawing.Point A2)](#pointDistanceToPiece-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [pointDistanceToPiece(System.Drawing.PointF aAPoint, System.Drawing.PointF A1, System.Drawing.PointF A2)](#pointDistanceToPiece-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [pointFsToLineDistance(List<System.Drawing.PointF> aPointFs, LineCoefs aLine)](#pointFsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.PointF--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [pointToLineDistance(System.Drawing.Point aPoint, LineCoefs aLine)](#pointToLineDistance-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | Calculate distance from current point to line |
| [pointToLineDistance(System.Drawing.PointF aPoint, LineCoefs aLine)](#pointToLineDistance-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | Calculate distance from current point to line |
| [pointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)](#pointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [ptFToPt(System.Drawing.PointF aPoint)](#ptFToPt-com.aspose.ms.System.Drawing.PointF-) |  |
| [ptToPtF(System.Drawing.Point aPoint)](#ptToPtF-com.aspose.ms.System.Drawing.Point-) |  |
| [quadArea(QuadPointFs aQuad)](#quadArea-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-) |  |
| [quadArea(QuadPoints aQuad)](#quadArea-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) |  |
| [rotatePoint(System.Drawing.PointF aPoint, System.Drawing.PointF aCentralPoint, double aAngle, boolean aClockwise)](#rotatePoint-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-boolean-) |  |
| [rotatePointList(List<System.Drawing.PointF> aList, System.Drawing.PointF aCentralPoint, double aAngle, boolean aClockwise)](#rotatePointList-java.util.List-com.aspose.ms.System.Drawing.PointF--com.aspose.ms.System.Drawing.PointF-double-boolean-) |  |
| [rotateQuad(System.Drawing.PointF centralPoint, QuadPointFs quadPointFs, double angle, boolean clockwise)](#rotateQuad-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-double-boolean-) |  |
| [toString()](#toString--) |  |
| [triangleArea(System.Drawing.Point aA, System.Drawing.Point aB, System.Drawing.Point aC)](#triangleArea-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [triangleArea(System.Drawing.PointF aA, System.Drawing.PointF aB, System.Drawing.PointF aC)](#triangleArea-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | http://en.wikipedia.org/wiki/Triangle |
| [triangleHeight(System.Drawing.Point aA, System.Drawing.Point aB, System.Drawing.Point aC)](#triangleHeight-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | h\_base = (2A)/base where A - is a area of a triangle base - a length of AC B is a point from where the height is outing. |
| [triangleHeight(System.Drawing.PointF aA, System.Drawing.PointF aB, System.Drawing.PointF aC)](#triangleHeight-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | h\_base = (2A)/base where A - is a area of a triangle base - a length of AC B is a point from where the height is outing. |
| [twoLineMinIntersectAngle(LineCoefs aFirstLine, LineCoefs aSecondLine)](#twoLineMinIntersectAngle-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) | Intersection between two lines have two angles. |
| [twoPiecesSameDirrectionMatching(System.Drawing.Point A1, System.Drawing.Point A2, System.Drawing.Point B1, System.Drawing.Point B2, double aVertShift)](#twoPiecesSameDirrectionMatching-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-double-) |  |
| [twoPiecesSameDirrectionMatching(System.Drawing.PointF A1, System.Drawing.PointF A2, System.Drawing.PointF B1, System.Drawing.PointF B2, double aVertShift)](#twoPiecesSameDirrectionMatching-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GeometryFunc() {#GeometryFunc--}
```
public GeometryFunc()
```


### absAngleBetweenTwoVectors(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt) {#absAngleBetweenTwoVectors-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double absAngleBetweenTwoVectors(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt)
```


Calculates absolute angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2)))

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVertexPt | com.aspose.ms.System.Drawing.Point | Vertex point |
| aFirstSidePt | com.aspose.ms.System.Drawing.Point | First side of the angle |
| aSecondSidePt | com.aspose.ms.System.Drawing.Point | Second side of the angle |

**Returns:**
double - Value of the angle in rads
### absAngleBetweenTwoVectors(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt) {#absAngleBetweenTwoVectors-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double absAngleBetweenTwoVectors(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt)
```


Calculates absolute angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2)))

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVertexPt | com.aspose.ms.System.Drawing.PointF | Vertex point |
| aFirstSidePt | com.aspose.ms.System.Drawing.PointF | First side of the angle |
| aSecondSidePt | com.aspose.ms.System.Drawing.PointF | Second side of the angle |

**Returns:**
double - Value of the angle in rads
### absPointFsToLineDistance(List<System.Drawing.PointF> aPoints, LineCoefs aLine) {#absPointFsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.PointF--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static List<Double> absPointFsToLineDistance(List<System.Drawing.PointF> aPoints, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoints | java.util.List<com.aspose.ms.System.Drawing.PointF> |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
[List](../../java.util/list)
### absPointToLineDistance(System.Drawing.Point aPoint, LineCoefs aLine) {#absPointToLineDistance-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double absPointToLineDistance(System.Drawing.Point aPoint, LineCoefs aLine)
```


Calculate unsigned distance from current point to line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.Point | point |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Line variable |

**Returns:**
double - distance to line
### absPointToLineDistance(System.Drawing.PointF aPoint, LineCoefs aLine) {#absPointToLineDistance-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double absPointToLineDistance(System.Drawing.PointF aPoint, LineCoefs aLine)
```


Calculate unsigned distance from current point to line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.PointF | point |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Line variable |

**Returns:**
double - distance to line
### absPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine) {#absPointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static List<Double> absPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoints | java.util.List<com.aspose.ms.System.Drawing.Point> |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
[List](../../java.util/list)
### angleBetweenTwoVectors(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt) {#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double angleBetweenTwoVectors(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt)
```


Calculates angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2)))

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVertexPt | com.aspose.ms.System.Drawing.Point | Vertex point |
| aFirstSidePt | com.aspose.ms.System.Drawing.Point | First side of the angle |
| aSecondSidePt | com.aspose.ms.System.Drawing.Point | Second side of the angle |

**Returns:**
double - Value of the angle in rads
### angleBetweenTwoVectors(System.Drawing.Point aFirstStartPt, System.Drawing.Point aFirstEndPt, System.Drawing.Point aSecondStartPt, System.Drawing.Point aSecondEndPt) {#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double angleBetweenTwoVectors(System.Drawing.Point aFirstStartPt, System.Drawing.Point aFirstEndPt, System.Drawing.Point aSecondStartPt, System.Drawing.Point aSecondEndPt)
```


Calculates absolute angle value between two vectors http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2)))

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirstStartPt | com.aspose.ms.System.Drawing.Point | Start point of the first vector |
| aFirstEndPt | com.aspose.ms.System.Drawing.Point | End point of the first vector |
| aSecondStartPt | com.aspose.ms.System.Drawing.Point | Start point of the second vector |
| aSecondEndPt | com.aspose.ms.System.Drawing.Point | End point of the second vector |

**Returns:**
double - Value of the angle in rads
### angleBetweenTwoVectors(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt) {#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double angleBetweenTwoVectors(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt)
```


Calculates angle value where aVertexPt is vertex point and aFirstSidePt, aSecondSidePt are other sides of the angle http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2)))

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVertexPt | com.aspose.ms.System.Drawing.PointF | Vertex point |
| aFirstSidePt | com.aspose.ms.System.Drawing.PointF | First side of the angle |
| aSecondSidePt | com.aspose.ms.System.Drawing.PointF | Second side of the angle |

**Returns:**
double - Value of the angle in rads
### angleBetweenTwoVectors(System.Drawing.PointF aFirstStartPt, System.Drawing.PointF aFirstEndPt, System.Drawing.PointF aSecondStartPt, System.Drawing.PointF aSecondEndPt) {#angleBetweenTwoVectors-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double angleBetweenTwoVectors(System.Drawing.PointF aFirstStartPt, System.Drawing.PointF aFirstEndPt, System.Drawing.PointF aSecondStartPt, System.Drawing.PointF aSecondEndPt)
```


Calculates absolute angle value between two vectors http://en.wikipedia.org/wiki/Angle angle = arcos((x1\*x2+y1\*y2)/(sqrt(x1^2+y1^2)\*sqrt(x2^2+y2^2)))

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirstStartPt | com.aspose.ms.System.Drawing.PointF | Start point of the first vector |
| aFirstEndPt | com.aspose.ms.System.Drawing.PointF | End point of the first vector |
| aSecondStartPt | com.aspose.ms.System.Drawing.PointF | Start point of the second vector |
| aSecondEndPt | com.aspose.ms.System.Drawing.PointF | End point of the second vector |

**Returns:**
double - Value of the angle in rads
### avgAbsPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine) {#avgAbsPointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double avgAbsPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoints | java.util.List<com.aspose.ms.System.Drawing.Point> |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
double
### calculateDistance(System.Drawing.Point p1, System.Drawing.Point p2) {#calculateDistance-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static float calculateDistance(System.Drawing.Point p1, System.Drawing.Point p2)
```


Calculates a distance between 2 points

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p1 | com.aspose.ms.System.Drawing.Point |  |
| p2 | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
float - 
### calculateDistance(System.Drawing.PointF p1, System.Drawing.PointF p2) {#calculateDistance-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static float calculateDistance(System.Drawing.PointF p1, System.Drawing.PointF p2)
```


Calculates a distance between 2 points

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p1 | com.aspose.ms.System.Drawing.PointF |  |
| p2 | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
float - 
### checkSegmentWithQuadIntersection(DoublePoints aSegment, QuadPoints aQuad, double aMaxShift) {#checkSegmentWithQuadIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-double-}
```
public static boolean checkSegmentWithQuadIntersection(DoublePoints aSegment, QuadPoints aQuad, double aMaxShift)
```


Checks is segment(line) intersect quad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegment | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) |  |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aMaxShift | double | max distance between two quads |

**Returns:**
boolean - return state is segment(line) intersect quad
### checkSegmentsIntersection(DoublePoints SegmentF, DoublePoints SegmentS) {#checkSegmentsIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-}
```
public static double checkSegmentsIntersection(DoublePoints SegmentF, DoublePoints SegmentS)
```


Checks inersection distance between two segments(0) or max distance between parallel segments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SegmentF | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) |  |
| SegmentS | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) |  |

**Returns:**
double - return distance
### clockWiseInPCCoordAngleDir(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt) {#clockWiseInPCCoordAngleDir-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static boolean clockWiseInPCCoordAngleDir(System.Drawing.Point aVertexPt, System.Drawing.Point aFirstSidePt, System.Drawing.Point aSecondSidePt)
```


Function calculate direction of angle rotation in PC coordinates where Y coord grows down

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVertexPt | com.aspose.ms.System.Drawing.Point | Vertex point |
| aFirstSidePt | com.aspose.ms.System.Drawing.Point | Point from which we rotate |
| aSecondSidePt | com.aspose.ms.System.Drawing.Point | Point To which we rotate |

**Returns:**
boolean - clockwise rotation in PC coordinates where Y coord grows down
### clockWiseInPCCoordAngleDir(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt) {#clockWiseInPCCoordAngleDir-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static boolean clockWiseInPCCoordAngleDir(System.Drawing.PointF aVertexPt, System.Drawing.PointF aFirstSidePt, System.Drawing.PointF aSecondSidePt)
```


Function calculate direction of angle rotation in PC coordinates where Y coord grows down

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVertexPt | com.aspose.ms.System.Drawing.PointF | Vertex point |
| aFirstSidePt | com.aspose.ms.System.Drawing.PointF | Point from which we rotate |
| aSecondSidePt | com.aspose.ms.System.Drawing.PointF | Point To which we rotate |

**Returns:**
boolean - clockwise rotation in PC coordinates where Y coord grows down
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findMostDistantPointsFromList(List<System.Drawing.Point> aPointList) {#findMostDistantPointsFromList-java.util.List-com.aspose.ms.System.Drawing.Point--}
```
public static DoublePoints findMostDistantPointsFromList(List<System.Drawing.Point> aPointList)
```


Calculates most distant points from the list of points on the same line O(N) complexity

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPointList | java.util.List<com.aspose.ms.System.Drawing.Point> |  |

**Returns:**
[DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) - Most distant points
### getAbsAngleBetweenLinesWithAngles(double FirstAngle, double SecondAngle) {#getAbsAngleBetweenLinesWithAngles-double-double-}
```
public static double getAbsAngleBetweenLinesWithAngles(double FirstAngle, double SecondAngle)
```


Calculate Abs intersect angle between lines with angles http://pipec8.narod.ru/mat/vec/11.htm L1: y=k1x+b1 L2: y=k2x+b2 tga=tg(a2-a1)=(k2-k1)/(1+k2\*k1)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| FirstAngle | double | First angle |
| SecondAngle | double | SecondAngle |

**Returns:**
double - the length of line
### getAngleBetweenLinesWithAngles(double FirstAngle, double SecondAngle) {#getAngleBetweenLinesWithAngles-double-double-}
```
public static double getAngleBetweenLinesWithAngles(double FirstAngle, double SecondAngle)
```


Calculate intersect angle between lines with angles http://pipec8.narod.ru/mat/vec/11.htm L1: y=k1x+b1 L2: y=k2x+b2 tga=tg(a2-a1)=(k2-k1)/(1+k2\*k1)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| FirstAngle | double | First angle |
| SecondAngle | double | SecondAngle |

**Returns:**
double - the length of line
### getAugmentedPoint(LineCoefs aLine, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF TestingOppositePoint, boolean isCloserToTesting) {#getAugmentedPoint-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getAugmentedPoint(LineCoefs aLine, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF TestingOppositePoint, boolean isCloserToTesting)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| aRad | double |  |
| ProlongedPoint | com.aspose.ms.System.Drawing.PointF |  |
| TestingOppositePoint | com.aspose.ms.System.Drawing.PointF |  |
| isCloserToTesting | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getAugmentedPoint(double aAngle, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF TestingOppositePoint, boolean isCloserToTesting) {#getAugmentedPoint-double-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getAugmentedPoint(double aAngle, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF TestingOppositePoint, boolean isCloserToTesting)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double |  |
| aRad | double |  |
| ProlongedPoint | com.aspose.ms.System.Drawing.PointF |  |
| TestingOppositePoint | com.aspose.ms.System.Drawing.PointF |  |
| isCloserToTesting | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getAugmentedPointClockWise(LineCoefs aLine, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF IntersectLinePoint, boolean isClockWise) {#getAugmentedPointClockWise-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getAugmentedPointClockWise(LineCoefs aLine, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF IntersectLinePoint, boolean isClockWise)
```


Function calculates augmented point from the line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | The line coeficients |
| aRad | double | prolonged distance |
| ProlongedPoint | com.aspose.ms.System.Drawing.PointF | point on line |
| IntersectLinePoint | com.aspose.ms.System.Drawing.PointF |  |
| isClockWise | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF - augmented point
### getAugmentedPointClockWise(double aAngle, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF IntersectLinePoint, boolean isClockWise) {#getAugmentedPointClockWise-double-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getAugmentedPointClockWise(double aAngle, double aRad, System.Drawing.PointF ProlongedPoint, System.Drawing.PointF IntersectLinePoint, boolean isClockWise)
```


Function calculates augmented point from the line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double | prolonged line |
| aRad | double | prolonged distance |
| ProlongedPoint | com.aspose.ms.System.Drawing.PointF | point on line |
| IntersectLinePoint | com.aspose.ms.System.Drawing.PointF |  |
| isClockWise | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF - augmented point
### getBalancedQuad(DoublePointFs StartPoints, DoublePointFs EndPoints) {#getBalancedQuad-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-}
```
public static QuadPointFs getBalancedQuad(DoublePointFs StartPoints, DoublePointFs EndPoints)
```


Creates balanced Quad form the start and stop points list with correct or incorrect order

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| StartPoints | [DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) | start points of the quad |
| EndPoints | [DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) | end points of the quad |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) - Quad of barcode area
### getBalancedQuad(DoublePoints StartPoints, DoublePoints EndPoints) {#getBalancedQuad-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-}
```
public static QuadPoints getBalancedQuad(DoublePoints StartPoints, DoublePoints EndPoints)
```


Creates balanced Quad form the start and stop points list with correct or incorrect order

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| StartPoints | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) | start points of the quad |
| EndPoints | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) | end points of the quad |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) - Quad of barcode area
### getBiggestQuad(QuadPoints aFirst, QuadPoints aSecond) {#getBiggestQuad-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public static QuadPoints getBiggestQuad(QuadPoints aFirst, QuadPoints aSecond)
```


Get biggest quad by the area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirst | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aSecond | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) - return biggest quad by the area
### getCentralPointByCentroid(List aList) {#getCentralPointByCentroid-java.util.List-}
```
public static PointResult getCentralPointByCentroid(List aList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List |  |

**Returns:**
[PointResult](../../com.aspose.barcode.barcoderecognition.common.algorithms/pointresult)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeightPointToLine(System.Drawing.Point aFrom, LineCoefs aLine) {#getHeightPointToLine-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static System.Drawing.Point getHeightPointToLine(System.Drawing.Point aFrom, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFrom | com.aspose.ms.System.Drawing.Point |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### getHeightPointToLine(System.Drawing.PointF aFrom, LineCoefs aLine) {#getHeightPointToLine-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static System.Drawing.PointF getHeightPointToLine(System.Drawing.PointF aFrom, LineCoefs aLine)
```


Function calculates point where height(shortest distance) from the aFrom point intersects Line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFrom | com.aspose.ms.System.Drawing.PointF | Point from which we create height |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Line to which we create height |

**Returns:**
com.aspose.ms.System.Drawing.PointF - Point where height from aFrom intersect line aLine
### getNextPointOnPiece(double aRad, LineCoefs aLine, System.Drawing.Point aFrom, System.Drawing.Point aSecond, boolean aOutline) {#getNextPointOnPiece-double-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-boolean-}
```
public static System.Drawing.Point getNextPointOnPiece(double aRad, LineCoefs aLine, System.Drawing.Point aFrom, System.Drawing.Point aSecond, boolean aOutline)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRad | double |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| aFrom | com.aspose.ms.System.Drawing.Point |  |
| aSecond | com.aspose.ms.System.Drawing.Point |  |
| aOutline | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### getNextPointOnPiece(double aRad, LineCoefs aLine, System.Drawing.PointF aFrom, System.Drawing.PointF aSecond, boolean aOutline) {#getNextPointOnPiece-double-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getNextPointOnPiece(double aRad, LineCoefs aLine, System.Drawing.PointF aFrom, System.Drawing.PointF aSecond, boolean aOutline)
```


dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRad | double | distance from the aFrom point, must be positive |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | The line coeficients |
| aFrom | com.aspose.ms.System.Drawing.PointF | The point from which we prologn new point |
| aSecond | com.aspose.ms.System.Drawing.PointF | the second point on the piece |
| aOutline | boolean | true the result outside the piece, false the result inside |

**Returns:**
com.aspose.ms.System.Drawing.PointF - the resulted point
### getNextPointOnPiece(double aRad, System.Drawing.PointF aFrom, System.Drawing.PointF aSecond, boolean aOutline) {#getNextPointOnPiece-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getNextPointOnPiece(double aRad, System.Drawing.PointF aFrom, System.Drawing.PointF aSecond, boolean aOutline)
```


dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRad | double | distance from the aFrom point, must be positive |
| aFrom | com.aspose.ms.System.Drawing.PointF | The point from which we prologn new point |
| aSecond | com.aspose.ms.System.Drawing.PointF | the second point on the piece |
| aOutline | boolean | true the result outside the piece, false the result inside |

**Returns:**
com.aspose.ms.System.Drawing.PointF - the resulted point
### getNextPointsFromCurrent(double aRad, LineCoefs aLine, System.Drawing.PointF aFrom) {#getNextPointsFromCurrent-double-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.PointF-}
```
public static DoublePointFs getNextPointsFromCurrent(double aRad, LineCoefs aLine, System.Drawing.PointF aFrom)
```


dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRad | double | distance from the aFrom point, must be positive |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | The line coeficients |
| aFrom | com.aspose.ms.System.Drawing.PointF | The point from which we prologn new point |

**Returns:**
[DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) - DoublePoints
### getNextPointsFromCurrent(double aRad, double aAngle, System.Drawing.PointF aFrom) {#getNextPointsFromCurrent-double-double-com.aspose.ms.System.Drawing.PointF-}
```
public static DoublePointFs getNextPointsFromCurrent(double aRad, double aAngle, System.Drawing.PointF aFrom)
```


dy = -+sqrt(R^2 / (1 + tg(min angle fromY)^2)) dx = dy \* tg(min angle fromY);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRad | double | distance from the aFrom point, must be positive |
| aAngle | double | the line angle |
| aFrom | com.aspose.ms.System.Drawing.PointF | The point from which we prologn new point |

**Returns:**
[DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) - DoublePoints
### getOppositeTriangleSide(double FirstSide, double SecondSide, double Angle) {#getOppositeTriangleSide-double-double-double-}
```
public static double getOppositeTriangleSide(double FirstSide, double SecondSide, double Angle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| FirstSide | double |  |
| SecondSide | double |  |
| Angle | double |  |

**Returns:**
double
### getProjectedLine(System.Drawing.Point FirstLinePoint, System.Drawing.Point SecondLinePoint, System.Drawing.Point[] ProjPts) {#getProjectedLine-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point---}
```
public static DoublePoints getProjectedLine(System.Drawing.Point FirstLinePoint, System.Drawing.Point SecondLinePoint, System.Drawing.Point[] ProjPts)
```


Project points on line. If new points extend the nine, extended line is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| FirstLinePoint | com.aspose.ms.System.Drawing.Point | First Point of line |
| SecondLinePoint | com.aspose.ms.System.Drawing.Point | Second Point of line |
| ProjPts | com.aspose.ms.System.Drawing.Point[] | List of point which must be projected |

**Returns:**
[DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) - two point of new line
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAnyPointOfQuadInsideOther(QuadPoints CheckedQuad, QuadPoints aQuad) {#isAnyPointOfQuadInsideOther-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public static boolean isAnyPointOfQuadInsideOther(QuadPoints CheckedQuad, QuadPoints aQuad)
```


Checks is any point of the quad inside this

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| CheckedQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |

**Returns:**
boolean - return state is any point of the quad inside this
### isPointInsideQuadPoints(QuadPointFs aQuad, System.Drawing.PointF CheckedPoint) {#isPointInsideQuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.ms.System.Drawing.PointF-}
```
public static boolean isPointInsideQuadPoints(QuadPointFs aQuad, System.Drawing.PointF CheckedPoint)
```


Function checks if point is inside convex quad. Will not work if quad isn't convex

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | Quad which we check |
| CheckedPoint | com.aspose.ms.System.Drawing.PointF | Checked point |

**Returns:**
boolean - if true, point inside convex quad
### isPointInsideQuadPoints(QuadPoints aQuad, System.Drawing.Point CheckedPoint) {#isPointInsideQuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.ms.System.Drawing.Point-}
```
public static boolean isPointInsideQuadPoints(QuadPoints aQuad, System.Drawing.Point CheckedPoint)
```


Function checks if point is inside convex quad. Will not work if quad isn't convex

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | Quad which we check |
| CheckedPoint | com.aspose.ms.System.Drawing.Point | Checked point |

**Returns:**
boolean - if true, point inside convex quad
### isPointInsideTriangle(System.Drawing.Point Vertex1, System.Drawing.Point Vertex2, System.Drawing.Point Vertex3, System.Drawing.Point CheckedPoint) {#isPointInsideTriangle-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static boolean isPointInsideTriangle(System.Drawing.Point Vertex1, System.Drawing.Point Vertex2, System.Drawing.Point Vertex3, System.Drawing.Point CheckedPoint)
```


Function checks if point is inside triangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Vertex1 | com.aspose.ms.System.Drawing.Point | First triangle vertex |
| Vertex2 | com.aspose.ms.System.Drawing.Point | Second triangle vertex |
| Vertex3 | com.aspose.ms.System.Drawing.Point | Third triangle vertex |
| CheckedPoint | com.aspose.ms.System.Drawing.Point | Checked point |

**Returns:**
boolean - if true, point inside triangle
### isPointInsideTriangle(System.Drawing.PointF Vertex1, System.Drawing.PointF Vertex2, System.Drawing.PointF Vertex3, System.Drawing.PointF CheckedPoint) {#isPointInsideTriangle-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static boolean isPointInsideTriangle(System.Drawing.PointF Vertex1, System.Drawing.PointF Vertex2, System.Drawing.PointF Vertex3, System.Drawing.PointF CheckedPoint)
```


Function checks if point is inside triangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Vertex1 | com.aspose.ms.System.Drawing.PointF | First triangle vertex |
| Vertex2 | com.aspose.ms.System.Drawing.PointF | Second triangle vertex |
| Vertex3 | com.aspose.ms.System.Drawing.PointF | Third triangle vertex |
| CheckedPoint | com.aspose.ms.System.Drawing.PointF | Checked point |

**Returns:**
boolean - if true, point inside triangle
### isQuadIntersectOrConsistOtherQuad(QuadPoints First, QuadPoints Second, double aMaxShift) {#isQuadIntersectOrConsistOtherQuad-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-double-}
```
public static boolean isQuadIntersectOrConsistOtherQuad(QuadPoints First, QuadPoints Second, double aMaxShift)
```


Checks is two quads intersected or touched one to other

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| First | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| Second | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aMaxShift | double | max distance between two quads |

**Returns:**
boolean - return state is two quads intersected or touched one to other
### lineAnglesDifference(double aFAngle, double aSAngle) {#lineAnglesDifference-double-double-}
```
public static double lineAnglesDifference(double aFAngle, double aSAngle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFAngle | double |  |
| aSAngle | double |  |

**Returns:**
double
### lineEquationData(System.Drawing.Point aFrom, System.Drawing.Point aTo, double[] aK, double[] aB) {#lineEquationData-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-double---double---}
```
public static void lineEquationData(System.Drawing.Point aFrom, System.Drawing.Point aTo, double[] aK, double[] aB)
```


Calculate line equation in slope form http://en.wikipedia.org/wiki/Linear\_equation y = k\*x + b;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFrom | com.aspose.ms.System.Drawing.Point | Start point |
| aTo | com.aspose.ms.System.Drawing.Point | End point |
| aK | double[] | k - variable |
| aB | double[] | b - variable |

### lineEquationData(System.Drawing.PointF aFrom, System.Drawing.PointF aTo, double[] aK, double[] aB) {#lineEquationData-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double---double---}
```
public static void lineEquationData(System.Drawing.PointF aFrom, System.Drawing.PointF aTo, double[] aK, double[] aB)
```


Calculate line equation in slope form http://en.wikipedia.org/wiki/Linear\_equation y = k\*x + b;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFrom | com.aspose.ms.System.Drawing.PointF | Start point |
| aTo | com.aspose.ms.System.Drawing.PointF | End point |
| aK | double[] | k - variable |
| aB | double[] | b - variable |

### lineFromAngleAndPoint(double aAngle, System.Drawing.Point aPoint) {#lineFromAngleAndPoint-double-com.aspose.ms.System.Drawing.Point-}
```
public static LineCoefs lineFromAngleAndPoint(double aAngle, System.Drawing.Point aPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double |  |
| aPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
[LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs)
### lineFromAngleAndPoint(double aAngle, System.Drawing.PointF aPoint) {#lineFromAngleAndPoint-double-com.aspose.ms.System.Drawing.PointF-}
```
public static LineCoefs lineFromAngleAndPoint(double aAngle, System.Drawing.PointF aPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double |  |
| aPoint | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
[LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs)
### lineLength(System.Drawing.Point aFrom, System.Drawing.Point aTo) {#lineLength-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double lineLength(System.Drawing.Point aFrom, System.Drawing.Point aTo)
```


Calculate line length between two point

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFrom | com.aspose.ms.System.Drawing.Point | Start point |
| aTo | com.aspose.ms.System.Drawing.Point | End point |

**Returns:**
double - the length of line
### lineLength(System.Drawing.PointF aFrom, System.Drawing.PointF aTo) {#lineLength-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double lineLength(System.Drawing.PointF aFrom, System.Drawing.PointF aTo)
```


Calculate line length between two point

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFrom | com.aspose.ms.System.Drawing.PointF | Start point |
| aTo | com.aspose.ms.System.Drawing.PointF | End point |

**Returns:**
double - the length of line
### linePerpendicularFromPoint(double aAngle, System.Drawing.Point aPoint) {#linePerpendicularFromPoint-double-com.aspose.ms.System.Drawing.Point-}
```
public static LineCoefs linePerpendicularFromPoint(double aAngle, System.Drawing.Point aPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double |  |
| aPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
[LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs)
### linePerpendicularFromPoint(double aAngle, System.Drawing.PointF aPoint) {#linePerpendicularFromPoint-double-com.aspose.ms.System.Drawing.PointF-}
```
public static LineCoefs linePerpendicularFromPoint(double aAngle, System.Drawing.PointF aPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double |  |
| aPoint | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
[LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs)
### linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine) {#linesIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static PointResult linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine)
```


From G.Korn, T.Korn http://sci-lib.com/book000575.html Px = (b1-b2)/(k2 - k1); Py = (k2\*b1 - k1\*b2)/(k2 - k1);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirstLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | First checked line |
| aSecondLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Second checked line |

**Returns:**
[PointResult](../../com.aspose.barcode.barcoderecognition.common.algorithms/pointresult) - intersect point in PointResult or null
### linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine, System.Drawing.Point aDef) {#linesIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.Point-}
```
public static System.Drawing.Point linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine, System.Drawing.Point aDef)
```


Return point of the intersection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirstLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | First checked line |
| aSecondLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Second checked line |
| aDef | com.aspose.ms.System.Drawing.Point | Default point |

**Returns:**
com.aspose.ms.System.Drawing.Point - intersect point or default point
### linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine, System.Drawing.PointF aDef) {#linesIntersection-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.ms.System.Drawing.PointF-}
```
public static System.Drawing.PointF linesIntersection(LineCoefs aFirstLine, LineCoefs aSecondLine, System.Drawing.PointF aDef)
```


Return point of the intersection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirstLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | First checked line |
| aSecondLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Second checked line |
| aDef | com.aspose.ms.System.Drawing.PointF | Default point |

**Returns:**
com.aspose.ms.System.Drawing.PointF - intersect point or default point
### linesIntersection(System.Drawing.Point a1, System.Drawing.Point a2, System.Drawing.Point b1, System.Drawing.Point b2) {#linesIntersection-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static PointResult linesIntersection(System.Drawing.Point a1, System.Drawing.Point a2, System.Drawing.Point b1, System.Drawing.Point b2)
```


Calculate a point of lines intersection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a1 | com.aspose.ms.System.Drawing.Point | first point of line A |
| a2 | com.aspose.ms.System.Drawing.Point | second point of line A |
| b1 | com.aspose.ms.System.Drawing.Point | first point of line B |
| b2 | com.aspose.ms.System.Drawing.Point | second point of line B |

**Returns:**
[PointResult](../../com.aspose.barcode.barcoderecognition.common.algorithms/pointresult) - intersect point in PointResult or null
### linesIntersection(System.Drawing.Point a1, System.Drawing.Point a2, System.Drawing.Point b1, System.Drawing.Point b2, System.Drawing.Point aDef) {#linesIntersection-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static System.Drawing.Point linesIntersection(System.Drawing.Point a1, System.Drawing.Point a2, System.Drawing.Point b1, System.Drawing.Point b2, System.Drawing.Point aDef)
```


Calculate a point of lines intersection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a1 | com.aspose.ms.System.Drawing.Point | first point of line A |
| a2 | com.aspose.ms.System.Drawing.Point | second point of line A |
| b1 | com.aspose.ms.System.Drawing.Point | first point of line B |
| b2 | com.aspose.ms.System.Drawing.Point | second point of line B |
| aDef | com.aspose.ms.System.Drawing.Point | Default point |

**Returns:**
com.aspose.ms.System.Drawing.Point - intersect point or default point
### linesIntersection(System.Drawing.PointF a1, System.Drawing.PointF a2, System.Drawing.PointF b1, System.Drawing.PointF b2, System.Drawing.PointF aDef) {#linesIntersection-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static System.Drawing.PointF linesIntersection(System.Drawing.PointF a1, System.Drawing.PointF a2, System.Drawing.PointF b1, System.Drawing.PointF b2, System.Drawing.PointF aDef)
```


Calculate a point of lines intersection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a1 | com.aspose.ms.System.Drawing.PointF | first point of line A |
| a2 | com.aspose.ms.System.Drawing.PointF | second point of line A |
| b1 | com.aspose.ms.System.Drawing.PointF | first point of line B |
| b2 | com.aspose.ms.System.Drawing.PointF | second point of line B |
| aDef | com.aspose.ms.System.Drawing.PointF | Default point |

**Returns:**
com.aspose.ms.System.Drawing.PointF - intersect point or default point
### manhattanDistanceBetweenPoints(System.Drawing.PointF a, System.Drawing.PointF b) {#manhattanDistanceBetweenPoints-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double manhattanDistanceBetweenPoints(System.Drawing.PointF a, System.Drawing.PointF b)
```


Calucalte distance between two point in Manhattan metrics (taxicab distance).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | com.aspose.ms.System.Drawing.PointF | First point. |
| b | com.aspose.ms.System.Drawing.PointF | Second point. |

**Returns:**
double - The distance between point in Mangattan metrics.
### maxAbsPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine) {#maxAbsPointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double maxAbsPointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoints | java.util.List<com.aspose.ms.System.Drawing.Point> |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
double
### mergeRectangles(System.Drawing.Rectangle first, System.Drawing.Rectangle second) {#mergeRectangles-com.aspose.ms.System.Drawing.Rectangle-com.aspose.ms.System.Drawing.Rectangle-}
```
public static System.Drawing.Rectangle mergeRectangles(System.Drawing.Rectangle first, System.Drawing.Rectangle second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | com.aspose.ms.System.Drawing.Rectangle |  |
| second | com.aspose.ms.System.Drawing.Rectangle |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### minDistanceBetweenTwoPieces(System.Drawing.Point A1, System.Drawing.Point A2, System.Drawing.Point B1, System.Drawing.Point B2) {#minDistanceBetweenTwoPieces-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double minDistanceBetweenTwoPieces(System.Drawing.Point A1, System.Drawing.Point A2, System.Drawing.Point B1, System.Drawing.Point B2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| A1 | com.aspose.ms.System.Drawing.Point |  |
| A2 | com.aspose.ms.System.Drawing.Point |  |
| B1 | com.aspose.ms.System.Drawing.Point |  |
| B2 | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
double
### minDistanceBetweenTwoPieces(System.Drawing.PointF A1, System.Drawing.PointF A2, System.Drawing.PointF B1, System.Drawing.PointF B2) {#minDistanceBetweenTwoPieces-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double minDistanceBetweenTwoPieces(System.Drawing.PointF A1, System.Drawing.PointF A2, System.Drawing.PointF B1, System.Drawing.PointF B2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| A1 | com.aspose.ms.System.Drawing.PointF |  |
| A2 | com.aspose.ms.System.Drawing.PointF |  |
| B1 | com.aspose.ms.System.Drawing.PointF |  |
| B2 | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
double
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### perpendicularAngle(double aAngle) {#perpendicularAngle-double-}
```
public static double perpendicularAngle(double aAngle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAngle | double |  |

**Returns:**
double
### pointDistanceToPiece(System.Drawing.Point aAPoint, System.Drawing.Point A1, System.Drawing.Point A2) {#pointDistanceToPiece-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double pointDistanceToPiece(System.Drawing.Point aAPoint, System.Drawing.Point A1, System.Drawing.Point A2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAPoint | com.aspose.ms.System.Drawing.Point |  |
| A1 | com.aspose.ms.System.Drawing.Point |  |
| A2 | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
double
### pointDistanceToPiece(System.Drawing.PointF aAPoint, System.Drawing.PointF A1, System.Drawing.PointF A2) {#pointDistanceToPiece-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double pointDistanceToPiece(System.Drawing.PointF aAPoint, System.Drawing.PointF A1, System.Drawing.PointF A2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aAPoint | com.aspose.ms.System.Drawing.PointF |  |
| A1 | com.aspose.ms.System.Drawing.PointF |  |
| A2 | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
double
### pointFsToLineDistance(List<System.Drawing.PointF> aPointFs, LineCoefs aLine) {#pointFsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.PointF--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static List<Double> pointFsToLineDistance(List<System.Drawing.PointF> aPointFs, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPointFs | java.util.List<com.aspose.ms.System.Drawing.PointF> |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
[List](../../java.util/list)
### pointToLineDistance(System.Drawing.Point aPoint, LineCoefs aLine) {#pointToLineDistance-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double pointToLineDistance(System.Drawing.Point aPoint, LineCoefs aLine)
```


Calculate distance from current point to line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.Point | point |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Line variable |

**Returns:**
double - distance, - or + means other sides of line
### pointToLineDistance(System.Drawing.PointF aPoint, LineCoefs aLine) {#pointToLineDistance-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double pointToLineDistance(System.Drawing.PointF aPoint, LineCoefs aLine)
```


Calculate distance from current point to line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.PointF | point |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Line variable |

**Returns:**
double - distance, - or + means other sides of line
### pointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine) {#pointsToLineDistance-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static List<Double> pointsToLineDistance(List<System.Drawing.Point> aPoints, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoints | java.util.List<com.aspose.ms.System.Drawing.Point> |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
[List](../../java.util/list)
### ptFToPt(System.Drawing.PointF aPoint) {#ptFToPt-com.aspose.ms.System.Drawing.PointF-}
```
public static System.Drawing.Point ptFToPt(System.Drawing.PointF aPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### ptToPtF(System.Drawing.Point aPoint) {#ptToPtF-com.aspose.ms.System.Drawing.Point-}
```
public static System.Drawing.PointF ptToPtF(System.Drawing.Point aPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### quadArea(QuadPointFs aQuad) {#quadArea-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-}
```
public static double quadArea(QuadPointFs aQuad)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) |  |

**Returns:**
double
### quadArea(QuadPoints aQuad) {#quadArea-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public static double quadArea(QuadPoints aQuad)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |

**Returns:**
double
### rotatePoint(System.Drawing.PointF aPoint, System.Drawing.PointF aCentralPoint, double aAngle, boolean aClockwise) {#rotatePoint-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-boolean-}
```
public static System.Drawing.PointF rotatePoint(System.Drawing.PointF aPoint, System.Drawing.PointF aCentralPoint, double aAngle, boolean aClockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.PointF |  |
| aCentralPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aClockwise | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### rotatePointList(List<System.Drawing.PointF> aList, System.Drawing.PointF aCentralPoint, double aAngle, boolean aClockwise) {#rotatePointList-java.util.List-com.aspose.ms.System.Drawing.PointF--com.aspose.ms.System.Drawing.PointF-double-boolean-}
```
public static List<System.Drawing.PointF> rotatePointList(List<System.Drawing.PointF> aList, System.Drawing.PointF aCentralPoint, double aAngle, boolean aClockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.ms.System.Drawing.PointF> |  |
| aCentralPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aClockwise | boolean |  |

**Returns:**
[List](../../java.util/list)
### rotateQuad(System.Drawing.PointF centralPoint, QuadPointFs quadPointFs, double angle, boolean clockwise) {#rotateQuad-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-double-boolean-}
```
public static QuadPointFs rotateQuad(System.Drawing.PointF centralPoint, QuadPointFs quadPointFs, double angle, boolean clockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| centralPoint | com.aspose.ms.System.Drawing.PointF |  |
| quadPointFs | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) |  |
| angle | double |  |
| clockwise | boolean |  |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangleArea(System.Drawing.Point aA, System.Drawing.Point aB, System.Drawing.Point aC) {#triangleArea-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double triangleArea(System.Drawing.Point aA, System.Drawing.Point aB, System.Drawing.Point aC)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aA | com.aspose.ms.System.Drawing.Point |  |
| aB | com.aspose.ms.System.Drawing.Point |  |
| aC | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
double
### triangleArea(System.Drawing.PointF aA, System.Drawing.PointF aB, System.Drawing.PointF aC) {#triangleArea-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double triangleArea(System.Drawing.PointF aA, System.Drawing.PointF aB, System.Drawing.PointF aC)
```


http://en.wikipedia.org/wiki/Triangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aA | com.aspose.ms.System.Drawing.PointF | A triangle point |
| aB | com.aspose.ms.System.Drawing.PointF | B triangle point |
| aC | com.aspose.ms.System.Drawing.PointF | C triangle point |

**Returns:**
double
### triangleHeight(System.Drawing.Point aA, System.Drawing.Point aB, System.Drawing.Point aC) {#triangleHeight-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double triangleHeight(System.Drawing.Point aA, System.Drawing.Point aB, System.Drawing.Point aC)
```


h\_base = (2A)/base where A - is a area of a triangle base - a length of AC B is a point from where the height is outing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aA | com.aspose.ms.System.Drawing.Point | A triangle point |
| aB | com.aspose.ms.System.Drawing.Point | B triangle point from where the height is outing |
| aC | com.aspose.ms.System.Drawing.Point | C triangle point |

**Returns:**
double
### triangleHeight(System.Drawing.PointF aA, System.Drawing.PointF aB, System.Drawing.PointF aC) {#triangleHeight-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static double triangleHeight(System.Drawing.PointF aA, System.Drawing.PointF aB, System.Drawing.PointF aC)
```


h\_base = (2A)/base where A - is a area of a triangle base - a length of AC B is a point from where the height is outing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aA | com.aspose.ms.System.Drawing.PointF | A triangle point |
| aB | com.aspose.ms.System.Drawing.PointF | B triangle point from where the height is outing |
| aC | com.aspose.ms.System.Drawing.PointF | C triangle point |

**Returns:**
double
### twoLineMinIntersectAngle(LineCoefs aFirstLine, LineCoefs aSecondLine) {#twoLineMinIntersectAngle-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static double twoLineMinIntersectAngle(LineCoefs aFirstLine, LineCoefs aSecondLine)
```


Intersection between two lines have two angles. So we chose minimal angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirstLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | First line variable |
| aSecondLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) | Second line variable |

**Returns:**
double - minimal intersection angle between lines
### twoPiecesSameDirrectionMatching(System.Drawing.Point A1, System.Drawing.Point A2, System.Drawing.Point B1, System.Drawing.Point B2, double aVertShift) {#twoPiecesSameDirrectionMatching-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-double-}
```
public static boolean twoPiecesSameDirrectionMatching(System.Drawing.Point A1, System.Drawing.Point A2, System.Drawing.Point B1, System.Drawing.Point B2, double aVertShift)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| A1 | com.aspose.ms.System.Drawing.Point |  |
| A2 | com.aspose.ms.System.Drawing.Point |  |
| B1 | com.aspose.ms.System.Drawing.Point |  |
| B2 | com.aspose.ms.System.Drawing.Point |  |
| aVertShift | double |  |

**Returns:**
boolean
### twoPiecesSameDirrectionMatching(System.Drawing.PointF A1, System.Drawing.PointF A2, System.Drawing.PointF B1, System.Drawing.PointF B2, double aVertShift) {#twoPiecesSameDirrectionMatching-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-}
```
public static boolean twoPiecesSameDirrectionMatching(System.Drawing.PointF A1, System.Drawing.PointF A2, System.Drawing.PointF B1, System.Drawing.PointF B2, double aVertShift)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| A1 | com.aspose.ms.System.Drawing.PointF |  |
| A2 | com.aspose.ms.System.Drawing.PointF |  |
| B1 | com.aspose.ms.System.Drawing.PointF |  |
| B2 | com.aspose.ms.System.Drawing.PointF |  |
| aVertShift | double |  |

**Returns:**
boolean
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

