# ProgressBarEx

Owner-drawn C# WinForms ProgressBarEx (community sample, not wyDay) with gradient, rounded corners, and a demo host. The control paints a custom bar with BackgroundColor, ProgressColor, GradiantColor/GradiantPosition, optional percentage or caption text, image overlay, and horizontal or vertical direction. Originally a VB.NET sample (comments still mention the VB Project menu) converted to a C# class library plus designer host; this is Dave Robinson's Historical Dev working copy, not original VaderConsulting code.

Working copy from my Historical Dev folder.

**Source last updated:** 2019-01-06  
**Language:** C#  
**Target:** .NET 3.5  
**Output:** WinForms control library + WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ProgressBarEx` | C# | WinForms library (.NET 3.5) | Owner-drawn `ProgressBarEx` control (gradient, rounded corners, % text) |
| `ProgressBarEx Demo` | C# | WinForms exe (.NET 3.5) | Designer host with 13 styled bars and a Load timer |

## How to open

Open `ProgressBarEx Demo.sln` in Visual Studio 2017 (or later) for the demo host. Open `ProgressBarEx/ProgressBarEx.sln` in Visual C# 2008 Express for the class library alone.

## Requirements

- Visual Studio 2008 to 2017, .NET Framework 3.5

## Attribution and provenance

From Dave Robinson's Historical Dev archive (OneDrive folder `ProgressBarEx`). This is a working copy of a widely circulated community ProgressBarEx WinForms control (originally VB.NET), not wyDay's wyUpdate/Aero ProgressBarEx. Assembly metadata is the Visual Studio template default: title/product `ProgressBarEx` and `ProgressBarEx Demo`, empty company, copyright 2015. See `THIRD_PARTY_NOTICES.md`.

## License

Keep the original author's terms for the control. VaderConsulting's packaging of this working copy does not relicense it as MIT. See `THIRD_PARTY_NOTICES.md`.
