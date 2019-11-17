https://docs.opencv.org/2.4/modules/imgproc/doc/geometric_transformations.html?highlight=perspective%20transform#void%20initUndistortRectifyMap(InputArray%20cameraMatrix,%20InputArray%20distCoeffs,%20InputArray%20R,%20InputArray%20newCameraMatrix,%20Size%20size,%20int%20m1type,%20OutputArray%20map1,%20OutputArray%20map2)
-> using undistort function
dst = cv2.undistort(src, cameraMartix, distCoeffs[, dst[, newCameraMatrix]])
where src: Input Image, dst: Output Image, distCoeffs = (k_1, k_2, p_1, p_2[, k_3[, k_4, k_5, k_6]])
camera matrix = [[f_x, 0, c_x], [0, f_y, c_y], [0, 0, 0]]
newCameraMatrix = distorted image의 Camera matrix
