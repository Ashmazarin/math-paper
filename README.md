# math-paper
func move(to: CGPoint)

func addLine(to: CGPoint)

func addArc(withCenter: CGPoint, radius: CGFloat, startAngle: CGFloat, endAngle: CGFloat, clockwise: Bool)

func addCurve(to: CGPoint, controlPoint1: CGPoint, controlPoint2: CGPoint)

func close()

func removeAllPoints()

func append(UIBezierPath)

var cgPath: CGPath

var currentPoint: CGPoint
