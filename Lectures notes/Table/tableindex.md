## Dàn ý:

Giới thiệu vấn đề --> Miêu tả đặc điểm các bảng để giúp người dùng hình dung.

## Bài học: 

Với việc tạo bảng cơ bản sau:  

|Tiêu đề 1|Tiêu đề 2|Tiêu đề 3|
|:--------|:--------|:--------|
|Ô 1|Ô 2|Ô 3|
|Ô kìa|Ô na na|Ô mê lý| 

Ta sẽ sử dụng môi trường **tabular**: 

```tex
\documentclass{article}

\usepackage[utf8]{vietnam}

\begin{document}

\begin{tabular}{c|c|c}
    Tiêu đề 1 & Tiêu đề 2 & Tiêu đề 3  \\
    Ô 1 & Ô 2 & Ô 3 \\
    Ô kìa & Ô na na & Ô mê lý \\ 
\end{tabular}

\end{document}
```

Để căn giữa bảng, ta sẽ đặt môi trường **tabular** vào bên trong môi trường **center**: 

```tex
\documentclass{article}

\usepackage[utf8]{vietnam}

\begin{document}

\begin{center}
    \begin{tabular}{c|c|c}
        Tiêu đề 1 & Tiêu đề 2 & Tiêu đề 3  \\
        Ô 1 & Ô 2 & Ô 3 \\
        Ô kìa & Ô na na & Ô mê lý \\ 
    \end{tabular}
\end{center}

\end{document}
```

## Tài liệu tham khảo: 

\[1]: [Tables](https://www.overleaf.com/learn/latex/Tables%23Positioning_tables) từ trang Overleaf.