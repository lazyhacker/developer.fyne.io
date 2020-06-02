---
layout: page
tags: [api]
title: Fyne API widget
---

# widget
--
    import "fyne.io/fyne/widget"

## Usage

#### type CustomTextGridStyle

```go
type CustomTextGridStyle struct {
	FGColor, BGColor color.Color
}
```

CustomTextGridStyle is a utility type for those not wanting to define their own style types.

#### func (*CustomTextGridStyle) BackgroundColor

```go
func (c *CustomTextGridStyle) BackgroundColor() color.Color
```
BackgroundColor is the color a cell should use for the background.

#### func (*CustomTextGridStyle) TextColor

```go
func (c *CustomTextGridStyle) TextColor() color.Color
```
TextColor is the color a cell should use for the text.