---
title: "BarCodeGeneratorControl"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Klasse ist für die Verwendung in Swing‑Anwendungen konzipiert."
type: docs
weight: 11
url: /de/java/com.aspose.barcode.barcodecontrol/barcodegeneratorcontrol/
---
**Inheritance:**
java.lang.Object, java.awt.Component, java.awt.Container, javax.swing.JComponent, javax.swing.JLabel

**All Implemented Interfaces:**
[com.aspose.barcode.barcodecontrol.IBarCodeGeneratorControl](../../com.aspose.barcode.barcodecontrol/ibarcodegeneratorcontrol)
```
public class BarCodeGeneratorControl extends JLabel implements IBarCodeGeneratorControl
```

Klasse ist für die Verwendung in Swing-Anwendungen konzipiert. Sie erweitert die Swing-Klasse JLabel und kann in die Benutzeroberfläche eingefügt werden
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BarCodeGeneratorControl()](#BarCodeGeneratorControl--) | Initialisiert eine neue Instanz der BarCodeGeneratorControl-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BOTTOM_ALIGNMENT](#BOTTOM-ALIGNMENT) |  |
| [CENTER_ALIGNMENT](#CENTER-ALIGNMENT) |  |
| [LEFT_ALIGNMENT](#LEFT-ALIGNMENT) |  |
| [RIGHT_ALIGNMENT](#RIGHT-ALIGNMENT) |  |
| [TOOL_TIP_TEXT_KEY](#TOOL-TIP-TEXT-KEY) |  |
| [TOP_ALIGNMENT](#TOP-ALIGNMENT) |  |
| [UNDEFINED_CONDITION](#UNDEFINED-CONDITION) |  |
| [WHEN_ANCESTOR_OF_FOCUSED_COMPONENT](#WHEN-ANCESTOR-OF-FOCUSED-COMPONENT) |  |
| [WHEN_FOCUSED](#WHEN-FOCUSED) |  |
| [WHEN_IN_FOCUSED_WINDOW](#WHEN-IN-FOCUSED-WINDOW) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [<T>getListeners(Class<T> arg0)](#-T-getListeners-java.lang.Class-T--) |  |
| [action(Event arg0, Object arg1)](#action-java.awt.Event-java.lang.Object-) |  |
| [add(Component arg0)](#add-java.awt.Component-) |  |
| [add(Component arg0, int arg1)](#add-java.awt.Component-int-) |  |
| [add(Component arg0, Object arg1)](#add-java.awt.Component-java.lang.Object-) |  |
| [add(Component arg0, Object arg1, int arg2)](#add-java.awt.Component-java.lang.Object-int-) |  |
| [add(PopupMenu arg0)](#add-java.awt.PopupMenu-) |  |
| [add(String arg0, Component arg1)](#add-java.lang.String-java.awt.Component-) |  |
| [addAncestorListener(AncestorListener arg0)](#addAncestorListener-javax.swing.event.AncestorListener-) |  |
| [addComponentListener(ComponentListener arg0)](#addComponentListener-java.awt.event.ComponentListener-) |  |
| [addContainerListener(ContainerListener arg0)](#addContainerListener-java.awt.event.ContainerListener-) |  |
| [addFocusListener(FocusListener arg0)](#addFocusListener-java.awt.event.FocusListener-) |  |
| [addHierarchyBoundsListener(HierarchyBoundsListener arg0)](#addHierarchyBoundsListener-java.awt.event.HierarchyBoundsListener-) |  |
| [addHierarchyListener(HierarchyListener arg0)](#addHierarchyListener-java.awt.event.HierarchyListener-) |  |
| [addInputMethodListener(InputMethodListener arg0)](#addInputMethodListener-java.awt.event.InputMethodListener-) |  |
| [addKeyListener(KeyListener arg0)](#addKeyListener-java.awt.event.KeyListener-) |  |
| [addMouseListener(MouseListener arg0)](#addMouseListener-java.awt.event.MouseListener-) |  |
| [addMouseMotionListener(MouseMotionListener arg0)](#addMouseMotionListener-java.awt.event.MouseMotionListener-) |  |
| [addMouseWheelListener(MouseWheelListener arg0)](#addMouseWheelListener-java.awt.event.MouseWheelListener-) |  |
| [addNotify()](#addNotify--) |  |
| [addPropertyChangeListener(PropertyChangeListener arg0)](#addPropertyChangeListener-java.beans.PropertyChangeListener-) |  |
| [addPropertyChangeListener(String arg0, PropertyChangeListener arg1)](#addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-) |  |
| [addVetoableChangeListener(VetoableChangeListener arg0)](#addVetoableChangeListener-java.beans.VetoableChangeListener-) |  |
| [applyComponentOrientation(ComponentOrientation arg0)](#applyComponentOrientation-java.awt.ComponentOrientation-) |  |
| [areFocusTraversalKeysSet(int arg0)](#areFocusTraversalKeysSet-int-) |  |
| [bounds()](#bounds--) |  |
| [checkImage(Image arg0, int arg1, int arg2, ImageObserver arg3)](#checkImage-java.awt.Image-int-int-java.awt.image.ImageObserver-) |  |
| [checkImage(Image arg0, ImageObserver arg1)](#checkImage-java.awt.Image-java.awt.image.ImageObserver-) |  |
| [computeVisibleRect(Rectangle arg0)](#computeVisibleRect-java.awt.Rectangle-) |  |
| [contains(int arg0, int arg1)](#contains-int-int-) |  |
| [contains(Point arg0)](#contains-java.awt.Point-) |  |
| [countComponents()](#countComponents--) |  |
| [createImage(int arg0, int arg1)](#createImage-int-int-) |  |
| [createImage(ImageProducer arg0)](#createImage-java.awt.image.ImageProducer-) |  |
| [createToolTip()](#createToolTip--) |  |
| [createVolatileImage(int arg0, int arg1)](#createVolatileImage-int-int-) |  |
| [createVolatileImage(int arg0, int arg1, ImageCapabilities arg2)](#createVolatileImage-int-int-java.awt.ImageCapabilities-) |  |
| [deliverEvent(Event arg0)](#deliverEvent-java.awt.Event-) |  |
| [disable()](#disable--) |  |
| [dispatchEvent(AWTEvent arg0)](#dispatchEvent-java.awt.AWTEvent-) |  |
| [doLayout()](#doLayout--) |  |
| [enable()](#enable--) |  |
| [enable(boolean arg0)](#enable-boolean-) |  |
| [enableInputMethods(boolean arg0)](#enableInputMethods-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findComponentAt(int arg0, int arg1)](#findComponentAt-int-int-) |  |
| [findComponentAt(Point arg0)](#findComponentAt-java.awt.Point-) |  |
| [firePropertyChange(String arg0, boolean arg1, boolean arg2)](#firePropertyChange-java.lang.String-boolean-boolean-) |  |
| [firePropertyChange(String arg0, byte arg1, byte arg2)](#firePropertyChange-java.lang.String-byte-byte-) |  |
| [firePropertyChange(String arg0, char arg1, char arg2)](#firePropertyChange-java.lang.String-char-char-) |  |
| [firePropertyChange(String arg0, double arg1, double arg2)](#firePropertyChange-java.lang.String-double-double-) |  |
| [firePropertyChange(String arg0, float arg1, float arg2)](#firePropertyChange-java.lang.String-float-float-) |  |
| [firePropertyChange(String arg0, int arg1, int arg2)](#firePropertyChange-java.lang.String-int-int-) |  |
| [firePropertyChange(String arg0, long arg1, long arg2)](#firePropertyChange-java.lang.String-long-long-) |  |
| [firePropertyChange(String arg0, short arg1, short arg2)](#firePropertyChange-java.lang.String-short-short-) |  |
| [getAccessibleContext()](#getAccessibleContext--) |  |
| [getActionForKeyStroke(KeyStroke arg0)](#getActionForKeyStroke-javax.swing.KeyStroke-) |  |
| [getActionMap()](#getActionMap--) |  |
| [getAlignmentX()](#getAlignmentX--) |  |
| [getAlignmentY()](#getAlignmentY--) |  |
| [getAncestorListeners()](#getAncestorListeners--) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Liest den Modus aus, in dem der Barcode automatisch skaliert wird. |
| [getAutoscrolls()](#getAutoscrolls--) |  |
| [getBackground()](#getBackground--) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Hintergrundfarbe des Barcode-Bildes. |
| [getBarCodeHeight()](#getBarCodeHeight--) | Barcode-Bildhöhe, wenn die Eigenschaft com.aspose.barcode.generation.AutoSizeMode auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [getBarCodeWidth()](#getBarCodeWidth--) | Barcode-Bildbreite, wenn die Eigenschaft com.aspose.barcode.generation.AutoSizeMode auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [getBarColor()](#getBarColor--) | Farbe der Balken. |
| [getBarHeight()](#getBarHeight--) | Höhe der Balken von 1D-Barcodes. |
| [getBarcodePaddings()](#getBarcodePaddings--) | Ruft die Barcode‑Abstandparameter com.aspose.barcode.generation.Padding ab. |
| [getBarcodeType()](#getBarcodeType--) | Kodierungstyp des Barcodes (Symbolik). |
| [getBaseline(int arg0, int arg1)](#getBaseline-int-int-) |  |
| [getBaselineResizeBehavior()](#getBaselineResizeBehavior--) |  |
| [getBorder()](#getBorder--) |  |
| [getBorderParameters()](#getBorderParameters--) | Ruft die Randparameter com.aspose.barcode.generation.BorderParameters ab. |
| [getBounds()](#getBounds--) |  |
| [getBounds(Rectangle arg0)](#getBounds-java.awt.Rectangle-) |  |
| [getCaptionAbove()](#getCaptionAbove--) | Beschriftung über dem Barcode‑Bild. |
| [getCaptionBelow()](#getCaptionBelow--) | Beschriftung über dem Barcode‑Bild. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes an. |
| [getClass()](#getClass--) |  |
| [getClientProperty(Object arg0)](#getClientProperty-java.lang.Object-) |  |
| [getCodeText()](#getCodeText--) | Zu codierende Daten; verschiedene Barcode‑Typen können unterschiedliche Längenbeschränkungen für den CodeText haben. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Ruft die CodeText‑Parameter com.aspose.barcode.generation.CodetextParameters ab. |
| [getColorModel()](#getColorModel--) |  |
| [getComponent(int arg0)](#getComponent-int-) |  |
| [getComponentAt(int arg0, int arg1)](#getComponentAt-int-int-) |  |
| [getComponentAt(Point arg0)](#getComponentAt-java.awt.Point-) |  |
| [getComponentCount()](#getComponentCount--) |  |
| [getComponentListeners()](#getComponentListeners--) |  |
| [getComponentOrientation()](#getComponentOrientation--) |  |
| [getComponentPopupMenu()](#getComponentPopupMenu--) |  |
| [getComponentZOrder(Component arg0)](#getComponentZOrder-java.awt.Component-) |  |
| [getComponents()](#getComponents--) |  |
| [getConditionForKeyStroke(KeyStroke arg0)](#getConditionForKeyStroke-javax.swing.KeyStroke-) |  |
| [getContainerListeners()](#getContainerListeners--) |  |
| [getCursor()](#getCursor--) |  |
| [getDebugGraphicsOptions()](#getDebugGraphicsOptions--) |  |
| [getDefaultLocale()](#getDefaultLocale--) |  |
| [getDisabledIcon()](#getDisabledIcon--) |  |
| [getDisplayedMnemonic()](#getDisplayedMnemonic--) |  |
| [getDisplayedMnemonicIndex()](#getDisplayedMnemonicIndex--) |  |
| [getDropTarget()](#getDropTarget--) |  |
| [getEncodeType()](#getEncodeType--) | Kodierungstyp des Barcodes (Symbolik). |
| [getFilledBars()](#getFilledBars--) | Ruft einen Wert ab, der angibt, ob die Balken gefüllt sind. |
| [getFocusCycleRootAncestor()](#getFocusCycleRootAncestor--) |  |
| [getFocusListeners()](#getFocusListeners--) |  |
| [getFocusTraversalKeys(int arg0)](#getFocusTraversalKeys-int-) |  |
| [getFocusTraversalKeysEnabled()](#getFocusTraversalKeysEnabled--) |  |
| [getFocusTraversalPolicy()](#getFocusTraversalPolicy--) |  |
| [getFont()](#getFont--) |  |
| [getFontMetrics(Font arg0)](#getFontMetrics-java.awt.Font-) |  |
| [getForeground()](#getForeground--) |  |
| [getGraphics()](#getGraphics--) |  |
| [getGraphicsConfiguration()](#getGraphicsConfiguration--) |  |
| [getHeight()](#getHeight--) |  |
| [getHierarchyBoundsListeners()](#getHierarchyBoundsListeners--) |  |
| [getHierarchyListeners()](#getHierarchyListeners--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) |  |
| [getHorizontalTextPosition()](#getHorizontalTextPosition--) |  |
| [getIcon()](#getIcon--) |  |
| [getIconTextGap()](#getIconTextGap--) |  |
| [getIgnoreRepaint()](#getIgnoreRepaint--) |  |
| [getInheritsPopupMenu()](#getInheritsPopupMenu--) |  |
| [getInputContext()](#getInputContext--) |  |
| [getInputMap()](#getInputMap--) |  |
| [getInputMap(int arg0)](#getInputMap-int-) |  |
| [getInputMethodListeners()](#getInputMethodListeners--) |  |
| [getInputMethodRequests()](#getInputMethodRequests--) |  |
| [getInputVerifier()](#getInputVerifier--) |  |
| [getInsets()](#getInsets--) |  |
| [getInsets(Insets arg0)](#getInsets-java.awt.Insets-) |  |
| [getKeyListeners()](#getKeyListeners--) |  |
| [getLabelFor()](#getLabelFor--) |  |
| [getLayout()](#getLayout--) |  |
| [getLocale()](#getLocale--) |  |
| [getLocation()](#getLocation--) |  |
| [getLocation(Point arg0)](#getLocation-java.awt.Point-) |  |
| [getLocationOnScreen()](#getLocationOnScreen--) |  |
| [getMaximumSize()](#getMaximumSize--) |  |
| [getMinimumSize()](#getMinimumSize--) |  |
| [getMouseListeners()](#getMouseListeners--) |  |
| [getMouseMotionListeners()](#getMouseMotionListeners--) |  |
| [getMousePosition()](#getMousePosition--) |  |
| [getMousePosition(boolean arg0)](#getMousePosition-boolean-) |  |
| [getMouseWheelListeners()](#getMouseWheelListeners--) |  |
| [getName()](#getName--) |  |
| [getNextFocusableComponent()](#getNextFocusableComponent--) |  |
| [getParent()](#getParent--) |  |
| [getPopupLocation(MouseEvent arg0)](#getPopupLocation-java.awt.event.MouseEvent-) |  |
| [getPreferredSize()](#getPreferredSize--) |  |
| [getPropertyChangeListeners()](#getPropertyChangeListeners--) |  |
| [getPropertyChangeListeners(String arg0)](#getPropertyChangeListeners-java.lang.String-) |  |
| [getRegisteredKeyStrokes()](#getRegisteredKeyStrokes--) |  |
| [getResolution()](#getResolution--) | Ruft die Auflösung des Barcode‑Bildes ab. |
| [getRootPane()](#getRootPane--) |  |
| [getRotationAngle()](#getRotationAngle--) | Drehwinkel des Barcode‑Bildes, gemessen in Grad, z. B. |
| [getSize()](#getSize--) |  |
| [getSize(Dimension arg0)](#getSize-java.awt.Dimension-) |  |
| [getSpecific()](#getSpecific--) | Spezifische Parameter |
| [getText()](#getText--) |  |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Nur für 1D‑Barcodes. |
| [getToolTipLocation(MouseEvent arg0)](#getToolTipLocation-java.awt.event.MouseEvent-) |  |
| [getToolTipText()](#getToolTipText--) |  |
| [getToolTipText(MouseEvent arg0)](#getToolTipText-java.awt.event.MouseEvent-) |  |
| [getToolkit()](#getToolkit--) |  |
| [getTopLevelAncestor()](#getTopLevelAncestor--) |  |
| [getTransferHandler()](#getTransferHandler--) |  |
| [getTreeLock()](#getTreeLock--) |  |
| [getUI()](#getUI--) |  |
| [getUIClassID()](#getUIClassID--) |  |
| [getVerifyInputWhenFocusTarget()](#getVerifyInputWhenFocusTarget--) |  |
| [getVerticalAlignment()](#getVerticalAlignment--) |  |
| [getVerticalTextPosition()](#getVerticalTextPosition--) |  |
| [getVetoableChangeListeners()](#getVetoableChangeListeners--) |  |
| [getVisibleRect()](#getVisibleRect--) |  |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Verhältnis von breiten zu schmalen Balken. |
| [getWidth()](#getWidth--) |  |
| [getX()](#getX--) |  |
| [getXDimension()](#getXDimension--) | Die X‑Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. |
| [getY()](#getY--) |  |
| [gotFocus(Event arg0, Object arg1)](#gotFocus-java.awt.Event-java.lang.Object-) |  |
| [grabFocus()](#grabFocus--) |  |
| [handleEvent(Event arg0)](#handleEvent-java.awt.Event-) |  |
| [hasFocus()](#hasFocus--) |  |
| [hashCode()](#hashCode--) |  |
| [hide()](#hide--) |  |
| [imageUpdate(Image arg0, int arg1, int arg2, int arg3, int arg4, int arg5)](#imageUpdate-java.awt.Image-int-int-int-int-int-) |  |
| [insets()](#insets--) |  |
| [inside(int arg0, int arg1)](#inside-int-int-) |  |
| [invalidate()](#invalidate--) |  |
| [isAncestorOf(Component arg0)](#isAncestorOf-java.awt.Component-) |  |
| [isBackgroundSet()](#isBackgroundSet--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [isCursorSet()](#isCursorSet--) |  |
| [isDisplayable()](#isDisplayable--) |  |
| [isDoubleBuffered()](#isDoubleBuffered--) |  |
| [isEnabled()](#isEnabled--) |  |
| [isFocusCycleRoot()](#isFocusCycleRoot--) |  |
| [isFocusCycleRoot(Container arg0)](#isFocusCycleRoot-java.awt.Container-) |  |
| [isFocusOwner()](#isFocusOwner--) |  |
| [isFocusTraversable()](#isFocusTraversable--) |  |
| [isFocusTraversalPolicyProvider()](#isFocusTraversalPolicyProvider--) |  |
| [isFocusTraversalPolicySet()](#isFocusTraversalPolicySet--) |  |
| [isFocusable()](#isFocusable--) |  |
| [isFontSet()](#isFontSet--) |  |
| [isForegroundSet()](#isForegroundSet--) |  |
| [isLightweight()](#isLightweight--) |  |
| [isLightweightComponent(Component arg0)](#isLightweightComponent-java.awt.Component-) |  |
| [isManagingFocus()](#isManagingFocus--) |  |
| [isMaximumSizeSet()](#isMaximumSizeSet--) |  |
| [isMinimumSizeSet()](#isMinimumSizeSet--) |  |
| [isOpaque()](#isOpaque--) |  |
| [isOptimizedDrawingEnabled()](#isOptimizedDrawingEnabled--) |  |
| [isPaintingForPrint()](#isPaintingForPrint--) |  |
| [isPaintingTile()](#isPaintingTile--) |  |
| [isPreferredSizeSet()](#isPreferredSizeSet--) |  |
| [isRequestFocusEnabled()](#isRequestFocusEnabled--) |  |
| [isShowing()](#isShowing--) |  |
| [isUseAntiAlias()](#isUseAntiAlias--) | Ruft einen Wert ab, der angibt, ob ein Anti‑Aliasing‑Modus zum Rendern des Bildes verwendet wird. |
| [isValid()](#isValid--) |  |
| [isValidateRoot()](#isValidateRoot--) |  |
| [isVisible()](#isVisible--) |  |
| [keyDown(Event arg0, int arg1)](#keyDown-java.awt.Event-int-) |  |
| [keyUp(Event arg0, int arg1)](#keyUp-java.awt.Event-int-) |  |
| [layout()](#layout--) |  |
| [list()](#list--) |  |
| [list(PrintStream arg0)](#list-java.io.PrintStream-) |  |
| [list(PrintStream arg0, int arg1)](#list-java.io.PrintStream-int-) |  |
| [list(PrintWriter arg0)](#list-java.io.PrintWriter-) |  |
| [list(PrintWriter arg0, int arg1)](#list-java.io.PrintWriter-int-) |  |
| [locate(int arg0, int arg1)](#locate-int-int-) |  |
| [location()](#location--) |  |
| [lostFocus(Event arg0, Object arg1)](#lostFocus-java.awt.Event-java.lang.Object-) |  |
| [minimumSize()](#minimumSize--) |  |
| [mouseDown(Event arg0, int arg1, int arg2)](#mouseDown-java.awt.Event-int-int-) |  |
| [mouseDrag(Event arg0, int arg1, int arg2)](#mouseDrag-java.awt.Event-int-int-) |  |
| [mouseEnter(Event arg0, int arg1, int arg2)](#mouseEnter-java.awt.Event-int-int-) |  |
| [mouseExit(Event arg0, int arg1, int arg2)](#mouseExit-java.awt.Event-int-int-) |  |
| [mouseMove(Event arg0, int arg1, int arg2)](#mouseMove-java.awt.Event-int-int-) |  |
| [mouseUp(Event arg0, int arg1, int arg2)](#mouseUp-java.awt.Event-int-int-) |  |
| [move(int arg0, int arg1)](#move-int-int-) |  |
| [nextFocus()](#nextFocus--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [paint(Graphics arg0)](#paint-java.awt.Graphics-) |  |
| [paintAll(Graphics arg0)](#paintAll-java.awt.Graphics-) |  |
| [paintComponents(Graphics arg0)](#paintComponents-java.awt.Graphics-) |  |
| [paintImmediately(int arg0, int arg1, int arg2, int arg3)](#paintImmediately-int-int-int-int-) |  |
| [paintImmediately(Rectangle arg0)](#paintImmediately-java.awt.Rectangle-) |  |
| [postEvent(Event arg0)](#postEvent-java.awt.Event-) |  |
| [preferredSize()](#preferredSize--) |  |
| [prepareImage(Image arg0, int arg1, int arg2, ImageObserver arg3)](#prepareImage-java.awt.Image-int-int-java.awt.image.ImageObserver-) |  |
| [prepareImage(Image arg0, ImageObserver arg1)](#prepareImage-java.awt.Image-java.awt.image.ImageObserver-) |  |
| [print(Graphics arg0)](#print-java.awt.Graphics-) |  |
| [printAll(Graphics arg0)](#printAll-java.awt.Graphics-) |  |
| [printComponents(Graphics arg0)](#printComponents-java.awt.Graphics-) |  |
| [putClientProperty(Object arg0, Object arg1)](#putClientProperty-java.lang.Object-java.lang.Object-) |  |
| [registerKeyboardAction(ActionListener arg0, String arg1, KeyStroke arg2, int arg3)](#registerKeyboardAction-java.awt.event.ActionListener-java.lang.String-javax.swing.KeyStroke-int-) |  |
| [registerKeyboardAction(ActionListener arg0, KeyStroke arg1, int arg2)](#registerKeyboardAction-java.awt.event.ActionListener-javax.swing.KeyStroke-int-) |  |
| [remove(int arg0)](#remove-int-) |  |
| [remove(Component arg0)](#remove-java.awt.Component-) |  |
| [remove(MenuComponent arg0)](#remove-java.awt.MenuComponent-) |  |
| [removeAll()](#removeAll--) |  |
| [removeAncestorListener(AncestorListener arg0)](#removeAncestorListener-javax.swing.event.AncestorListener-) |  |
| [removeComponentListener(ComponentListener arg0)](#removeComponentListener-java.awt.event.ComponentListener-) |  |
| [removeContainerListener(ContainerListener arg0)](#removeContainerListener-java.awt.event.ContainerListener-) |  |
| [removeFocusListener(FocusListener arg0)](#removeFocusListener-java.awt.event.FocusListener-) |  |
| [removeHierarchyBoundsListener(HierarchyBoundsListener arg0)](#removeHierarchyBoundsListener-java.awt.event.HierarchyBoundsListener-) |  |
| [removeHierarchyListener(HierarchyListener arg0)](#removeHierarchyListener-java.awt.event.HierarchyListener-) |  |
| [removeInputMethodListener(InputMethodListener arg0)](#removeInputMethodListener-java.awt.event.InputMethodListener-) |  |
| [removeKeyListener(KeyListener arg0)](#removeKeyListener-java.awt.event.KeyListener-) |  |
| [removeMouseListener(MouseListener arg0)](#removeMouseListener-java.awt.event.MouseListener-) |  |
| [removeMouseMotionListener(MouseMotionListener arg0)](#removeMouseMotionListener-java.awt.event.MouseMotionListener-) |  |
| [removeMouseWheelListener(MouseWheelListener arg0)](#removeMouseWheelListener-java.awt.event.MouseWheelListener-) |  |
| [removeNotify()](#removeNotify--) |  |
| [removePropertyChangeListener(PropertyChangeListener arg0)](#removePropertyChangeListener-java.beans.PropertyChangeListener-) |  |
| [removePropertyChangeListener(String arg0, PropertyChangeListener arg1)](#removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-) |  |
| [removeVetoableChangeListener(VetoableChangeListener arg0)](#removeVetoableChangeListener-java.beans.VetoableChangeListener-) |  |
| [repaint()](#repaint--) |  |
| [repaint(int arg0, int arg1, int arg2, int arg3)](#repaint-int-int-int-int-) |  |
| [repaint(Rectangle arg0)](#repaint-java.awt.Rectangle-) |  |
| [repaint(long arg0)](#repaint-long-) |  |
| [repaint(long arg0, int arg1, int arg2, int arg3, int arg4)](#repaint-long-int-int-int-int-) |  |
| [requestDefaultFocus()](#requestDefaultFocus--) |  |
| [requestFocus()](#requestFocus--) |  |
| [requestFocus(boolean arg0)](#requestFocus-boolean-) |  |
| [requestFocus(FocusEvent.Cause arg0)](#requestFocus-java.awt.event.FocusEvent.Cause-) |  |
| [requestFocusInWindow()](#requestFocusInWindow--) |  |
| [requestFocusInWindow(FocusEvent.Cause arg0)](#requestFocusInWindow-java.awt.event.FocusEvent.Cause-) |  |
| [resetKeyboardActions()](#resetKeyboardActions--) |  |
| [reshape(int arg0, int arg1, int arg2, int arg3)](#reshape-int-int-int-int-) |  |
| [resize(int arg0, int arg1)](#resize-int-int-) |  |
| [resize(Dimension arg0)](#resize-java.awt.Dimension-) |  |
| [revalidate()](#revalidate--) |  |
| [scrollRectToVisible(Rectangle arg0)](#scrollRectToVisible-java.awt.Rectangle-) |  |
| [setActionMap(ActionMap arg0)](#setActionMap-javax.swing.ActionMap-) |  |
| [setAlignmentX(float arg0)](#setAlignmentX-float-) |  |
| [setAlignmentY(float arg0)](#setAlignmentY-float-) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Legt den Modus fest, in dem der Barcode automatisch die Größe ändert. |
| [setAutoscrolls(boolean arg0)](#setAutoscrolls-boolean-) |  |
| [setBackground(Color arg0)](#setBackground-java.awt.Color-) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Hintergrundfarbe des Barcode-Bildes. |
| [setBarColor(Color value)](#setBarColor-java.awt.Color-) | Farbe der Balken. |
| [setBarcodeType(String value)](#setBarcodeType-java.lang.String-) | Kodierungstyp des Barcodes (Symbolik). |
| [setBorder(Border arg0)](#setBorder-javax.swing.border.Border-) |  |
| [setBounds(int arg0, int arg1, int arg2, int arg3)](#setBounds-int-int-int-int-) |  |
| [setBounds(Rectangle arg0)](#setBounds-java.awt.Rectangle-) |  |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes an. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) | Aktiviert die Prüfziffer bei der Erzeugung von 1D‑Barcodes. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Zu codierende Daten; verschiedene Barcode‑Typen können unterschiedliche Längenbeschränkungen für den CodeText haben. |
| [setComponentOrientation(ComponentOrientation arg0)](#setComponentOrientation-java.awt.ComponentOrientation-) |  |
| [setComponentPopupMenu(JPopupMenu arg0)](#setComponentPopupMenu-javax.swing.JPopupMenu-) |  |
| [setComponentZOrder(Component arg0, int arg1)](#setComponentZOrder-java.awt.Component-int-) |  |
| [setCursor(Cursor arg0)](#setCursor-java.awt.Cursor-) |  |
| [setDebugGraphicsOptions(int arg0)](#setDebugGraphicsOptions-int-) |  |
| [setDefaultLocale(Locale arg0)](#setDefaultLocale-java.util.Locale-) |  |
| [setDisabledIcon(Icon arg0)](#setDisabledIcon-javax.swing.Icon-) |  |
| [setDisplayedMnemonic(char arg0)](#setDisplayedMnemonic-char-) |  |
| [setDisplayedMnemonic(int arg0)](#setDisplayedMnemonic-int-) |  |
| [setDisplayedMnemonicIndex(int arg0)](#setDisplayedMnemonicIndex-int-) |  |
| [setDoubleBuffered(boolean arg0)](#setDoubleBuffered-boolean-) |  |
| [setDropTarget(DropTarget arg0)](#setDropTarget-java.awt.dnd.DropTarget-) |  |
| [setEnabled(boolean arg0)](#setEnabled-boolean-) |  |
| [setEncodeType(BaseEncodeType value)](#setEncodeType-com.aspose.barcode.generation.BaseEncodeType-) | Kodierungstyp des Barcodes (Symbolik). |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Ruft einen Wert ab, der angibt, ob die Balken gefüllt sind. |
| [setFocusCycleRoot(boolean arg0)](#setFocusCycleRoot-boolean-) |  |
| [setFocusTraversalKeys(int arg0, Set<? extends AWTKeyStroke> arg1)](#setFocusTraversalKeys-int-java.util.Set---extends-java.awt.AWTKeyStroke--) |  |
| [setFocusTraversalKeysEnabled(boolean arg0)](#setFocusTraversalKeysEnabled-boolean-) |  |
| [setFocusTraversalPolicy(FocusTraversalPolicy arg0)](#setFocusTraversalPolicy-java.awt.FocusTraversalPolicy-) |  |
| [setFocusTraversalPolicyProvider(boolean arg0)](#setFocusTraversalPolicyProvider-boolean-) |  |
| [setFocusable(boolean arg0)](#setFocusable-boolean-) |  |
| [setFont(Font arg0)](#setFont-java.awt.Font-) |  |
| [setForeground(Color arg0)](#setForeground-java.awt.Color-) |  |
| [setHorizontalAlignment(int arg0)](#setHorizontalAlignment-int-) |  |
| [setHorizontalTextPosition(int arg0)](#setHorizontalTextPosition-int-) |  |
| [setIcon(Icon arg0)](#setIcon-javax.swing.Icon-) |  |
| [setIconTextGap(int arg0)](#setIconTextGap-int-) |  |
| [setIgnoreRepaint(boolean arg0)](#setIgnoreRepaint-boolean-) |  |
| [setInheritsPopupMenu(boolean arg0)](#setInheritsPopupMenu-boolean-) |  |
| [setInputMap(int arg0, InputMap arg1)](#setInputMap-int-javax.swing.InputMap-) |  |
| [setInputVerifier(InputVerifier arg0)](#setInputVerifier-javax.swing.InputVerifier-) |  |
| [setLabelFor(Component arg0)](#setLabelFor-java.awt.Component-) |  |
| [setLayout(LayoutManager arg0)](#setLayout-java.awt.LayoutManager-) |  |
| [setLocale(Locale arg0)](#setLocale-java.util.Locale-) |  |
| [setLocation(int arg0, int arg1)](#setLocation-int-int-) |  |
| [setLocation(Point arg0)](#setLocation-java.awt.Point-) |  |
| [setMaximumSize(Dimension arg0)](#setMaximumSize-java.awt.Dimension-) |  |
| [setMinimumSize(Dimension arg0)](#setMinimumSize-java.awt.Dimension-) |  |
| [setMixingCutoutShape(Shape arg0)](#setMixingCutoutShape-java.awt.Shape-) |  |
| [setName(String arg0)](#setName-java.lang.String-) |  |
| [setNextFocusableComponent(Component arg0)](#setNextFocusableComponent-java.awt.Component-) |  |
| [setOpaque(boolean arg0)](#setOpaque-boolean-) |  |
| [setPreferredSize(Dimension arg0)](#setPreferredSize-java.awt.Dimension-) |  |
| [setRequestFocusEnabled(boolean arg0)](#setRequestFocusEnabled-boolean-) |  |
| [setResolution(float value)](#setResolution-float-) | Legt die Auflösung des Barcode‑Bildes fest. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Drehwinkel des Barcode‑Bildes, gemessen in Grad, z. B. |
| [setSize(int arg0, int arg1)](#setSize-int-int-) |  |
| [setSize(Dimension arg0)](#setSize-java.awt.Dimension-) |  |
| [setText(String arg0)](#setText-java.lang.String-) |  |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Nur für 1D‑Barcodes. |
| [setToolTipText(String arg0)](#setToolTipText-java.lang.String-) |  |
| [setTransferHandler(TransferHandler arg0)](#setTransferHandler-javax.swing.TransferHandler-) |  |
| [setUI(LabelUI arg0)](#setUI-javax.swing.plaf.LabelUI-) |  |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Legt einen Wert fest, der angibt, ob ein Anti‑Aliasing‑Modus zum Rendern des Bildes verwendet wird. |
| [setVerifyInputWhenFocusTarget(boolean arg0)](#setVerifyInputWhenFocusTarget-boolean-) |  |
| [setVerticalAlignment(int arg0)](#setVerticalAlignment-int-) |  |
| [setVerticalTextPosition(int arg0)](#setVerticalTextPosition-int-) |  |
| [setVisible(boolean arg0)](#setVisible-boolean-) |  |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Verhältnis von breiten zu schmalen Balken. |
| [show()](#show--) |  |
| [show(boolean arg0)](#show-boolean-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [transferFocus()](#transferFocus--) |  |
| [transferFocusBackward()](#transferFocusBackward--) |  |
| [transferFocusDownCycle()](#transferFocusDownCycle--) |  |
| [transferFocusUpCycle()](#transferFocusUpCycle--) |  |
| [unregisterKeyboardAction(KeyStroke arg0)](#unregisterKeyboardAction-javax.swing.KeyStroke-) |  |
| [update(Graphics arg0)](#update-java.awt.Graphics-) |  |
| [updateUI()](#updateUI--) |  |
| [validate()](#validate--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeGeneratorControl() {#BarCodeGeneratorControl--}
```
public BarCodeGeneratorControl()
```


Initialisiert eine neue Instanz der BarCodeGeneratorControl-Klasse.

### BOTTOM_ALIGNMENT {#BOTTOM-ALIGNMENT}
```
public static final float BOTTOM_ALIGNMENT
```


### CENTER_ALIGNMENT {#CENTER-ALIGNMENT}
```
public static final float CENTER_ALIGNMENT
```


### LEFT_ALIGNMENT {#LEFT-ALIGNMENT}
```
public static final float LEFT_ALIGNMENT
```


### RIGHT_ALIGNMENT {#RIGHT-ALIGNMENT}
```
public static final float RIGHT_ALIGNMENT
```


### TOOL_TIP_TEXT_KEY {#TOOL-TIP-TEXT-KEY}
```
public static final String TOOL_TIP_TEXT_KEY
```


### TOP_ALIGNMENT {#TOP-ALIGNMENT}
```
public static final float TOP_ALIGNMENT
```


### UNDEFINED_CONDITION {#UNDEFINED-CONDITION}
```
public static final int UNDEFINED_CONDITION
```


### WHEN_ANCESTOR_OF_FOCUSED_COMPONENT {#WHEN-ANCESTOR-OF-FOCUSED-COMPONENT}
```
public static final int WHEN_ANCESTOR_OF_FOCUSED_COMPONENT
```


### WHEN_FOCUSED {#WHEN-FOCUSED}
```
public static final int WHEN_FOCUSED
```


### WHEN_IN_FOCUSED_WINDOW {#WHEN-IN-FOCUSED-WINDOW}
```
public static final int WHEN_IN_FOCUSED_WINDOW
```


### <T>getListeners(Class<T> arg0) {#-T-getListeners-java.lang.Class-T--}
```
public T[] <T>getListeners(Class<T> arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |

**Returns:**
T[]
### action(Event arg0, Object arg1) {#action-java.awt.Event-java.lang.Object-}
```
public boolean action(Event arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolesch
### add(Component arg0) {#add-java.awt.Component-}
```
public Component add(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

**Returns:**
java.awt.Component
### add(Component arg0, int arg1) {#add-java.awt.Component-int-}
```
public Component add(Component arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |
| arg1 | int |  |

**Returns:**
java.awt.Component
### add(Component arg0, Object arg1) {#add-java.awt.Component-java.lang.Object-}
```
public void add(Component arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |
| arg1 | java.lang.Object |  |

### add(Component arg0, Object arg1, int arg2) {#add-java.awt.Component-java.lang.Object-int-}
```
public void add(Component arg0, Object arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |
| arg1 | java.lang.Object |  |
| arg2 | int |  |

### add(PopupMenu arg0) {#add-java.awt.PopupMenu-}
```
public void add(PopupMenu arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.PopupMenu |  |

### add(String arg0, Component arg1) {#add-java.lang.String-java.awt.Component-}
```
public Component add(String arg0, Component arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | java.awt.Component |  |

**Returns:**
java.awt.Component
### addAncestorListener(AncestorListener arg0) {#addAncestorListener-javax.swing.event.AncestorListener-}
```
public void addAncestorListener(AncestorListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.event.AncestorListener |  |

### addComponentListener(ComponentListener arg0) {#addComponentListener-java.awt.event.ComponentListener-}
```
public synchronized void addComponentListener(ComponentListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.ComponentListener |  |

### addContainerListener(ContainerListener arg0) {#addContainerListener-java.awt.event.ContainerListener-}
```
public synchronized void addContainerListener(ContainerListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.ContainerListener |  |

### addFocusListener(FocusListener arg0) {#addFocusListener-java.awt.event.FocusListener-}
```
public synchronized void addFocusListener(FocusListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.FocusListener |  |

### addHierarchyBoundsListener(HierarchyBoundsListener arg0) {#addHierarchyBoundsListener-java.awt.event.HierarchyBoundsListener-}
```
public void addHierarchyBoundsListener(HierarchyBoundsListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.HierarchyBoundsListener |  |

### addHierarchyListener(HierarchyListener arg0) {#addHierarchyListener-java.awt.event.HierarchyListener-}
```
public void addHierarchyListener(HierarchyListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.HierarchyListener |  |

### addInputMethodListener(InputMethodListener arg0) {#addInputMethodListener-java.awt.event.InputMethodListener-}
```
public synchronized void addInputMethodListener(InputMethodListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.InputMethodListener |  |

### addKeyListener(KeyListener arg0) {#addKeyListener-java.awt.event.KeyListener-}
```
public synchronized void addKeyListener(KeyListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.KeyListener |  |

### addMouseListener(MouseListener arg0) {#addMouseListener-java.awt.event.MouseListener-}
```
public synchronized void addMouseListener(MouseListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseListener |  |

### addMouseMotionListener(MouseMotionListener arg0) {#addMouseMotionListener-java.awt.event.MouseMotionListener-}
```
public synchronized void addMouseMotionListener(MouseMotionListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseMotionListener |  |

### addMouseWheelListener(MouseWheelListener arg0) {#addMouseWheelListener-java.awt.event.MouseWheelListener-}
```
public synchronized void addMouseWheelListener(MouseWheelListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseWheelListener |  |

### addNotify() {#addNotify--}
```
public void addNotify()
```




### addPropertyChangeListener(PropertyChangeListener arg0) {#addPropertyChangeListener-java.beans.PropertyChangeListener-}
```
public void addPropertyChangeListener(PropertyChangeListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.beans.PropertyChangeListener |  |

### addPropertyChangeListener(String arg0, PropertyChangeListener arg1) {#addPropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-}
```
public void addPropertyChangeListener(String arg0, PropertyChangeListener arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | java.beans.PropertyChangeListener |  |

### addVetoableChangeListener(VetoableChangeListener arg0) {#addVetoableChangeListener-java.beans.VetoableChangeListener-}
```
public synchronized void addVetoableChangeListener(VetoableChangeListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.beans.VetoableChangeListener |  |

### applyComponentOrientation(ComponentOrientation arg0) {#applyComponentOrientation-java.awt.ComponentOrientation-}
```
public void applyComponentOrientation(ComponentOrientation arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.ComponentOrientation |  |

### areFocusTraversalKeysSet(int arg0) {#areFocusTraversalKeysSet-int-}
```
public boolean areFocusTraversalKeysSet(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
boolesch
### bounds() {#bounds--}
```
public Rectangle bounds()
```




**Returns:**
java.awt.Rectangle
### checkImage(Image arg0, int arg1, int arg2, ImageObserver arg3) {#checkImage-java.awt.Image-int-int-java.awt.image.ImageObserver-}
```
public int checkImage(Image arg0, int arg1, int arg2, ImageObserver arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Image |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | java.awt.image.ImageObserver |  |

**Returns:**
int
### checkImage(Image arg0, ImageObserver arg1) {#checkImage-java.awt.Image-java.awt.image.ImageObserver-}
```
public int checkImage(Image arg0, ImageObserver arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Image |  |
| arg1 | java.awt.image.ImageObserver |  |

**Returns:**
int
### computeVisibleRect(Rectangle arg0) {#computeVisibleRect-java.awt.Rectangle-}
```
public void computeVisibleRect(Rectangle arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Rectangle |  |

### contains(int arg0, int arg1) {#contains-int-int-}
```
public boolean contains(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
boolesch
### contains(Point arg0) {#contains-java.awt.Point-}
```
public boolean contains(Point arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Point |  |

**Returns:**
boolesch
### countComponents() {#countComponents--}
```
public int countComponents()
```




**Returns:**
int
### createImage(int arg0, int arg1) {#createImage-int-int-}
```
public Image createImage(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.awt.Image
### createImage(ImageProducer arg0) {#createImage-java.awt.image.ImageProducer-}
```
public Image createImage(ImageProducer arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.image.ImageProducer |  |

**Returns:**
java.awt.Image
### createToolTip() {#createToolTip--}
```
public JToolTip createToolTip()
```




**Returns:**
javax.swing.JToolTip
### createVolatileImage(int arg0, int arg1) {#createVolatileImage-int-int-}
```
public VolatileImage createVolatileImage(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.awt.image.VolatileImage
### createVolatileImage(int arg0, int arg1, ImageCapabilities arg2) {#createVolatileImage-int-int-java.awt.ImageCapabilities-}
```
public VolatileImage createVolatileImage(int arg0, int arg1, ImageCapabilities arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | java.awt.ImageCapabilities |  |

**Returns:**
java.awt.image.VolatileImage
### deliverEvent(Event arg0) {#deliverEvent-java.awt.Event-}
```
public void deliverEvent(Event arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |

### disable() {#disable--}
```
public void disable()
```




### dispatchEvent(AWTEvent arg0) {#dispatchEvent-java.awt.AWTEvent-}
```
public final void dispatchEvent(AWTEvent arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.AWTEvent |  |

### doLayout() {#doLayout--}
```
public void doLayout()
```




### enable() {#enable--}
```
public void enable()
```




### enable(boolean arg0) {#enable-boolean-}
```
public void enable(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### enableInputMethods(boolean arg0) {#enableInputMethods-boolean-}
```
public void enableInputMethods(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### findComponentAt(int arg0, int arg1) {#findComponentAt-int-int-}
```
public Component findComponentAt(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.awt.Component
### findComponentAt(Point arg0) {#findComponentAt-java.awt.Point-}
```
public Component findComponentAt(Point arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Point |  |

**Returns:**
java.awt.Component
### firePropertyChange(String arg0, boolean arg1, boolean arg2) {#firePropertyChange-java.lang.String-boolean-boolean-}
```
public void firePropertyChange(String arg0, boolean arg1, boolean arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | boolesch |  |
| arg2 | boolesch |  |

### firePropertyChange(String arg0, byte arg1, byte arg2) {#firePropertyChange-java.lang.String-byte-byte-}
```
public void firePropertyChange(String arg0, byte arg1, byte arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | byte |  |
| arg2 | byte |  |

### firePropertyChange(String arg0, char arg1, char arg2) {#firePropertyChange-java.lang.String-char-char-}
```
public void firePropertyChange(String arg0, char arg1, char arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | char |  |
| arg2 | char |  |

### firePropertyChange(String arg0, double arg1, double arg2) {#firePropertyChange-java.lang.String-double-double-}
```
public void firePropertyChange(String arg0, double arg1, double arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | double |  |
| arg2 | double |  |

### firePropertyChange(String arg0, float arg1, float arg2) {#firePropertyChange-java.lang.String-float-float-}
```
public void firePropertyChange(String arg0, float arg1, float arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | float |  |
| arg2 | float |  |

### firePropertyChange(String arg0, int arg1, int arg2) {#firePropertyChange-java.lang.String-int-int-}
```
public void firePropertyChange(String arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |
| arg2 | int |  |

### firePropertyChange(String arg0, long arg1, long arg2) {#firePropertyChange-java.lang.String-long-long-}
```
public void firePropertyChange(String arg0, long arg1, long arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | long |  |
| arg2 | long |  |

### firePropertyChange(String arg0, short arg1, short arg2) {#firePropertyChange-java.lang.String-short-short-}
```
public void firePropertyChange(String arg0, short arg1, short arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | short |  |
| arg2 | short |  |

### getAccessibleContext() {#getAccessibleContext--}
```
public AccessibleContext getAccessibleContext()
```




**Returns:**
javax.accessibility.AccessibleContext
### getActionForKeyStroke(KeyStroke arg0) {#getActionForKeyStroke-javax.swing.KeyStroke-}
```
public ActionListener getActionForKeyStroke(KeyStroke arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.KeyStroke |  |

**Returns:**
java.awt.event.ActionListener
### getActionMap() {#getActionMap--}
```
public final ActionMap getActionMap()
```




**Returns:**
javax.swing.ActionMap
### getAlignmentX() {#getAlignmentX--}
```
public float getAlignmentX()
```




**Returns:**
float
### getAlignmentY() {#getAlignmentY--}
```
public float getAlignmentY()
```




**Returns:**
float
### getAncestorListeners() {#getAncestorListeners--}
```
public AncestorListener[] getAncestorListeners()
```




**Returns:**
javax.swing.event.AncestorListener[]
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Ermittelt den Modus, mit dem der Barcode automatisch skaliert wird. Der Standardwert ist AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getAutoscrolls() {#getAutoscrolls--}
```
public boolean getAutoscrolls()
```




**Returns:**
boolesch
### getBackground() {#getBackground--}
```
public Color getBackground()
```




**Returns:**
java.awt.Color
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hintergrundfarbe des Barcode-Bildes.

**Returns:**
java.awt.Color
### getBarCodeHeight() {#getBarCodeHeight--}
```
public Unit getBarCodeHeight()
```


Barcode-Bildhöhe, wenn die Eigenschaft com.aspose.barcode.generation.AutoSizeMode auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarCodeWidth() {#getBarCodeWidth--}
```
public Unit getBarCodeWidth()
```


Barcode-Bildbreite, wenn die Eigenschaft com.aspose.barcode.generation.AutoSizeMode auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarColor() {#getBarColor--}
```
public Color getBarColor()
```


Farbe der Balken.

**Returns:**
java.awt.Color
### getBarHeight() {#getBarHeight--}
```
public Unit getBarHeight()
```


Höhe der Balken von 1D-Barcodes. Ignoriert, wenn die Eigenschaft com.aspose.barcode.generation.AutoSizeMode auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarcodePaddings() {#getBarcodePaddings--}
```
public Padding getBarcodePaddings()
```


Ruft die Barcode‑Abstandparameter com.aspose.barcode.generation.Padding ab.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getBarcodeType() {#getBarcodeType--}
```
public String getBarcodeType()
```


Kodierungstyp des BarCodes (Symbolik). Verwenden Sie com.aspose.barcode.generation.EncodeTypes, um die aktuelle Symbolik zu erhalten.

**Returns:**
java.lang.String
### getBaseline(int arg0, int arg1) {#getBaseline-int-int-}
```
public int getBaseline(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
int
### getBaselineResizeBehavior() {#getBaselineResizeBehavior--}
```
public Component.BaselineResizeBehavior getBaselineResizeBehavior()
```




**Returns:**
java.awt.Component.BaselineResizeBehavior
### getBorder() {#getBorder--}
```
public Border getBorder()
```




**Returns:**
javax.swing.border.Border
### getBorderParameters() {#getBorderParameters--}
```
public BorderParameters getBorderParameters()
```


Ruft die Randparameter com.aspose.barcode.generation.BorderParameters ab.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```




**Returns:**
java.awt.Rectangle
### getBounds(Rectangle arg0) {#getBounds-java.awt.Rectangle-}
```
public Rectangle getBounds(Rectangle arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Rectangle |  |

**Returns:**
java.awt.Rectangle
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionUI getCaptionAbove()
```


Beschriftung über dem BarCode-Bild. Siehe com.aspose.barcode.generation.CaptionParameters.

**Returns:**
[CaptionUI](../../com.aspose.barcode.barcodecontrol/captionui)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionUI getCaptionBelow()
```


Beschriftung über dem BarCode-Bild. Siehe com.aspose.barcode.generation.CaptionParameters.

**Returns:**
[CaptionUI](../../com.aspose.barcode.barcodecontrol/captionui)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public boolean getChecksumAlwaysShow()
```


Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes an.

**Returns:**
boolesch
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientProperty(Object arg0) {#getClientProperty-java.lang.Object-}
```
public final Object getClientProperty(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
java.lang.Object
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Zu codierende Daten; verschiedene Barcode‑Typen können unterschiedliche Längenbeschränkungen für den CodeText haben.

**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public CodetextParametersUI getCodeTextParameters()
```


Ruft die CodeText‑Parameter com.aspose.barcode.generation.CodetextParameters ab.

**Returns:**
[CodetextParametersUI](../../com.aspose.barcode.barcodecontrol/codetextparametersui)
### getColorModel() {#getColorModel--}
```
public ColorModel getColorModel()
```




**Returns:**
java.awt.image.ColorModel
### getComponent(int arg0) {#getComponent-int-}
```
public Component getComponent(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.awt.Component
### getComponentAt(int arg0, int arg1) {#getComponentAt-int-int-}
```
public Component getComponentAt(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.awt.Component
### getComponentAt(Point arg0) {#getComponentAt-java.awt.Point-}
```
public Component getComponentAt(Point arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Point |  |

**Returns:**
java.awt.Component
### getComponentCount() {#getComponentCount--}
```
public int getComponentCount()
```




**Returns:**
int
### getComponentListeners() {#getComponentListeners--}
```
public synchronized ComponentListener[] getComponentListeners()
```




**Returns:**
java.awt.event.ComponentListener[]
### getComponentOrientation() {#getComponentOrientation--}
```
public ComponentOrientation getComponentOrientation()
```




**Returns:**
java.awt.ComponentOrientation
### getComponentPopupMenu() {#getComponentPopupMenu--}
```
public JPopupMenu getComponentPopupMenu()
```




**Returns:**
javax.swing.JPopupMenu
### getComponentZOrder(Component arg0) {#getComponentZOrder-java.awt.Component-}
```
public int getComponentZOrder(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

**Returns:**
int
### getComponents() {#getComponents--}
```
public Component[] getComponents()
```




**Returns:**
java.awt.Component[]
### getConditionForKeyStroke(KeyStroke arg0) {#getConditionForKeyStroke-javax.swing.KeyStroke-}
```
public int getConditionForKeyStroke(KeyStroke arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.KeyStroke |  |

**Returns:**
int
### getContainerListeners() {#getContainerListeners--}
```
public synchronized ContainerListener[] getContainerListeners()
```




**Returns:**
java.awt.event.ContainerListener[]
### getCursor() {#getCursor--}
```
public Cursor getCursor()
```




**Returns:**
java.awt.Cursor
### getDebugGraphicsOptions() {#getDebugGraphicsOptions--}
```
public int getDebugGraphicsOptions()
```




**Returns:**
int
### getDefaultLocale() {#getDefaultLocale--}
```
public static Locale getDefaultLocale()
```




**Returns:**
java.util.Locale
### getDisabledIcon() {#getDisabledIcon--}
```
public Icon getDisabledIcon()
```




**Returns:**
javax.swing.Icon
### getDisplayedMnemonic() {#getDisplayedMnemonic--}
```
public int getDisplayedMnemonic()
```




**Returns:**
int
### getDisplayedMnemonicIndex() {#getDisplayedMnemonicIndex--}
```
public int getDisplayedMnemonicIndex()
```




**Returns:**
int
### getDropTarget() {#getDropTarget--}
```
public synchronized DropTarget getDropTarget()
```




**Returns:**
java.awt.dnd.DropTarget
### getEncodeType() {#getEncodeType--}
```
public BaseEncodeType getEncodeType()
```


Kodierungstyp des BarCodes (Symbolik). Verwenden Sie com.aspose.barcode.generation.EncodeTypes, um die aktuelle Symbolik zu erhalten.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getFilledBars() {#getFilledBars--}
```
public boolean getFilledBars()
```


Ermittelt einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes.

**Returns:**
boolesch
### getFocusCycleRootAncestor() {#getFocusCycleRootAncestor--}
```
public Container getFocusCycleRootAncestor()
```




**Returns:**
java.awt.Container
### getFocusListeners() {#getFocusListeners--}
```
public synchronized FocusListener[] getFocusListeners()
```




**Returns:**
java.awt.event.FocusListener[]
### getFocusTraversalKeys(int arg0) {#getFocusTraversalKeys-int-}
```
public Set<AWTKeyStroke> getFocusTraversalKeys(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.util.Set<java.awt.AWTKeyStroke>
### getFocusTraversalKeysEnabled() {#getFocusTraversalKeysEnabled--}
```
public boolean getFocusTraversalKeysEnabled()
```




**Returns:**
boolesch
### getFocusTraversalPolicy() {#getFocusTraversalPolicy--}
```
public FocusTraversalPolicy getFocusTraversalPolicy()
```




**Returns:**
java.awt.FocusTraversalPolicy
### getFont() {#getFont--}
```
public Font getFont()
```




**Returns:**
java.awt.Font
### getFontMetrics(Font arg0) {#getFontMetrics-java.awt.Font-}
```
public FontMetrics getFontMetrics(Font arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Font |  |

**Returns:**
java.awt.FontMetrics
### getForeground() {#getForeground--}
```
public Color getForeground()
```




**Returns:**
java.awt.Color
### getGraphics() {#getGraphics--}
```
public Graphics getGraphics()
```




**Returns:**
java.awt.Graphics
### getGraphicsConfiguration() {#getGraphicsConfiguration--}
```
public GraphicsConfiguration getGraphicsConfiguration()
```




**Returns:**
java.awt.GraphicsConfiguration
### getHeight() {#getHeight--}
```
public int getHeight()
```




**Returns:**
int
### getHierarchyBoundsListeners() {#getHierarchyBoundsListeners--}
```
public synchronized HierarchyBoundsListener[] getHierarchyBoundsListeners()
```




**Returns:**
java.awt.event.HierarchyBoundsListener[]
### getHierarchyListeners() {#getHierarchyListeners--}
```
public synchronized HierarchyListener[] getHierarchyListeners()
```




**Returns:**
java.awt.event.HierarchyListener[]
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```




**Returns:**
int
### getHorizontalTextPosition() {#getHorizontalTextPosition--}
```
public int getHorizontalTextPosition()
```




**Returns:**
int
### getIcon() {#getIcon--}
```
public Icon getIcon()
```




**Returns:**
javax.swing.Icon
### getIconTextGap() {#getIconTextGap--}
```
public int getIconTextGap()
```




**Returns:**
int
### getIgnoreRepaint() {#getIgnoreRepaint--}
```
public boolean getIgnoreRepaint()
```




**Returns:**
boolesch
### getInheritsPopupMenu() {#getInheritsPopupMenu--}
```
public boolean getInheritsPopupMenu()
```




**Returns:**
boolesch
### getInputContext() {#getInputContext--}
```
public InputContext getInputContext()
```




**Returns:**
java.awt.im.InputContext
### getInputMap() {#getInputMap--}
```
public final InputMap getInputMap()
```




**Returns:**
javax.swing.InputMap
### getInputMap(int arg0) {#getInputMap-int-}
```
public final InputMap getInputMap(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
javax.swing.InputMap
### getInputMethodListeners() {#getInputMethodListeners--}
```
public synchronized InputMethodListener[] getInputMethodListeners()
```




**Returns:**
java.awt.event.InputMethodListener[]
### getInputMethodRequests() {#getInputMethodRequests--}
```
public InputMethodRequests getInputMethodRequests()
```




**Returns:**
java.awt.im.InputMethodRequests
### getInputVerifier() {#getInputVerifier--}
```
public InputVerifier getInputVerifier()
```




**Returns:**
javax.swing.InputVerifier
### getInsets() {#getInsets--}
```
public Insets getInsets()
```




**Returns:**
java.awt.Insets
### getInsets(Insets arg0) {#getInsets-java.awt.Insets-}
```
public Insets getInsets(Insets arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Insets |  |

**Returns:**
java.awt.Insets
### getKeyListeners() {#getKeyListeners--}
```
public synchronized KeyListener[] getKeyListeners()
```




**Returns:**
java.awt.event.KeyListener[]
### getLabelFor() {#getLabelFor--}
```
public Component getLabelFor()
```




**Returns:**
java.awt.Component
### getLayout() {#getLayout--}
```
public LayoutManager getLayout()
```




**Returns:**
java.awt.LayoutManager
### getLocale() {#getLocale--}
```
public Locale getLocale()
```




**Returns:**
java.util.Locale
### getLocation() {#getLocation--}
```
public Point getLocation()
```




**Returns:**
java.awt.Point
### getLocation(Point arg0) {#getLocation-java.awt.Point-}
```
public Point getLocation(Point arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Point |  |

**Returns:**
java.awt.Point
### getLocationOnScreen() {#getLocationOnScreen--}
```
public Point getLocationOnScreen()
```




**Returns:**
java.awt.Point
### getMaximumSize() {#getMaximumSize--}
```
public Dimension getMaximumSize()
```




**Returns:**
java.awt.Dimension
### getMinimumSize() {#getMinimumSize--}
```
public Dimension getMinimumSize()
```




**Returns:**
java.awt.Dimension
### getMouseListeners() {#getMouseListeners--}
```
public synchronized MouseListener[] getMouseListeners()
```




**Returns:**
java.awt.event.MouseListener[]
### getMouseMotionListeners() {#getMouseMotionListeners--}
```
public synchronized MouseMotionListener[] getMouseMotionListeners()
```




**Returns:**
java.awt.event.MouseMotionListener[]
### getMousePosition() {#getMousePosition--}
```
public Point getMousePosition()
```




**Returns:**
java.awt.Point
### getMousePosition(boolean arg0) {#getMousePosition-boolean-}
```
public Point getMousePosition(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

**Returns:**
java.awt.Point
### getMouseWheelListeners() {#getMouseWheelListeners--}
```
public synchronized MouseWheelListener[] getMouseWheelListeners()
```




**Returns:**
java.awt.event.MouseWheelListener[]
### getName() {#getName--}
```
public String getName()
```




**Returns:**
java.lang.String
### getNextFocusableComponent() {#getNextFocusableComponent--}
```
public Component getNextFocusableComponent()
```




**Returns:**
java.awt.Component
### getParent() {#getParent--}
```
public Container getParent()
```




**Returns:**
java.awt.Container
### getPopupLocation(MouseEvent arg0) {#getPopupLocation-java.awt.event.MouseEvent-}
```
public Point getPopupLocation(MouseEvent arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseEvent |  |

**Returns:**
java.awt.Point
### getPreferredSize() {#getPreferredSize--}
```
public Dimension getPreferredSize()
```




**Returns:**
java.awt.Dimension
### getPropertyChangeListeners() {#getPropertyChangeListeners--}
```
public PropertyChangeListener[] getPropertyChangeListeners()
```




**Returns:**
java.beans.PropertyChangeListener[]
### getPropertyChangeListeners(String arg0) {#getPropertyChangeListeners-java.lang.String-}
```
public PropertyChangeListener[] getPropertyChangeListeners(String arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.beans.PropertyChangeListener[]
### getRegisteredKeyStrokes() {#getRegisteredKeyStrokes--}
```
public KeyStroke[] getRegisteredKeyStrokes()
```




**Returns:**
javax.swing.KeyStroke[]
### getResolution() {#getResolution--}
```
public float getResolution()
```


Ermittelt die Auflösung des BarCode-Bildes. Ein Wert für beide Dimensionen. Standardwert: 96 dpi.

**Returns:**
float – Der Wert des Parameters **Resolution** ist kleiner oder gleich 0.
### getRootPane() {#getRootPane--}
```
public JRootPane getRootPane()
```




**Returns:**
javax.swing.JRootPane
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Der Rotationswinkel des BarCode-Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen.

**Returns:**
float
### getSize() {#getSize--}
```
public Dimension getSize()
```




**Returns:**
java.awt.Dimension
### getSize(Dimension arg0) {#getSize-java.awt.Dimension-}
```
public Dimension getSize(Dimension arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Dimension |  |

**Returns:**
java.awt.Dimension
### getSpecific() {#getSpecific--}
```
public SpecificParametersUI getSpecific()
```


Spezifische Parameter

**Returns:**
[SpecificParametersUI](../../com.aspose.barcode.barcodecontrol/specificparametersui)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public boolean getThrowExceptionWhenCodeTextIncorrect()
```


Nur für 1D-Barcodes. Wenn der codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Eine Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der codetext inkorrekt ist. Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128-Symbologie, wenn der codetext inkorrekt ist.

**Returns:**
boolesch
### getToolTipLocation(MouseEvent arg0) {#getToolTipLocation-java.awt.event.MouseEvent-}
```
public Point getToolTipLocation(MouseEvent arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseEvent |  |

**Returns:**
java.awt.Point
### getToolTipText() {#getToolTipText--}
```
public String getToolTipText()
```




**Returns:**
java.lang.String
### getToolTipText(MouseEvent arg0) {#getToolTipText-java.awt.event.MouseEvent-}
```
public String getToolTipText(MouseEvent arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseEvent |  |

**Returns:**
java.lang.String
### getToolkit() {#getToolkit--}
```
public Toolkit getToolkit()
```




**Returns:**
java.awt.Toolkit
### getTopLevelAncestor() {#getTopLevelAncestor--}
```
public Container getTopLevelAncestor()
```




**Returns:**
java.awt.Container
### getTransferHandler() {#getTransferHandler--}
```
public TransferHandler getTransferHandler()
```




**Returns:**
javax.swing.TransferHandler
### getTreeLock() {#getTreeLock--}
```
public final Object getTreeLock()
```




**Returns:**
java.lang.Object
### getUI() {#getUI--}
```
public LabelUI getUI()
```




**Returns:**
javax.swing.plaf.LabelUI
### getUIClassID() {#getUIClassID--}
```
public String getUIClassID()
```




**Returns:**
java.lang.String
### getVerifyInputWhenFocusTarget() {#getVerifyInputWhenFocusTarget--}
```
public boolean getVerifyInputWhenFocusTarget()
```




**Returns:**
boolesch
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```




**Returns:**
int
### getVerticalTextPosition() {#getVerticalTextPosition--}
```
public int getVerticalTextPosition()
```




**Returns:**
int
### getVetoableChangeListeners() {#getVetoableChangeListeners--}
```
public synchronized VetoableChangeListener[] getVetoableChangeListeners()
```




**Returns:**
java.beans.VetoableChangeListener[]
### getVisibleRect() {#getVisibleRect--}
```
public Rectangle getVisibleRect()
```




**Returns:**
java.awt.Rectangle
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public float getWideNarrowRatio()
```


Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind 3‑mal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard

**Returns:**
float – Der Wert des Parameters **WideNarrowRatio** ist kleiner oder gleich 0.
### getWidth() {#getWidth--}
```
public int getWidth()
```




**Returns:**
int
### getX() {#getX--}
```
public int getX()
```




**Returns:**
int
### getXDimension() {#getXDimension--}
```
public Unit getXDimension()
```


Die X‑Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft com.aspose.barcode.generation.AutoSizeMode auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getY() {#getY--}
```
public int getY()
```




**Returns:**
int
### gotFocus(Event arg0, Object arg1) {#gotFocus-java.awt.Event-java.lang.Object-}
```
public boolean gotFocus(Event arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolesch
### grabFocus() {#grabFocus--}
```
public void grabFocus()
```




### handleEvent(Event arg0) {#handleEvent-java.awt.Event-}
```
public boolean handleEvent(Event arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |

**Returns:**
boolesch
### hasFocus() {#hasFocus--}
```
public boolean hasFocus()
```




**Returns:**
boolesch
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### hide() {#hide--}
```
public void hide()
```




### imageUpdate(Image arg0, int arg1, int arg2, int arg3, int arg4, int arg5) {#imageUpdate-java.awt.Image-int-int-int-int-int-}
```
public boolean imageUpdate(Image arg0, int arg1, int arg2, int arg3, int arg4, int arg5)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Image |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |
| arg4 | int |  |
| arg5 | int |  |

**Returns:**
boolesch
### insets() {#insets--}
```
public Insets insets()
```




**Returns:**
java.awt.Insets
### inside(int arg0, int arg1) {#inside-int-int-}
```
public boolean inside(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
boolesch
### invalidate() {#invalidate--}
```
public void invalidate()
```




### isAncestorOf(Component arg0) {#isAncestorOf-java.awt.Component-}
```
public boolean isAncestorOf(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

**Returns:**
boolesch
### isBackgroundSet() {#isBackgroundSet--}
```
public boolean isBackgroundSet()
```




**Returns:**
boolesch
### isChecksumEnabled() {#isChecksumEnabled--}
```
public EnableChecksum isChecksumEnabled()
```




**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### isCursorSet() {#isCursorSet--}
```
public boolean isCursorSet()
```




**Returns:**
boolesch
### isDisplayable() {#isDisplayable--}
```
public boolean isDisplayable()
```




**Returns:**
boolesch
### isDoubleBuffered() {#isDoubleBuffered--}
```
public boolean isDoubleBuffered()
```




**Returns:**
boolesch
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```




**Returns:**
boolesch
### isFocusCycleRoot() {#isFocusCycleRoot--}
```
public boolean isFocusCycleRoot()
```




**Returns:**
boolesch
### isFocusCycleRoot(Container arg0) {#isFocusCycleRoot-java.awt.Container-}
```
public boolean isFocusCycleRoot(Container arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Container |  |

**Returns:**
boolesch
### isFocusOwner() {#isFocusOwner--}
```
public boolean isFocusOwner()
```




**Returns:**
boolesch
### isFocusTraversable() {#isFocusTraversable--}
```
public boolean isFocusTraversable()
```




**Returns:**
boolesch
### isFocusTraversalPolicyProvider() {#isFocusTraversalPolicyProvider--}
```
public final boolean isFocusTraversalPolicyProvider()
```




**Returns:**
boolesch
### isFocusTraversalPolicySet() {#isFocusTraversalPolicySet--}
```
public boolean isFocusTraversalPolicySet()
```




**Returns:**
boolesch
### isFocusable() {#isFocusable--}
```
public boolean isFocusable()
```




**Returns:**
boolesch
### isFontSet() {#isFontSet--}
```
public boolean isFontSet()
```




**Returns:**
boolesch
### isForegroundSet() {#isForegroundSet--}
```
public boolean isForegroundSet()
```




**Returns:**
boolesch
### isLightweight() {#isLightweight--}
```
public boolean isLightweight()
```




**Returns:**
boolesch
### isLightweightComponent(Component arg0) {#isLightweightComponent-java.awt.Component-}
```
public static boolean isLightweightComponent(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

**Returns:**
boolesch
### isManagingFocus() {#isManagingFocus--}
```
public boolean isManagingFocus()
```




**Returns:**
boolesch
### isMaximumSizeSet() {#isMaximumSizeSet--}
```
public boolean isMaximumSizeSet()
```




**Returns:**
boolesch
### isMinimumSizeSet() {#isMinimumSizeSet--}
```
public boolean isMinimumSizeSet()
```




**Returns:**
boolesch
### isOpaque() {#isOpaque--}
```
public boolean isOpaque()
```




**Returns:**
boolesch
### isOptimizedDrawingEnabled() {#isOptimizedDrawingEnabled--}
```
public boolean isOptimizedDrawingEnabled()
```




**Returns:**
boolesch
### isPaintingForPrint() {#isPaintingForPrint--}
```
public final boolean isPaintingForPrint()
```




**Returns:**
boolesch
### isPaintingTile() {#isPaintingTile--}
```
public boolean isPaintingTile()
```




**Returns:**
boolesch
### isPreferredSizeSet() {#isPreferredSizeSet--}
```
public boolean isPreferredSizeSet()
```




**Returns:**
boolesch
### isRequestFocusEnabled() {#isRequestFocusEnabled--}
```
public boolean isRequestFocusEnabled()
```




**Returns:**
boolesch
### isShowing() {#isShowing--}
```
public boolean isShowing()
```




**Returns:**
boolesch
### isUseAntiAlias() {#isUseAntiAlias--}
```
public boolean isUseAntiAlias()
```


Ruft einen Wert ab, der angibt, ob ein Anti‑Aliasing‑Modus zum Rendern des Bildes verwendet wird.

**Returns:**
boolesch
### isValid() {#isValid--}
```
public boolean isValid()
```




**Returns:**
boolesch
### isValidateRoot() {#isValidateRoot--}
```
public boolean isValidateRoot()
```




**Returns:**
boolesch
### isVisible() {#isVisible--}
```
public boolean isVisible()
```




**Returns:**
boolesch
### keyDown(Event arg0, int arg1) {#keyDown-java.awt.Event-int-}
```
public boolean keyDown(Event arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |

**Returns:**
boolesch
### keyUp(Event arg0, int arg1) {#keyUp-java.awt.Event-int-}
```
public boolean keyUp(Event arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |

**Returns:**
boolesch
### layout() {#layout--}
```
public void layout()
```




### list() {#list--}
```
public void list()
```




### list(PrintStream arg0) {#list-java.io.PrintStream-}
```
public void list(PrintStream arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### list(PrintStream arg0, int arg1) {#list-java.io.PrintStream-int-}
```
public void list(PrintStream arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |
| arg1 | int |  |

### list(PrintWriter arg0) {#list-java.io.PrintWriter-}
```
public void list(PrintWriter arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### list(PrintWriter arg0, int arg1) {#list-java.io.PrintWriter-int-}
```
public void list(PrintWriter arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |
| arg1 | int |  |

### locate(int arg0, int arg1) {#locate-int-int-}
```
public Component locate(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.awt.Component
### location() {#location--}
```
public Point location()
```




**Returns:**
java.awt.Point
### lostFocus(Event arg0, Object arg1) {#lostFocus-java.awt.Event-java.lang.Object-}
```
public boolean lostFocus(Event arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolesch
### minimumSize() {#minimumSize--}
```
public Dimension minimumSize()
```




**Returns:**
java.awt.Dimension
### mouseDown(Event arg0, int arg1, int arg2) {#mouseDown-java.awt.Event-int-int-}
```
public boolean mouseDown(Event arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
boolesch
### mouseDrag(Event arg0, int arg1, int arg2) {#mouseDrag-java.awt.Event-int-int-}
```
public boolean mouseDrag(Event arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
boolesch
### mouseEnter(Event arg0, int arg1, int arg2) {#mouseEnter-java.awt.Event-int-int-}
```
public boolean mouseEnter(Event arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
boolesch
### mouseExit(Event arg0, int arg1, int arg2) {#mouseExit-java.awt.Event-int-int-}
```
public boolean mouseExit(Event arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
boolesch
### mouseMove(Event arg0, int arg1, int arg2) {#mouseMove-java.awt.Event-int-int-}
```
public boolean mouseMove(Event arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
boolesch
### mouseUp(Event arg0, int arg1, int arg2) {#mouseUp-java.awt.Event-int-int-}
```
public boolean mouseUp(Event arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
boolesch
### move(int arg0, int arg1) {#move-int-int-}
```
public void move(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### nextFocus() {#nextFocus--}
```
public void nextFocus()
```




### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### paint(Graphics arg0) {#paint-java.awt.Graphics-}
```
public void paint(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### paintAll(Graphics arg0) {#paintAll-java.awt.Graphics-}
```
public void paintAll(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### paintComponents(Graphics arg0) {#paintComponents-java.awt.Graphics-}
```
public void paintComponents(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### paintImmediately(int arg0, int arg1, int arg2, int arg3) {#paintImmediately-int-int-int-int-}
```
public void paintImmediately(int arg0, int arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |

### paintImmediately(Rectangle arg0) {#paintImmediately-java.awt.Rectangle-}
```
public void paintImmediately(Rectangle arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Rectangle |  |

### postEvent(Event arg0) {#postEvent-java.awt.Event-}
```
public boolean postEvent(Event arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Event |  |

**Returns:**
boolesch
### preferredSize() {#preferredSize--}
```
public Dimension preferredSize()
```




**Returns:**
java.awt.Dimension
### prepareImage(Image arg0, int arg1, int arg2, ImageObserver arg3) {#prepareImage-java.awt.Image-int-int-java.awt.image.ImageObserver-}
```
public boolean prepareImage(Image arg0, int arg1, int arg2, ImageObserver arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Image |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | java.awt.image.ImageObserver |  |

**Returns:**
boolesch
### prepareImage(Image arg0, ImageObserver arg1) {#prepareImage-java.awt.Image-java.awt.image.ImageObserver-}
```
public boolean prepareImage(Image arg0, ImageObserver arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Image |  |
| arg1 | java.awt.image.ImageObserver |  |

**Returns:**
boolesch
### print(Graphics arg0) {#print-java.awt.Graphics-}
```
public void print(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### printAll(Graphics arg0) {#printAll-java.awt.Graphics-}
```
public void printAll(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### printComponents(Graphics arg0) {#printComponents-java.awt.Graphics-}
```
public void printComponents(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### putClientProperty(Object arg0, Object arg1) {#putClientProperty-java.lang.Object-java.lang.Object-}
```
public final void putClientProperty(Object arg0, Object arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |
| arg1 | java.lang.Object |  |

### registerKeyboardAction(ActionListener arg0, String arg1, KeyStroke arg2, int arg3) {#registerKeyboardAction-java.awt.event.ActionListener-java.lang.String-javax.swing.KeyStroke-int-}
```
public void registerKeyboardAction(ActionListener arg0, String arg1, KeyStroke arg2, int arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.ActionListener |  |
| arg1 | java.lang.String |  |
| arg2 | javax.swing.KeyStroke |  |
| arg3 | int |  |

### registerKeyboardAction(ActionListener arg0, KeyStroke arg1, int arg2) {#registerKeyboardAction-java.awt.event.ActionListener-javax.swing.KeyStroke-int-}
```
public void registerKeyboardAction(ActionListener arg0, KeyStroke arg1, int arg2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.ActionListener |  |
| arg1 | javax.swing.KeyStroke |  |
| arg2 | int |  |

### remove(int arg0) {#remove-int-}
```
public void remove(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### remove(Component arg0) {#remove-java.awt.Component-}
```
public void remove(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

### remove(MenuComponent arg0) {#remove-java.awt.MenuComponent-}
```
public void remove(MenuComponent arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.MenuComponent |  |

### removeAll() {#removeAll--}
```
public void removeAll()
```




### removeAncestorListener(AncestorListener arg0) {#removeAncestorListener-javax.swing.event.AncestorListener-}
```
public void removeAncestorListener(AncestorListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.event.AncestorListener |  |

### removeComponentListener(ComponentListener arg0) {#removeComponentListener-java.awt.event.ComponentListener-}
```
public synchronized void removeComponentListener(ComponentListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.ComponentListener |  |

### removeContainerListener(ContainerListener arg0) {#removeContainerListener-java.awt.event.ContainerListener-}
```
public synchronized void removeContainerListener(ContainerListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.ContainerListener |  |

### removeFocusListener(FocusListener arg0) {#removeFocusListener-java.awt.event.FocusListener-}
```
public synchronized void removeFocusListener(FocusListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.FocusListener |  |

### removeHierarchyBoundsListener(HierarchyBoundsListener arg0) {#removeHierarchyBoundsListener-java.awt.event.HierarchyBoundsListener-}
```
public void removeHierarchyBoundsListener(HierarchyBoundsListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.HierarchyBoundsListener |  |

### removeHierarchyListener(HierarchyListener arg0) {#removeHierarchyListener-java.awt.event.HierarchyListener-}
```
public void removeHierarchyListener(HierarchyListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.HierarchyListener |  |

### removeInputMethodListener(InputMethodListener arg0) {#removeInputMethodListener-java.awt.event.InputMethodListener-}
```
public synchronized void removeInputMethodListener(InputMethodListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.InputMethodListener |  |

### removeKeyListener(KeyListener arg0) {#removeKeyListener-java.awt.event.KeyListener-}
```
public synchronized void removeKeyListener(KeyListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.KeyListener |  |

### removeMouseListener(MouseListener arg0) {#removeMouseListener-java.awt.event.MouseListener-}
```
public synchronized void removeMouseListener(MouseListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseListener |  |

### removeMouseMotionListener(MouseMotionListener arg0) {#removeMouseMotionListener-java.awt.event.MouseMotionListener-}
```
public synchronized void removeMouseMotionListener(MouseMotionListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseMotionListener |  |

### removeMouseWheelListener(MouseWheelListener arg0) {#removeMouseWheelListener-java.awt.event.MouseWheelListener-}
```
public synchronized void removeMouseWheelListener(MouseWheelListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.MouseWheelListener |  |

### removeNotify() {#removeNotify--}
```
public void removeNotify()
```




### removePropertyChangeListener(PropertyChangeListener arg0) {#removePropertyChangeListener-java.beans.PropertyChangeListener-}
```
public void removePropertyChangeListener(PropertyChangeListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.beans.PropertyChangeListener |  |

### removePropertyChangeListener(String arg0, PropertyChangeListener arg1) {#removePropertyChangeListener-java.lang.String-java.beans.PropertyChangeListener-}
```
public void removePropertyChangeListener(String arg0, PropertyChangeListener arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | java.beans.PropertyChangeListener |  |

### removeVetoableChangeListener(VetoableChangeListener arg0) {#removeVetoableChangeListener-java.beans.VetoableChangeListener-}
```
public synchronized void removeVetoableChangeListener(VetoableChangeListener arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.beans.VetoableChangeListener |  |

### repaint() {#repaint--}
```
public void repaint()
```




### repaint(int arg0, int arg1, int arg2, int arg3) {#repaint-int-int-int-int-}
```
public void repaint(int arg0, int arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |

### repaint(Rectangle arg0) {#repaint-java.awt.Rectangle-}
```
public void repaint(Rectangle arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Rectangle |  |

### repaint(long arg0) {#repaint-long-}
```
public void repaint(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### repaint(long arg0, int arg1, int arg2, int arg3, int arg4) {#repaint-long-int-int-int-int-}
```
public void repaint(long arg0, int arg1, int arg2, int arg3, int arg4)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |
| arg4 | int |  |

### requestDefaultFocus() {#requestDefaultFocus--}
```
public boolean requestDefaultFocus()
```




**Returns:**
boolesch
### requestFocus() {#requestFocus--}
```
public void requestFocus()
```




### requestFocus(boolean arg0) {#requestFocus-boolean-}
```
public boolean requestFocus(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

**Returns:**
boolesch
### requestFocus(FocusEvent.Cause arg0) {#requestFocus-java.awt.event.FocusEvent.Cause-}
```
public void requestFocus(FocusEvent.Cause arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.FocusEvent.Cause |  |

### requestFocusInWindow() {#requestFocusInWindow--}
```
public boolean requestFocusInWindow()
```




**Returns:**
boolesch
### requestFocusInWindow(FocusEvent.Cause arg0) {#requestFocusInWindow-java.awt.event.FocusEvent.Cause-}
```
public boolean requestFocusInWindow(FocusEvent.Cause arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.event.FocusEvent.Cause |  |

**Returns:**
boolesch
### resetKeyboardActions() {#resetKeyboardActions--}
```
public void resetKeyboardActions()
```




### reshape(int arg0, int arg1, int arg2, int arg3) {#reshape-int-int-int-int-}
```
public void reshape(int arg0, int arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |

### resize(int arg0, int arg1) {#resize-int-int-}
```
public void resize(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### resize(Dimension arg0) {#resize-java.awt.Dimension-}
```
public void resize(Dimension arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Dimension |  |

### revalidate() {#revalidate--}
```
public void revalidate()
```




### scrollRectToVisible(Rectangle arg0) {#scrollRectToVisible-java.awt.Rectangle-}
```
public void scrollRectToVisible(Rectangle arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Rectangle |  |

### setActionMap(ActionMap arg0) {#setActionMap-javax.swing.ActionMap-}
```
public final void setActionMap(ActionMap arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.ActionMap |  |

### setAlignmentX(float arg0) {#setAlignmentX-float-}
```
public void setAlignmentX(float arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | float |  |

### setAlignmentY(float arg0) {#setAlignmentY-float-}
```
public void setAlignmentY(float arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | float |  |

### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


Legt den Modus fest, in dem der Barcode automatisch die Größe ändert. Standardwert ist AutoSizeMode.NONE.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setAutoscrolls(boolean arg0) {#setAutoscrolls-boolean-}
```
public void setAutoscrolls(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setBackground(Color arg0) {#setBackground-java.awt.Color-}
```
public void setBackground(Color arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Color |  |

### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color value)
```


Hintergrundfarbe des Barcode-Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setBarColor(Color value) {#setBarColor-java.awt.Color-}
```
public void setBarColor(Color value)
```


Farbe der Balken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setBarcodeType(String value) {#setBarcodeType-java.lang.String-}
```
public void setBarcodeType(String value)
```


Kodierungstyp des BarCodes (Symbolik). Verwenden Sie com.aspose.barcode.generation.EncodeTypes, um die aktuelle Symbolik zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setBorder(Border arg0) {#setBorder-javax.swing.border.Border-}
```
public void setBorder(Border arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.border.Border |  |

### setBounds(int arg0, int arg1, int arg2, int arg3) {#setBounds-int-int-int-int-}
```
public void setBounds(int arg0, int arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |

### setBounds(Rectangle arg0) {#setBounds-java.awt.Rectangle-}
```
public void setBounds(Rectangle arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Rectangle |  |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public void setChecksumAlwaysShow(boolean value)
```


Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public void setChecksumEnabled(EnableChecksum value)
```


Aktivieren Sie die Prüfsumme bei der Erzeugung von 1D‑Barcodes. Standardmäßig wird sie als Ja behandelt für Symbologien, die zwingend eine Prüfsumme enthalten, und als Nein, wo eine Prüfsumme nur optional ist. Prüfsumme ist möglich bei: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codaba. Prüfsumme wird immer verwendet bei: übrige Symbologien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Zu codierende Daten; verschiedene Barcode‑Typen können unterschiedliche Längenbeschränkungen für den CodeText haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setComponentOrientation(ComponentOrientation arg0) {#setComponentOrientation-java.awt.ComponentOrientation-}
```
public void setComponentOrientation(ComponentOrientation arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.ComponentOrientation |  |

### setComponentPopupMenu(JPopupMenu arg0) {#setComponentPopupMenu-javax.swing.JPopupMenu-}
```
public void setComponentPopupMenu(JPopupMenu arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.JPopupMenu |  |

### setComponentZOrder(Component arg0, int arg1) {#setComponentZOrder-java.awt.Component-int-}
```
public void setComponentZOrder(Component arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |
| arg1 | int |  |

### setCursor(Cursor arg0) {#setCursor-java.awt.Cursor-}
```
public void setCursor(Cursor arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Cursor |  |

### setDebugGraphicsOptions(int arg0) {#setDebugGraphicsOptions-int-}
```
public void setDebugGraphicsOptions(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setDefaultLocale(Locale arg0) {#setDefaultLocale-java.util.Locale-}
```
public static void setDefaultLocale(Locale arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.util.Locale |  |

### setDisabledIcon(Icon arg0) {#setDisabledIcon-javax.swing.Icon-}
```
public void setDisabledIcon(Icon arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.Icon |  |

### setDisplayedMnemonic(char arg0) {#setDisplayedMnemonic-char-}
```
public void setDisplayedMnemonic(char arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | char |  |

### setDisplayedMnemonic(int arg0) {#setDisplayedMnemonic-int-}
```
public void setDisplayedMnemonic(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setDisplayedMnemonicIndex(int arg0) {#setDisplayedMnemonicIndex-int-}
```
public void setDisplayedMnemonicIndex(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setDoubleBuffered(boolean arg0) {#setDoubleBuffered-boolean-}
```
public void setDoubleBuffered(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setDropTarget(DropTarget arg0) {#setDropTarget-java.awt.dnd.DropTarget-}
```
public synchronized void setDropTarget(DropTarget arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.dnd.DropTarget |  |

### setEnabled(boolean arg0) {#setEnabled-boolean-}
```
public void setEnabled(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setEncodeType(BaseEncodeType value) {#setEncodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setEncodeType(BaseEncodeType value)
```


Kodierungstyp des BarCodes (Symbolik). Verwenden Sie com.aspose.barcode.generation.EncodeTypes, um die aktuelle Symbolik zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public void setFilledBars(boolean value)
```


Ermittelt einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setFocusCycleRoot(boolean arg0) {#setFocusCycleRoot-boolean-}
```
public void setFocusCycleRoot(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setFocusTraversalKeys(int arg0, Set<? extends AWTKeyStroke> arg1) {#setFocusTraversalKeys-int-java.util.Set---extends-java.awt.AWTKeyStroke--}
```
public void setFocusTraversalKeys(int arg0, Set<? extends AWTKeyStroke> arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.util.Set<? extends java.awt.AWTKeyStroke> |  |

### setFocusTraversalKeysEnabled(boolean arg0) {#setFocusTraversalKeysEnabled-boolean-}
```
public void setFocusTraversalKeysEnabled(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setFocusTraversalPolicy(FocusTraversalPolicy arg0) {#setFocusTraversalPolicy-java.awt.FocusTraversalPolicy-}
```
public void setFocusTraversalPolicy(FocusTraversalPolicy arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.FocusTraversalPolicy |  |

### setFocusTraversalPolicyProvider(boolean arg0) {#setFocusTraversalPolicyProvider-boolean-}
```
public final void setFocusTraversalPolicyProvider(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setFocusable(boolean arg0) {#setFocusable-boolean-}
```
public void setFocusable(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setFont(Font arg0) {#setFont-java.awt.Font-}
```
public void setFont(Font arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Font |  |

### setForeground(Color arg0) {#setForeground-java.awt.Color-}
```
public void setForeground(Color arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Color |  |

### setHorizontalAlignment(int arg0) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setHorizontalTextPosition(int arg0) {#setHorizontalTextPosition-int-}
```
public void setHorizontalTextPosition(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setIcon(Icon arg0) {#setIcon-javax.swing.Icon-}
```
public void setIcon(Icon arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.Icon |  |

### setIconTextGap(int arg0) {#setIconTextGap-int-}
```
public void setIconTextGap(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setIgnoreRepaint(boolean arg0) {#setIgnoreRepaint-boolean-}
```
public void setIgnoreRepaint(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setInheritsPopupMenu(boolean arg0) {#setInheritsPopupMenu-boolean-}
```
public void setInheritsPopupMenu(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setInputMap(int arg0, InputMap arg1) {#setInputMap-int-javax.swing.InputMap-}
```
public final void setInputMap(int arg0, InputMap arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | javax.swing.InputMap |  |

### setInputVerifier(InputVerifier arg0) {#setInputVerifier-javax.swing.InputVerifier-}
```
public void setInputVerifier(InputVerifier arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.InputVerifier |  |

### setLabelFor(Component arg0) {#setLabelFor-java.awt.Component-}
```
public void setLabelFor(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

### setLayout(LayoutManager arg0) {#setLayout-java.awt.LayoutManager-}
```
public void setLayout(LayoutManager arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.LayoutManager |  |

### setLocale(Locale arg0) {#setLocale-java.util.Locale-}
```
public void setLocale(Locale arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.util.Locale |  |

### setLocation(int arg0, int arg1) {#setLocation-int-int-}
```
public void setLocation(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### setLocation(Point arg0) {#setLocation-java.awt.Point-}
```
public void setLocation(Point arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Point |  |

### setMaximumSize(Dimension arg0) {#setMaximumSize-java.awt.Dimension-}
```
public void setMaximumSize(Dimension arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Dimension |  |

### setMinimumSize(Dimension arg0) {#setMinimumSize-java.awt.Dimension-}
```
public void setMinimumSize(Dimension arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Dimension |  |

### setMixingCutoutShape(Shape arg0) {#setMixingCutoutShape-java.awt.Shape-}
```
public void setMixingCutoutShape(Shape arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Shape |  |

### setName(String arg0) {#setName-java.lang.String-}
```
public void setName(String arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### setNextFocusableComponent(Component arg0) {#setNextFocusableComponent-java.awt.Component-}
```
public void setNextFocusableComponent(Component arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Component |  |

### setOpaque(boolean arg0) {#setOpaque-boolean-}
```
public void setOpaque(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setPreferredSize(Dimension arg0) {#setPreferredSize-java.awt.Dimension-}
```
public void setPreferredSize(Dimension arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Dimension |  |

### setRequestFocusEnabled(boolean arg0) {#setRequestFocusEnabled-boolean-}
```
public void setRequestFocusEnabled(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Legt die Auflösung des Barcode‑Bildes fest. Ein Wert für beide Dimensionen. Standardwert: 96 dpi.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert des Parameters **Resolution** ist kleiner oder gleich 0. |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Der Rotationswinkel des BarCode-Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setSize(int arg0, int arg1) {#setSize-int-int-}
```
public void setSize(int arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### setSize(Dimension arg0) {#setSize-java.awt.Dimension-}
```
public void setSize(Dimension arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Dimension |  |

### setText(String arg0) {#setText-java.lang.String-}
```
public void setText(String arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Nur für 1D-Barcodes. Wenn der codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Eine Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der codetext inkorrekt ist. Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128-Symbologie, wenn der codetext inkorrekt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setToolTipText(String arg0) {#setToolTipText-java.lang.String-}
```
public void setToolTipText(String arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### setTransferHandler(TransferHandler arg0) {#setTransferHandler-javax.swing.TransferHandler-}
```
public void setTransferHandler(TransferHandler arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.TransferHandler |  |

### setUI(LabelUI arg0) {#setUI-javax.swing.plaf.LabelUI-}
```
public void setUI(LabelUI arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.plaf.LabelUI |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Legt einen Wert fest, der angibt, ob ein Anti‑Aliasing‑Modus zum Rendern des Bildes verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setVerifyInputWhenFocusTarget(boolean arg0) {#setVerifyInputWhenFocusTarget-boolean-}
```
public void setVerifyInputWhenFocusTarget(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setVerticalAlignment(int arg0) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setVerticalTextPosition(int arg0) {#setVerticalTextPosition-int-}
```
public void setVerticalTextPosition(int arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | int |  |

### setVisible(boolean arg0) {#setVisible-boolean-}
```
public void setVisible(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public void setWideNarrowRatio(float value)
```


Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind 3‑mal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert des Parameters **WideNarrowRatio** ist kleiner oder gleich 0. |

### show() {#show--}
```
public void show()
```




### show(boolean arg0) {#show-boolean-}
```
public void show(boolean arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | boolesch |  |

### size() {#size--}
```
public Dimension size()
```




**Returns:**
java.awt.Dimension
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transferFocus() {#transferFocus--}
```
public void transferFocus()
```




### transferFocusBackward() {#transferFocusBackward--}
```
public void transferFocusBackward()
```




### transferFocusDownCycle() {#transferFocusDownCycle--}
```
public void transferFocusDownCycle()
```




### transferFocusUpCycle() {#transferFocusUpCycle--}
```
public void transferFocusUpCycle()
```




### unregisterKeyboardAction(KeyStroke arg0) {#unregisterKeyboardAction-javax.swing.KeyStroke-}
```
public void unregisterKeyboardAction(KeyStroke arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | javax.swing.KeyStroke |  |

### update(Graphics arg0) {#update-java.awt.Graphics-}
```
public void update(Graphics arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.awt.Graphics |  |

### updateUI() {#updateUI--}
```
public void updateUI()
```




### validate() {#validate--}
```
public void validate()
```




### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

