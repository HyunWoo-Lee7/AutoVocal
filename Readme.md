# AutoVocal

Python code (Appendix A,C) and Praat scripts(Low, Mid, High) for automatic speech analysis.

## Repository Structure
src/ : Python source code
  Appendix A. 자동음절분석 타임스템프 라벨 기반 자르기.py
  Appendix C. Automatic Voice Diagnosis System.py
praat/ : Praat scripts
  Low_Segmentation.praat
  Mid_Segmentation.praat
  High_Segmentation.praat
csv/ : CSV files (manual and automatic segmentation results)
  
## Usage
### Python
```bash
python src/"Appendix A. 자동음절분석 타임스템프 라벨 기반 자르기.py"
python src/"Appendix C. Automatic Voice Diagnosis System.py"

### Praat Script
```bash
praat praat/"Low_Segmentation.praat"
praat praat/"Mid_Segmentation.praat"
praat praat/"High_Segmentation.praat"

### CSV Files
```bash
 ├─ Manually_Segmented_Low.csv
 ├─ Manually_Segmented_Mid.csv
 ├─ Manually_Segmented_High.csv
 ├─ Auto_Segmented_Low.csv
 ├─ Auto_Segmented_Mid.csv
 └─ Auto_Segmented_High.csv
