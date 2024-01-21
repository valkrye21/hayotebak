

        .no {
            background-color: #f44336;
            color: rgb(255, 255, 255);
            position: relative;
        }

        .no:hover {
            animation: moveAway 0.50s forwards ease-in-out;
        }

        @keyframes moveAway {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-1000px);
            }
        }

        .btn:hover {
            transform: scale(1.1);
        }
    

.cry-rabbit {
    width: 200px;
    height: auto;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
    </style>
</head>
<body>
    <div class="container">
        <h1 class="question">Will you go out with me?</h1>
        <div class="options">
            <button class="btn yes" onclick="alert('okee, mau kapan ka?')">Yes</button>
            <button class="btn no" onclick="moveNo()">No</button>
        </div>
    </div>

    <script>
        function moveNo() {
            alert('yahh, kenapa ka?');
        }
    </script>
</body>
</html>

