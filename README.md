let textScript =    `${ textBg === 'true'
                            ? model.textBg(fontColor, fontAlign, fontAlignY, fontSize, text)
                            ? model.textBg(fontColor, fontAlign || 50, fontAlignY || 50, fontSize, text)
                            : '' }
                        ${ textBg === 'true'
                            ? checkText(text, textBgColor, fontAlign, fontAlignY, stroke, strokeWidth)
