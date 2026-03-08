└─# export PATH=/usr/bin:/bin:$PATH

# Read the full API router file — this has headers/auth logic
cat ~/mgm/jadx-output/sources/o/projectedMetersForLatLng.java
package o;

import android.content.Context;
import android.graphics.Color;
import android.graphics.ImageFormat;
import android.graphics.PointF;
import android.graphics.drawable.Drawable;
import android.media.AudioTrack;
import android.os.Process;
import android.os.SystemClock;
import android.telephony.cdma.CdmaCellLocation;
import android.text.AndroidCharacter;
import android.text.TextUtils;
import android.util.TypedValue;
import android.view.Gravity;
import android.view.KeyEvent;
import android.view.MotionEvent;
import android.view.View;
import android.view.ViewConfiguration;
import android.widget.ExpandableListView;
import java.io.ByteArrayInputStream;
import java.io.InputStream;
import java.lang.reflect.Array;
import java.lang.reflect.Method;
import java.util.HashMap;
import java.util.Map;
import me.pushy.sdk.lib.paho.internal.wire.MqttWireMessage;

/* loaded from: classes.dex */
public final class projectedMetersForLatLng {
    public static Map<String, Object> setTabContainer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.4
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/RequestOneTimeToken");
            put("method", "POST");
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.4.5
                {
                    put("UniqueKey", "user:uniqueKey:required");
                    put("CustomerID", "user:customerId");
                }
            });
        }
    };
    public static Map<String, Object> asInterface = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.15
        private static final byte[] $$d = {84, 37, -96, -32};
        private static final int $$e = 104;
        private static int $10 = 0;
        private static int $11 = 1;
        private static final byte[] $$a = {92, 85, -73, 113, -23, 44, -44, -10, 5, -6, -18, -8, 2};
        private static final int $$b = 82;
        private static int asInterface = 0;
        private static int RemoteActionCompatParcelizer = 1;
        private static char[] read = {30244, 30222, 30304, 30209, 30312, 30280, 30288, 30293, 30280, 30295, 30288, 30321, 30320, 30303, 30293, 30281, 30290, 30288, 30302, 30291, 30287, 30295, 30293, 30280, 30306, 30351, 30338, 30341, 30351, 30341, 30347, 30353, 30347, 30350, 30351, 30349, 30351, 30352, 30366, 30350, 30350, 30219, 30288, 30302, 30318, 30304, 30303, 30301, 30303, 30302, 30299, 30305, 30299, 30293, 30303, 30308, 30456, 30458, 30460, 30451, 30463, 30457, 30362, 30363, 30458, 30449, 30450, 30463, 30458, 30450, 30354, 30352, 30449, 30366, 30368, 30347, 30341, 30456, 30457, 30343, 30457, 30346, 30344, 30456, 30456, 30343, 30457, 30460, 30218, 30303, 30293, 30299, 30305, 30299, 30302, 30303, 30301, 30303, 30318, 30306, 30291, 30291, 30239, 30321, 30213, 30217, 30302, 30288, 30290, 30281, 30293, 30303, 30320, 30321, 30288, 30295, 30280, 30293, 30288, 30280, 30312, 30326, 30295, 30324, 30214, 30305, 30299, 30302, 30303, 30301, 30303, 30318, 30306, 30291, 30291, 30394, 30523, 30513, 30513, 30429, 30420, 30512, 30520, 30512, 30505, 30515, 30514, 30506, 30409, 30435, 30415, 30512, 30505, 30526, 30520, 30522, 30408, 30410, 30524, 30522, 30512, 30505, 30217, 30302, 30288, 30290, 30281, 30293, 30303, 30320, 30321, 30288, 30295, 30280, 30293, 30288, 30280, 30312, 30326, 30295, 30324, 30329, 30311, 30289, 30291, 30302, 30291, 30285, 30282, 30290, 30208, 30304, 30314, 30293, 30287, 30308, 30305, 30280, 30287, 30292, 30288};
        private static char[] asBinder = {57515, 57475, 57478, 57504, 57489, 57507, 57484, 57483, 57494, 57488, 57556, 57521, 57473, 57479, 57552, 57519, 57505, 57477, 57559, 57518, 57551, 57495, 57517, 57516, 57514};
        private static char onTransact = 54653;

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/AssignCustomerID");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.15.3
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.15.4
                {
                    put("UniqueKey", "user:uniqueKey:required");
                }
            });
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0028  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x0020  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0028 -> B:11:0x002d). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void a(byte r6, short r7, byte r8, java.lang.Object[] r9) {
            /*
                int r6 = r6 * 17
                int r6 = 114 - r6
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass15.$$a
                int r7 = r7 * 7
                int r7 = 11 - r7
                int r8 = r8 * 5
                int r1 = 8 - r8
                byte[] r1 = new byte[r1]
                int r8 = 7 - r8
                r2 = 0
                if (r0 != 0) goto L18
                r3 = r7
                r4 = r2
                goto L2d
            L18:
                r3 = r2
            L19:
                byte r4 = (byte) r6
                r1[r3] = r4
                int r4 = r3 + 1
                if (r3 != r8) goto L28
                java.lang.String r6 = new java.lang.String
                r6.<init>(r1, r2)
                r9[r2] = r6
                return
            L28:
                r3 = r0[r7]
                r5 = r3
                r3 = r6
                r6 = r5
            L2d:
                int r7 = r7 + 1
                int r6 = -r6
                int r3 = r3 + r6
                int r6 = r3 + (-5)
                r3 = r4
                goto L19
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass15.a(byte, short, byte, java.lang.Object[]):void");
        }

        /* JADX WARN: Code restructure failed: missing block: B:101:0x05c9, code lost:

            r10 = 343337308 ^ ((int) java.lang.System.currentTimeMillis());
            r8 = (~r10) & r36;
            r11 = ~r36;
         */
        /* JADX WARN: Code restructure failed: missing block: B:102:0x05d5, code lost:

            r13 = new java.lang.Object[]{java.lang.Integer.valueOf(r8 | (r10 & r11)), r4, java.lang.Integer.valueOf(r35)};
            r4 = o.onCameraWillChange.PlaybackStateCompat.get(300777817);
         */
        /* JADX WARN: Code restructure failed: missing block: B:103:0x05f5, code lost:

            if (r4 == null) goto L105;
         */
        /* JADX WARN: Code restructure failed: missing block: B:105:0x05f8, code lost:

            r4 = (java.lang.Class) o.onCameraWillChange.read((char) (1 - (android.os.SystemClock.currentThreadTimeMillis() > (-1) ? 1 : (android.os.SystemClock.currentThreadTimeMillis() == (-1) ? 0 : -1))), android.view.View.MeasureSpec.getSize(0) + 288, 25 - (android.view.ViewConfiguration.getJumpTapTimeout() >> 16));
            r12 = (byte) 0;
            r15 = r12;
            r14 = new java.lang.Object[1];
            a(r12, r15, (byte) (r15 + 1), r14);
            r4 = r4.getMethod((java.lang.String) r14[0], java.lang.Integer.TYPE, byte[][].class, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(300777817, r4);
         */
        /* JADX WARN: Code restructure failed: missing block: B:106:0x064c, code lost:

            r4 = ((java.lang.Long) ((java.lang.reflect.Method) r4).invoke(null, r13)).longValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:107:0x0659, code lost:

            r12 = -150626009;
            r14 = -494;
            r8 = -1;
            r24 = ((r14 * r12) + (r14 * r4)) + ((-495) * ((r12 | r4) ^ r8));
            r14 = 495;
            r26 = r23;
            r1 = (r36 ^ r8) | r12;
            r1 = ((r24 + (r14 * r1)) + (r14 * ((r1 ^ r8) | (((r4 ^ r8) | (r12 ^ r8)) ^ r8)))) - 1792339208;
            r4 = o.projectedMetersForLatLng.AnonymousClass15.asInterface;
            r5 = (r4 & 59) + (r4 | 59);
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r5 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:108:0x069a, code lost:

            if ((r5 % 2) != 0) goto L110;
         */
        /* JADX WARN: Code restructure failed: missing block: B:109:0x069c, code lost:

            r8 = ~((-973749545) | r11);
            r5 = ((int) (r1 >>> 32)) & (((((27263106 | r8) | (~(973749544 | r36))) * (-338)) + 2062221646) + ((r8 | (~(1001012650 | r36))) * 338));
            r1 = (int) r1;
            r9 = ((-539179179) + (((~((-11512264) | r11)) | 633153) * 98)) + ((((~(1448738673 | r11)) | (-11512264)) | (~((-1448738674) | r36))) * (-49));
            r2 = ((~((-11512264) | r36)) | 1448105520) * 49;
         */
        /* JADX WARN: Code restructure failed: missing block: B:10:0x0055, code lost:

            r6 = 1496444928 + ((~(r36 | 753198904)) * 216);
            r3 = ~r36;
         */
        /* JADX WARN: Code restructure failed: missing block: B:110:0x06e9, code lost:

            r5 = ((int) (r1 >> 32)) & ((((-1153123274) + (((-625623307) | r11) * 1444)) + ((((~((-1670247590) | r36)) | 1116058789) | (~((-1187493296) | r36))) * (-1444))) + 728460852);
            r1 = (int) r1;
            r9 = (-1704616964) + (((~((-1322476312) | r36)) | 114450962) * 305);
            r2 = ((~((-1322476312) | r11)) | 114750098) * 305;
         */
        /* JADX WARN: Code restructure failed: missing block: B:111:0x0728, code lost:

            r1 = r1 & (r9 + r2);
            r1 = (r1 & r5) | (r5 ^ r1);
            r1 = (r1 | r10) & (~(r1 & r10));
         */
        /* JADX WARN: Code restructure failed: missing block: B:112:0x0736, code lost:

            if ((r37 & 1) != 1) goto L136;
         */
        /* JADX WARN: Code restructure failed: missing block: B:113:0x0738, code lost:

            r5 = ((r4 | 53) << 1) - (r4 ^ 53);
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r5 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:114:0x0744, code lost:

            if ((r5 % 2) != 0) goto L118;
         */
        /* JADX WARN: Code restructure failed: missing block: B:116:0x074e, code lost:

            if (((~(r1 & r36)) & (r1 | r36)) != 46) goto L136;
         */
        /* JADX WARN: Code restructure failed: missing block: B:119:0x0756, code lost:

            if ((r1 ^ r36) != 15) goto L136;
         */
        /* JADX WARN: Code restructure failed: missing block: B:11:0x0072, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 0, java.lang.Integer.valueOf((r6 + ((1055909823 | r3) * (-216))) + (((~(753198904 | r3)) | (-445350328)) * 216))};
            r3 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:121:0x0759, code lost:

            r4 = new java.lang.Object[]{new int[]{r36}, new int[]{r1}, new int[1]};
         */
        /* JADX WARN: Code restructure failed: missing block: B:122:0x0773, code lost:

            r5 = 397325184 + (((((~((-713675692) | r11)) | 579441025) | (~(405827114 | r11))) | (~((-271592449) | r36))) * (-84));
            r1 = (~(405827114 | r36)) | 713675691;
            r2 = ~((-405827115) | r11);
         */
        /* JADX WARN: Code restructure failed: missing block: B:123:0x07a7, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 16, java.lang.Integer.valueOf((r5 + ((r1 | r2) * (-84))) + ((271592448 | r2) * 84))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:124:0x07cd, code lost:

            if (r1 == null) goto L126;
         */
        /* JADX WARN: Code restructure failed: missing block: B:126:0x07d0, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getFadingEdgeLength() >> 16), android.graphics.Color.blue(0) + 1715, 24 - (android.view.ViewConfiguration.getMaximumFlingVelocity() >> 16));
            r5 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r5;
            r11 = new java.lang.Object[1];
            a(r5, r9, (byte) (r9 - 1), r11);
            r1 = r1.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:129:0x0834, code lost:

            ((int[]) r4[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:12:0x0090, code lost:

            if (r3 == null) goto L14;
         */
        /* JADX WARN: Code restructure failed: missing block: B:130:0x083b, code lost:

            return r4;
         */
        /* JADX WARN: Code restructure failed: missing block: B:131:0x083c, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:132:0x083d, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:133:0x0842, code lost:

            if (r2 != null) goto L134;
         */
        /* JADX WARN: Code restructure failed: missing block: B:134:0x0844, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:135:0x0845, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:136:0x0846, code lost:

            r2 = (~(r1 & r36)) & (r1 | r36);
         */
        /* JADX WARN: Code restructure failed: missing block: B:137:0x084c, code lost:

            if (r2 != 0) goto L172;
         */
        /* JADX WARN: Code restructure failed: missing block: B:138:0x084e, code lost:

            r2 = (r4 & 37) + (r4 | 37);
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r2 % 128;
            r2 = r2 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:139:0x085a, code lost:

            r9 = new int[1];
            r5 = new java.lang.Object[]{new int[]{r36}, r9, new int[1]};
            r9 = r9;
         */
        /* JADX WARN: Code restructure failed: missing block: B:140:0x0872, code lost:

            r2 = (r4 & 15) + (r4 | 15);
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r2 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:141:0x087d, code lost:

            if ((r2 % 2) != 0) goto L157;
         */
        /* JADX WARN: Code restructure failed: missing block: B:143:0x0880, code lost:

            r9[0] = r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:145:0x08a8, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 1, java.lang.Integer.valueOf((((-532293298) + (((~((-575681339) | r11)) | (-267832762)) * (-602))) + ((((~((-575681339) | r36)) | 536883714) | (~((-229035138) | r11))) * (-301))) + ((~(r11 | (-267832762))) * com.mapxus.map.mapxusmap.api.services.constant.RoutePlanningInstructionSign.PASS_AREA))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:146:0x08cc, code lost:

            if (r1 == null) goto L148;
         */
        /* JADX WARN: Code restructure failed: missing block: B:148:0x08cf, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) ((android.os.Process.getThreadPriority(0) + 20) >> 6), android.graphics.Color.alpha(0) + 1715, 24 - android.view.KeyEvent.keyCodeFromString(""));
            r4 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r4;
            r11 = new java.lang.Object[1];
            a(r4, r9, (byte) (r9 - 1), r11);
            r1 = r1.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:149:0x0924, code lost:

            r1 = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:14:0x0093, code lost:

            r3 = (java.lang.Class) o.onCameraWillChange.read((char) android.graphics.Color.argb(0, 0, 0, 0), 1715 - android.graphics.Color.green(0), android.view.KeyEvent.normalizeMetaState(0) + 24);
            r5 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r6 = r5;
            r11 = new java.lang.Object[1];
            a(r5, r6, (byte) (r6 - 1), r11);
            r3 = r3.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r3);
         */
        /* JADX WARN: Code restructure failed: missing block: B:151:0x0934, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:153:0x0936, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:154:0x093a, code lost:

            if (r2 != null) goto L155;
         */
        /* JADX WARN: Code restructure failed: missing block: B:155:0x093c, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:156:0x093d, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:157:0x093e, code lost:

            r9[0] = r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:159:0x0960, code lost:

            r4 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 0, java.lang.Integer.valueOf((((-1643632256) + (((~(571882224 | r36)) | 342458369) * 104)) + ((~((-34609793) | r11)) * (-104))) + ((879730801 | r36) * 104))};
            r2 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:15:0x00d7, code lost:

            r2 = ((java.lang.Integer) ((java.lang.reflect.Method) r3).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:160:0x0984, code lost:

            if (r2 == null) goto L162;
         */
        /* JADX WARN: Code restructure failed: missing block: B:162:0x0987, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) android.graphics.Color.green(0), 1715 - android.graphics.Color.argb(0, 0, 0, 0), 25 - (android.os.SystemClock.currentThreadTimeMillis() > (-1) ? 1 : (android.os.SystemClock.currentThreadTimeMillis() == (-1) ? 0 : -1)));
            r2 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r2;
            r11 = new java.lang.Object[1];
            a(r2, r9, (byte) (r9 - 1), r11);
            r2 = r1.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r2);
         */
        /* JADX WARN: Code restructure failed: missing block: B:163:0x09da, code lost:

            r1 = ((java.lang.Integer) ((java.lang.reflect.Method) r2).invoke(null, r4)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:165:0x09e9, code lost:

            ((int[]) r5[2])[0] = r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:166:0x09f0, code lost:

            return r5;
         */
        /* JADX WARN: Code restructure failed: missing block: B:167:0x09f1, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:168:0x09f2, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:169:0x09f7, code lost:

            if (r2 != null) goto L170;
         */
        /* JADX WARN: Code restructure failed: missing block: B:16:0x00e3, code lost:

            r3 = r1[5];
         */
        /* JADX WARN: Code restructure failed: missing block: B:170:0x09f9, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:171:0x09fa, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:173:0x09fd, code lost:

            if (r2 != 11) goto L195;
         */
        /* JADX WARN: Code restructure failed: missing block: B:174:0x09ff, code lost:

            r4 = new java.lang.Object[]{new int[]{r36}, new int[]{r1}, new int[1]};
         */
        /* JADX WARN: Code restructure failed: missing block: B:175:0x0a1a, code lost:

            r1 = ~(159524920 | r11);
         */
        /* JADX WARN: Code restructure failed: missing block: B:176:0x0a3f, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 16, java.lang.Integer.valueOf(((922483200 + ((5576000 | r1) * (-712))) + (((~((-5576001) | r11)) | (~(165100920 | r36))) * (-712))) + ((r1 | (-148323657)) * 712))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:177:0x0a65, code lost:

            if (r1 == null) goto L179;
         */
        /* JADX WARN: Code restructure failed: missing block: B:179:0x0a68, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.text.TextUtils.indexOf((java.lang.CharSequence) "", '0', 0) + 1), android.graphics.Color.argb(0, 0, 0, 0) + 1715, 24 - android.view.View.getDefaultSize(0, 0));
            r5 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r5;
            r11 = new java.lang.Object[1];
            a(r5, r9, (byte) (r9 - 1), r11);
            r1 = r1.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:182:0x0acb, code lost:

            ((int[]) r4[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:183:0x0ad2, code lost:

            return r4;
         */
        /* JADX WARN: Code restructure failed: missing block: B:184:0x0ad3, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:185:0x0ad4, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:186:0x0ad9, code lost:

            if (r2 != null) goto L187;
         */
        /* JADX WARN: Code restructure failed: missing block: B:187:0x0adb, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:188:0x0adc, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:189:0x0add, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:18:0x00e9, code lost:

            r2 = ~r36;
         */
        /* JADX WARN: Code restructure failed: missing block: B:190:0x0ade, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:191:0x0ae3, code lost:

            if (r2 != null) goto L192;
         */
        /* JADX WARN: Code restructure failed: missing block: B:192:0x0ae5, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:193:0x0ae6, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:194:0x0ae7, code lost:

            r26 = r23;
         */
        /* JADX WARN: Code restructure failed: missing block: B:196:0x0aeb, code lost:

            r1 = new java.lang.Object[1];
            b(new byte[]{1, 0, 1, 0, 0, 1, 1, 0, 1, 0, 1, 0, 1, 0, 1, 0, 0, 1, 1, 0, 1, 1, 0}, new int[]{1, 23, 0, 18}, true, r1);
            r1 = java.lang.Class.forName((java.lang.String) r1[0]);
         */
        /* JADX WARN: Code restructure failed: missing block: B:197:0x0b05, code lost:

            r2 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer + 79;
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r2 % 128;
            r2 = r2 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:198:0x0b11, code lost:

            r9 = new java.lang.Object[1];
            b(new byte[]{1, 0, 1, 1, 0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 1}, new int[]{24, 17, 80, 3}, false, r9);
            r1 = r1.getMethod((java.lang.String) r9[0], null).invoke(r34, null);
         */
        /* JADX WARN: Code restructure failed: missing block: B:19:0x0110, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 0, java.lang.Integer.valueOf(((563444144 + (((~((-148026454) | r2)) | 455875030) * (-328))) + ((r36 | 455875030) * 164)) + (((~(r2 | (-13804546))) | ((~(r36 | 148026453)) | 321653122)) * 164))};
            r3 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:200:0x0b39, code lost:

            r9 = new java.lang.Object[1];
            b(new byte[]{1, 0, 1, 0, 0, 1, 1, 0, 1, 0, 1, 0, 1, 0, 1, 0, 0, 1, 1, 0, 1, 1, 0}, new int[]{1, 23, 0, 18}, true, r9);
            r4 = java.lang.Class.forName((java.lang.String) r9[0]);
            r12 = new java.lang.Object[1];
            b(new byte[]{1, 0, 0, 1, 1, 0, 0, 0, 0, 0, 1, 0, 1, 0}, new int[]{41, 14, 0, 0}, true, r12);
            r2 = r4.getMethod((java.lang.String) r12[0], null).invoke(r34, null);
         */
        /* JADX WARN: Code restructure failed: missing block: B:201:0x0b74, code lost:

            r4 = o.projectedMetersForLatLng.AnonymousClass15.asInterface + 11;
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r4 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:202:0x0b81, code lost:

            if ((r4 % 2) != 0) goto L205;
         */
        /* JADX WARN: Code restructure failed: missing block: B:204:0x0b84, code lost:

            r10 = new java.lang.Object[5];
            r10[0] = 64;
         */
        /* JADX WARN: Code restructure failed: missing block: B:205:0x0b8e, code lost:

            r10 = new java.lang.Object[2];
            r10[1] = 64;
         */
        /* JADX WARN: Code restructure failed: missing block: B:206:0x0b98, code lost:

            r10[0] = r2;
            r11 = new java.lang.Object[1];
            b(new byte[]{1, 1, 0, 0, 1, 0, 1, 0, 1, 0, 1, 0, 1, 1, 0, 0, 0, 1, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 1}, new int[]{55, 33, 90, 0}, false, r11);
            r2 = java.lang.Class.forName((java.lang.String) r11[0]);
            r11 = new java.lang.Object[1];
            b(new byte[]{1, 0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 1}, new int[]{88, 14, 0, 0}, false, r11);
            r5 = (java.lang.String) r11[0];
            r9 = new java.lang.Class[2];
            r9[0] = java.lang.String.class;
            r4 = ~r36;
            r11 = -(-((((-1081474) & r4) | ((-1081474) ^ r4)) * (-490)));
            r13 = (((-1986505874) | r11) << 1) - (r11 ^ (-1986505874));
            r11 = ~(((-716210310) & r36) | ((-716210310) ^ r36));
            r11 = -(-(((r11 & 715128836) | (715128836 ^ r11)) * 490));
            r12 = ((r13 | r11) << 1) - (r11 ^ r13);
            r13 = (r12 ^ 798631756) + ((798631756 & r12) << 1);
            r11 = ~r36;
            r12 = ~((1863179343 & r11) | (1863179343 ^ r11));
            r12 = (r12 & (-1869610736)) | ((-1869610736) ^ r12);
            r14 = ~((191622818 & r4) | (191622818 ^ r4));
            r12 = (((r12 & r14) | (r12 ^ r14)) | (~(((-185191427) & r36) | ((-185191427) ^ r36)))) * (-84);
            r15 = (1435475281 & r12) + (r12 | 1435475281);
            r12 = ~(191622818 | r36);
            r15 = (r15 - (~(((~(r11 | (-191622819))) | (((-1863179344) ^ r12) | (r12 & (-1863179344)))) * (-84)))) - 1;
            r8 = ~((r11 ^ (-191622819)) | (r11 & (-191622819)));
            r8 = -(-(((r8 & 185191426) | (r8 ^ 185191426)) * 84));
         */
        /* JADX WARN: Code restructure failed: missing block: B:207:0x0c6b, code lost:

            if (r13 > ((r15 ^ r8) + ((r8 & r15) << 1))) goto L210;
         */
        /* JADX WARN: Code restructure failed: missing block: B:208:0x0c6d, code lost:

            r9[0] = java.lang.Integer.TYPE;
            r2 = r2.getMethod(r5, r9);
         */
        /* JADX WARN: Code restructure failed: missing block: B:209:0x0c76, code lost:

            r1 = r2.invoke(r1, r10);
         */
        /* JADX WARN: Code restructure failed: missing block: B:20:0x012e, code lost:

            if (r3 == null) goto L22;
         */
        /* JADX WARN: Code restructure failed: missing block: B:210:0x0c7b, code lost:

            r9[1] = java.lang.Integer.TYPE;
            r2 = r2.getMethod(r5, r9);
         */
        /* JADX WARN: Code restructure failed: missing block: B:212:0x0c85, code lost:

            r2 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r5 = (r2 & 97) + (r2 | 97);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r5 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:213:0x0c92, code lost:

            if ((r5 % 2) == 0) goto L215;
         */
        /* JADX WARN: Code restructure failed: missing block: B:214:0x0c94, code lost:

            r5 = r26;
            r2 = 1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:215:0x0c98, code lost:

            r5 = r26;
            r2 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:216:0x0c9b, code lost:

            if (r2 >= r5) goto L375;
         */
        /* JADX WARN: Code restructure failed: missing block: B:217:0x0c9d, code lost:

            r9 = r6[r2];
         */
        /* JADX WARN: Code restructure failed: missing block: B:218:0x0ca5, code lost:

            if (r9.capacity() != 4) goto L222;
         */
        /* JADX WARN: Code restructure failed: missing block: B:219:0x0ca7, code lost:

            r14 = android.text.TextUtils.lastIndexOf("", '0');
            r15 = ~((r11 ^ 8) | (r11 & 8));
            r10 = ((((r14 * 522) - 4160) - (~(((r14 ^ r15) | (r15 & r14)) * (-1042)))) - 1) + (((r36 ^ 8) | (r36 & 8)) * 521);
            r15 = ~r14;
            r8 = ~((r15 ^ (-9)) | (r15 & (-9)));
            r15 = ~((r15 ^ r36) | (r15 & r36));
            r14 = (r14 & r4) | (r4 ^ r14);
            r8 = -(-((((r8 ^ r15) | (r8 & r15)) | (~((r14 & 8) | (r14 ^ 8)))) * 521));
            r14 = (r10 & r8) + (r8 | r10);
            r10 = new char[]{14, 21, '\n', 0, '\r', 19, 13844};
         */
        /* JADX WARN: Code restructure failed: missing block: B:220:0x0cfe, code lost:

            r13 = -android.text.TextUtils.lastIndexOf("", '0', 0, 0);
            r15 = (r13 * 491) - 50367;
            r8 = (~r13) | (-104);
            r12 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer + 45;
            r24 = r4;
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r12 % 128;
            r12 = r12 % 2;
            r8 = (-490) * ((r8 ^ r11) | (r8 & r11));
            r4 = (r15 ^ r8) + ((r8 & r15) << 1);
            r8 = ~((-104) | r13);
            r12 = ~(((-104) ^ r36) | ((-104) & r36));
            r4 = (r4 - (~(((r8 & r12) | (r8 ^ r12)) * 490))) - 1;
            r12 = -(-((~r13) * 490));
            r4 = (byte) ((r4 & r12) + (r4 | r12));
         */
        /* JADX WARN: Code restructure failed: missing block: B:221:0x0d42, code lost:

            r12 = new java.lang.Object[1];
            c(r14, r10, r4, r12);
            r10 = (java.lang.String) r12[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:222:0x0d4d, code lost:

            r24 = r4;
            r13 = new java.lang.Object[1];
            b(new byte[]{1, 1, 1}, new int[]{102, 3, 0, 3}, false, r13);
            r10 = (java.lang.String) r13[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:223:0x0d67, code lost:

            r14 = new java.lang.Object[1];
            b(new byte[]{1, 1, 0, 0, 1, 0, 1, 0, 1, 0, 1, 0, 1, 1, 0, 0, 0, 1, 1, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 1}, new int[]{105, 30, 0, 0}, false, r14);
            r4 = java.lang.Class.forName((java.lang.String) r14[0]);
            r12 = -android.view.View.MeasureSpec.getMode(0);
            r14 = -android.view.View.getDefaultSize(0, 0);
            r15 = new java.lang.Object[1];
            c((r12 & 10) + (r12 | 10), new char[]{2, '\t', 16, 7, 3, 6, 24, 6, 14, 3}, (byte) (((r14 | 47) << 1) - (r14 ^ 47)), r15);
            r4 = (java.lang.Object[]) r4.getField((java.lang.String) r15[0]).get(r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:224:0x0db8, code lost:

            r12 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r13 = (r12 & 21) + (r12 | 21);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r13 % 128;
            r13 = r13 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:225:0x0dc5, code lost:

            r12 = r4.length;
         */
        /* JADX WARN: Code restructure failed: missing block: B:226:0x0dc6, code lost:

            r13 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:227:0x0dc7, code lost:

            if (r13 >= r12) goto L377;
         */
        /* JADX WARN: Code restructure failed: missing block: B:228:0x0dc9, code lost:

            r14 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer + 65;
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r14 % 128;
            r14 = r14 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:229:0x0dd3, code lost:

            r14 = r4[r13];
         */
        /* JADX WARN: Code restructure failed: missing block: B:22:0x0131, code lost:

            r3 = (java.lang.Class) o.onCameraWillChange.read((char) android.graphics.Color.alpha(0), android.graphics.Color.blue(0) + 1715, (android.view.ViewConfiguration.getZoomControlsTimeout() > 0 ? 1 : (android.view.ViewConfiguration.getZoomControlsTimeout() == 0 ? 0 : -1)) + 23);
            r5 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r6 = r5;
            r9 = new java.lang.Object[1];
            a(r5, r6, (byte) (r6 - 1), r9);
            r3 = r3.getMethod((java.lang.String) r9[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r3);
         */
        /* JADX WARN: Code restructure failed: missing block: B:230:0x0dd5, code lost:

            r15 = new java.lang.Object[]{r10};
            r16 = r1;
            r37 = r4;
            r26 = r5;
            r25 = r6;
            r8 = new java.lang.Object[1];
            b(new byte[]{1, 1, 1, 1, 1, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 1}, new int[]{135, 27, 157, 0}, false, r8);
            r1 = java.lang.Class.forName((java.lang.String) r8[0]);
         */
        /* JADX WARN: Code restructure failed: missing block: B:231:0x0dff, code lost:

            r5 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r6 = (r5 & 63) + (r5 | 63);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r6 % 128;
            r6 = r6 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:232:0x0e0f, code lost:

            r5 = -(-(android.util.TypedValue.complexToFraction(0, 0.0f, 0.0f) > 0.0f ? 1 : (android.util.TypedValue.complexToFraction(0, 0.0f, 0.0f) == 0.0f ? 0 : -1)));
            r6 = (r5 & 11) + (r5 | 11);
            r5 = new char[]{18, '\f', 5, 3, '\t', 1, 6, 3, 7, 11, 13838};
            r4 = android.text.AndroidCharacter.getMirror('0');
         */
        /* JADX WARN: Code restructure failed: missing block: B:233:0x0e29, code lost:

            r8 = r4 * 'F';
            r28 = r10;
            r10 = (r8 & 2244) + (r8 | 2244);
            r8 = ~r4;
            r29 = (r8 ^ 32) | (r8 & 32);
            r31 = r12;
            r12 = ~((r29 ^ r36) | (r29 & r36));
            r29 = o.projectedMetersForLatLng.AnonymousClass15.asInterface;
            r32 = r2;
            r2 = (r29 & 107) + (r29 | 107);
            r29 = r13;
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r2 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:234:0x0e58, code lost:

            if ((r2 % 2) != 0) goto L237;
         */
        /* JADX WARN: Code restructure failed: missing block: B:235:0x0e5a, code lost:

            r2 = r4 | 65503;
            r2 = ~((r2 ^ r36) | (r2 & r36));
         */
        /* JADX WARN: Code restructure failed: missing block: B:236:0x0e69, code lost:

            r10 = r10 % (69 >>> ((r12 ^ r2) | (r2 & r12)));
            r2 = (r8 ^ (-33)) | (r8 & (-33));
         */
        /* JADX WARN: Code restructure failed: missing block: B:237:0x0e70, code lost:

            r2 = (r4 ^ 65503) | (r4 & 65503);
            r2 = -(-(((~((r2 ^ r36) | (r2 & r36))) | r12) * 69));
            r10 = ((r10 | r2) << 1) - (r2 ^ r10);
            r2 = ~r4;
            r2 = (r2 & (-33)) | (r2 ^ (-33));
         */
        /* JADX WARN: Code restructure failed: missing block: B:238:0x0e8f, code lost:

            r2 = ~r2;
            r8 = ~(r8 | r36);
            r8 = (-69) * (((r2 & r8) | (r2 ^ r8)) | (~((-33) | r36)));
            r2 = (r10 & r8) + (r8 | r10);
            r4 = (~(r4 | ' ')) * 69;
            r8 = new java.lang.Object[1];
            c(r6, r5, (byte) ((r2 ^ r4) + ((r2 & r4) << 1)), r8);
            r5 = (java.lang.String) r8[0];
            r6 = new java.lang.Class[]{java.lang.String.class};
         */
        /* JADX WARN: Code restructure failed: missing block: B:239:0x0ebe, code lost:

            r8 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r12 = ((r8 | 49) << 1) - (r8 ^ 49);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r12 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:23:0x017b, code lost:

            r2 = ((java.lang.Integer) ((java.lang.reflect.Method) r3).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:240:0x0ecc, code lost:

            if ((r12 % 2) == 0) goto L245;
         */
        /* JADX WARN: Code restructure failed: missing block: B:241:0x0ece, code lost:

            r1 = r1.getMethod(r5, r6).invoke(null, r15);
         */
        /* JADX WARN: Code restructure failed: missing block: B:243:0x0eda, code lost:

            r4 = 44 / 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:245:0x0edc, code lost:

            r1 = r1.getMethod(r5, r6).invoke(null, r15);
         */
        /* JADX WARN: Code restructure failed: missing block: B:246:0x0ee5, code lost:

            r4 = o.projectedMetersForLatLng.AnonymousClass15.asInterface;
            r5 = (r4 & 7) + (r4 | 7);
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r5 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:247:0x0ef2, code lost:

            if ((r5 % 2) != 0) goto L251;
         */
        /* JADX WARN: Code restructure failed: missing block: B:249:0x0ef6, code lost:

            r12 = new java.lang.Object[1];
            b(new byte[]{1, 1, 0, 0, 1, 0, 1, 0, 1, 0, 1, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 0, 1, 1, 1, 1, 1, 1}, new int[]{162, 28, 0, 0}, false, r12);
            r4 = (java.lang.String) r12[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:24:0x0187, code lost:

            r3 = r1[2];
         */
        /* JADX WARN: Code restructure failed: missing block: B:250:0x0f0e, code lost:

            r4 = java.lang.Class.forName(r4);
         */
        /* JADX WARN: Code restructure failed: missing block: B:251:0x0f13, code lost:

            r12 = new java.lang.Object[1];
            b(new byte[]{1, 1, 0, 0, 1, 0, 1, 0, 1, 0, 1, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 0, 1, 1, 1, 1, 1, 1}, new int[]{162, 28, 0, 0}, false, r12);
            r4 = (java.lang.String) r12[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:253:0x0f2e, code lost:

            r5 = o.projectedMetersForLatLng.AnonymousClass15.asInterface;
            r8 = (r5 ^ 27) + ((r5 & 27) << 1);
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r8 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:254:0x0f40, code lost:

            if ((r8 % 2) != 0) goto L256;
         */
        /* JADX WARN: Code restructure failed: missing block: B:255:0x0f42, code lost:

            r13 = new java.lang.Object[1];
            b(new byte[]{0, 1, 0, 1, 1, 1, 1, 1, 1, 0, 1}, new int[]{190, 11, 0, 8}, false, r13);
            r8 = (java.lang.String) r13[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:256:0x0f5e, code lost:

            r15 = new java.lang.Object[1];
            b(new byte[]{0, 1, 0, 1, 1, 1, 1, 1, 1, 0, 1}, new int[]{190, 11, 0, 8}, true, r15);
            r8 = (java.lang.String) r15[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:258:0x0f7f, code lost:

            r4 = new java.lang.Object[]{r4.getMethod(r8, null).invoke(r14, null)};
            r14 = new java.lang.Object[1];
            b(new byte[]{1, 1, 1, 1, 1, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 1}, new int[]{135, 27, 157, 0}, false, r14);
            r2 = java.lang.Class.forName((java.lang.String) r14[0]);
            r12 = -((byte) android.view.KeyEvent.getModifierMetaStateMask());
            r5 = -(-android.view.View.getDefaultSize(0, 0));
            r8 = new java.lang.Object[1];
            c((r12 ^ 5) + ((r12 & 5) << 1), new char[]{7, '\f', 18, '\f', 3, '\t'}, (byte) ((r5 & 85) + (r5 | 85)), r8);
         */
        /* JADX WARN: Code restructure failed: missing block: B:25:0x018b, code lost:

            ((int[]) r3)[0] = r2;
            r2 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r3 = (r2 & 25) + (r2 | 25);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r3 % 128;
            r3 = r3 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:260:0x0fee, code lost:

            if (java.nio.ByteBuffer.wrap((byte[]) r2.getMethod((java.lang.String) r8[0], byte[].class).invoke(r1, r4)).asLongBuffer().equals(r9.rewind()) == false) goto L277;
         */
        /* JADX WARN: Code restructure failed: missing block: B:261:0x0ff0, code lost:

            r1 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r2 = (r1 ^ 83) + ((r1 & 83) << 1);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r2 % 128;
            r2 = r2 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:262:0x1000, code lost:

            r2 = new java.lang.Object[]{new int[]{r36}, new int[]{r36}, new int[1]};
         */
        /* JADX WARN: Code restructure failed: missing block: B:264:0x1041, code lost:

            r4 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 0, java.lang.Integer.valueOf((((-273928656) + ((((~(669032017 | r11)) | (-976880595)) | (~((-669032018) | r36))) * (-564))) + ((~((-572523089) | r36)) * 1128)) + (((~((-976880595) | r11)) | 96508929) * 564))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:265:0x1065, code lost:

            if (r1 == null) goto L267;
         */
        /* JADX WARN: Code restructure failed: missing block: B:267:0x1068, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) android.widget.ExpandableListView.getPackedPositionGroup(0), android.text.TextUtils.indexOf((java.lang.CharSequence) "", '0', 0, 0) + 1716, android.graphics.Color.blue(0) + 24);
            r5 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r5;
            r11 = new java.lang.Object[1];
            a(r5, r9, (byte) (r9 - 1), r11);
            r1 = r1.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:26:0x0199, code lost:

            return r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:270:0x10cb, code lost:

            ((int[]) r2[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r4)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:271:0x10d2, code lost:

            return r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:272:0x10d3, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:273:0x10d4, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:274:0x10d9, code lost:

            if (r2 != null) goto L275;
         */
        /* JADX WARN: Code restructure failed: missing block: B:275:0x10db, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:276:0x10dc, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:277:0x10dd, code lost:

            r13 = r29 + 1;
            r4 = r37;
            r1 = r16;
            r6 = r25;
            r5 = r26;
            r10 = r28;
            r12 = r31;
            r2 = r32;
         */
        /* JADX WARN: Code restructure failed: missing block: B:278:0x10ef, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:279:0x10f0, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:27:0x019a, code lost:

            r9 = 16;
         */
        /* JADX WARN: Code restructure failed: missing block: B:280:0x10f5, code lost:

            if (r2 != null) goto L281;
         */
        /* JADX WARN: Code restructure failed: missing block: B:281:0x10f7, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:282:0x10f8, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:283:0x10f9, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:284:0x10fa, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:285:0x10ff, code lost:

            if (r2 != null) goto L286;
         */
        /* JADX WARN: Code restructure failed: missing block: B:286:0x1101, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:287:0x1102, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:288:0x1103, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:289:0x1104, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:28:0x019f, code lost:

            if (r2.length != 0) goto L39;
         */
        /* JADX WARN: Code restructure failed: missing block: B:290:0x1109, code lost:

            if (r2 != null) goto L291;
         */
        /* JADX WARN: Code restructure failed: missing block: B:291:0x110b, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:292:0x110c, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:293:0x110d, code lost:

            r32 = r2;
            r2 = ((r32 | 1) << 1) - (r32 ^ 1);
            r1 = r1;
            r4 = r24;
         */
        /* JADX WARN: Code restructure failed: missing block: B:294:0x1127, code lost:

            r4 = new java.lang.Object[]{new int[]{r36}, new int[]{(r36 & (-2)) | (r11 & 1)}, new int[1]};
         */
        /* JADX WARN: Code restructure failed: missing block: B:296:0x116c, code lost:

            r5 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 16, java.lang.Integer.valueOf((((-107456888) + ((1013210804 | r11) * (-757))) + ((~(1047461815 | r36)) * 1514)) + ((((~(705362227 | r11)) | 342099588) | (~((-34251012) | r36))) * 757))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:297:0x1192, code lost:

            if (r1 == null) goto L299;
         */
        /* JADX WARN: Code restructure failed: missing block: B:299:0x1195, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getDoubleTapTimeout() >> 16), 1715 - (android.view.ViewConfiguration.getMaximumFlingVelocity() >> 16), (android.view.ViewConfiguration.getMaximumFlingVelocity() >> 16) + 24);
            r2 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r2;
            r11 = new java.lang.Object[1];
            a(r2, r9, (byte) (r9 - 1), r11);
            r1 = r1.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:29:0x01a1, code lost:

            r1 = ((r5 | 41) << 1) - (r5 ^ 41);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r1 % 128;
            r1 = r1 % 2;
            r2 = ~r36;
            r5 = new java.lang.Object[]{new int[1], new int[1], new int[1]};
            ((int[]) r5[0])[0] = r36;
            ((int[]) r5[1])[0] = (r36 & (-5)) | (r2 & 4);
         */
        /* JADX WARN: Code restructure failed: missing block: B:302:0x11f8, code lost:

            ((int[]) r4[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r5)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:303:0x11ff, code lost:

            return r4;
         */
        /* JADX WARN: Code restructure failed: missing block: B:304:0x1200, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:305:0x1201, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:306:0x1206, code lost:

            if (r2 != null) goto L307;
         */
        /* JADX WARN: Code restructure failed: missing block: B:307:0x1208, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:308:0x1209, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:309:0x120a, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:30:0x01e0, code lost:

            r1 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 16, java.lang.Integer.valueOf(((((~(r36 | (-9357351))) | 289691004) * 398) - 1971313452) + (((~((-9357351) | r2)) | 289691004) * 398))};
            r2 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:310:0x120b, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:311:0x1210, code lost:

            if (r2 != null) goto L312;
         */
        /* JADX WARN: Code restructure failed: missing block: B:312:0x1212, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:313:0x1213, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:314:0x1214, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:315:0x1215, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:316:0x121a, code lost:

            if (r2 != null) goto L317;
         */
        /* JADX WARN: Code restructure failed: missing block: B:317:0x121c, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:318:0x121d, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:319:0x121e, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:31:0x01fe, code lost:

            if (r2 == null) goto L33;
         */
        /* JADX WARN: Code restructure failed: missing block: B:320:0x121f, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:321:0x1224, code lost:

            if (r2 != null) goto L322;
         */
        /* JADX WARN: Code restructure failed: missing block: B:322:0x1226, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:323:0x1227, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:324:0x1228, code lost:

            r2 = ~r36;
            r5 = new java.lang.Object[]{new int[1], new int[1], new int[1]};
            ((int[]) r5[0])[0] = r36;
            ((int[]) r5[1])[0] = (r36 & (-3)) | (r2 & 2);
         */
        /* JADX WARN: Code restructure failed: missing block: B:325:0x126e, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 16, java.lang.Integer.valueOf(((915146860 + (((~(268477294 | r36)) | (~((-268477185) | r2))) * (-406))) + ((~(844803055 | r2)) * (-406))) + (((~((-576325872) | r36)) | (~(r2 | (-268477295)))) * 406))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:326:0x1294, code lost:

            if (r1 != null) goto L327;
         */
        /* JADX WARN: Code restructure failed: missing block: B:328:0x1297, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getKeyRepeatTimeout() >> 16), android.text.AndroidCharacter.getMirror('0') + 1667, 24 - android.text.TextUtils.indexOf("", ""));
            r3 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r6 = r3;
            r9 = new java.lang.Object[1];
            a(r3, r6, (byte) (r6 - 1), r9);
            r1 = r1.getMethod((java.lang.String) r9[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:330:0x12fa, code lost:

            ((int[]) r5[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:331:0x1302, code lost:

            return r5;
         */
        /* JADX WARN: Code restructure failed: missing block: B:33:0x0201, code lost:

            r2 = (java.lang.Class) o.onCameraWillChange.read((char) android.text.TextUtils.getTrimmedLength(""), 1715 - android.view.KeyEvent.keyCodeFromString(""), 24 - android.text.TextUtils.indexOf("", ""));
            r3 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r6 = r3;
            r9 = new java.lang.Object[1];
            a(r3, r6, (byte) (r6 - 1), r9);
            r2 = r2.getMethod((java.lang.String) r9[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r2);
         */
        /* JADX WARN: Code restructure failed: missing block: B:35:0x0252, code lost:

            ((int[]) r5[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r2).invoke(null, r1)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:36:0x0258, code lost:

            return r5;
         */
        /* JADX WARN: Code restructure failed: missing block: B:39:0x025d, code lost:

            r5 = r2.length;
            r6 = new java.nio.LongBuffer[r5];
            r13 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:41:0x0264, code lost:

            if (r13 >= r2.length) goto L366;
         */
        /* JADX WARN: Code restructure failed: missing block: B:42:0x0266, code lost:

            r12 = r2[r13].toLowerCase();
            r4 = new byte[r8];
            r4[r10] = r10;
            r15 = new java.lang.Object[r8];
            b(r4, new int[]{r10, r8, r10, r8}, r8, r15);
            r4 = r12.replaceAll((java.lang.String) r15[r10], "");
            r11 = new java.math.BigInteger(r4.substring(r9, 32), r9).longValue();
            r9 = new java.math.BigInteger(r4.substring(r10, r9), r9).longValue();
            r15 = r4.length();
         */
        /* JADX WARN: Code restructure failed: missing block: B:43:0x029f, code lost:

            if (r15 == 32) goto L59;
         */
        /* JADX WARN: Code restructure failed: missing block: B:45:0x02a3, code lost:

            if (r15 == 64) goto L58;
         */
        /* JADX WARN: Code restructure failed: missing block: B:46:0x02a5, code lost:

            r1 = (~(r36 & 3)) & (r36 | 3);
            r4 = new java.lang.Object[3];
            r4[0] = new int[1];
            r2 = ~(495249100 | r36);
            r5 = (-1816986235) - (~(-(-(((r2 & 1646795059) | (1646795059 ^ r2)) * 992))));
            r2 = ~(495249100 | r36);
            r2 = (r2 & 1646795059) | (1646795059 ^ r2);
            r6 = ~r36;
            r6 = ~(((r6 & (-495249101)) | (r6 ^ (-495249101))) | 1722334707);
            r2 = ((r2 & r6) | (r2 ^ r6)) * (-496);
            r6 = (((r5 ^ r2) + ((r2 & r5) << 1)) - (~(-(-((1722334707 | r36) * 496))))) - 1;
            r2 = ~r36;
            r9 = ~((1676208539 ^ r2) | (1676208539 & r2));
            r9 = -(-(((r9 & (-1125928824)) | ((-1125928824) ^ r9)) * (-235)));
            r5 = ~(1676208539 | r36);
            r12 = ((1815244392 & r9) + (r9 | 1815244392)) + (((r5 & (-1125928824)) | ((-1125928824) ^ r5)) * (-470));
            r5 = ~(((-1312357) & r36) | ((-1312357) ^ r36));
            r5 = ((r5 & 551592072) | (551592072 ^ r5)) * 235;
         */
        /* JADX WARN: Code restructure failed: missing block: B:47:0x0333, code lost:

            if (r6 <= (((r12 | r5) << 1) - (r5 ^ r12))) goto L49;
         */
        /* JADX WARN: Code restructure failed: missing block: B:48:0x0335, code lost:

            r6 = 0;
            r4[0] = new int[1];
            r4[4] = new int[1];
         */
        /* JADX WARN: Code restructure failed: missing block: B:49:0x0340, code lost:

            r6 = 0;
            r4[1] = new int[1];
            r4[2] = new int[1];
         */
        /* JADX WARN: Code restructure failed: missing block: B:50:0x034a, code lost:

            ((int[]) r4[r6])[r6] = r36;
            ((int[]) r4[1])[r6] = r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:51:0x036e, code lost:

            r3 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 16, java.lang.Integer.valueOf((((~((-268468225) | r2)) * 130) - 370304256) + (((~((-268468225) | r36)) | 1054016) * 130))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:52:0x0394, code lost:

            if (r1 == null) goto L54;
         */
        /* JADX WARN: Code restructure failed: missing block: B:54:0x0397, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getTouchSlop() >> 8), android.text.TextUtils.indexOf("", "") + 1715, android.graphics.Color.alpha(0) + 24);
            r2 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r6 = r2;
            r9 = new java.lang.Object[1];
            a(r2, r6, (byte) (r6 - 1), r9);
            r1 = r1.getMethod((java.lang.String) r9[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:56:0x03f7, code lost:

            ((int[]) r4[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r3)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:57:0x03ff, code lost:

            return r4;
         */
        /* JADX WARN: Code restructure failed: missing block: B:58:0x0400, code lost:

            r23 = r5;
            r6[r13] = java.nio.LongBuffer.allocate(4).put(r9).put(r11).put(new java.math.BigInteger(r4.substring(32, 48), 16).longValue()).put(new java.math.BigInteger(r4.substring(48), 16).longValue());
         */
        /* JADX WARN: Code restructure failed: missing block: B:59:0x043a, code lost:

            r23 = r5;
            r6[r13] = java.nio.LongBuffer.allocate(2).put(r9).put(r11);
         */
        /* JADX WARN: Code restructure failed: missing block: B:5:0x0027, code lost:

            if (r34 == null) goto L8;
         */
        /* JADX WARN: Code restructure failed: missing block: B:60:0x044b, code lost:

            r13 = ((r13 | 1) << 1) - (r13 ^ 1);
            r2 = r35;
            r8 = 1;
            r5 = r23;
            r9 = 16;
            r10 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:61:0x0464, code lost:

            r23 = r5;
            r4 = r8;
         */
        /* JADX WARN: Code restructure failed: missing block: B:62:0x0467, code lost:

            if (r34 != null) goto L81;
         */
        /* JADX WARN: Code restructure failed: missing block: B:64:0x046a, code lost:

            r1 = new java.lang.Object[3];
            r2 = new int[r4];
            r1[0] = r2;
            r5 = new int[r4];
            r1[r4] = r5;
            r1[2] = new int[r4];
            r2 = r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:65:0x047c, code lost:

            r6 = o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer;
            r9 = (r6 ^ 115) + ((r6 & 115) << r4);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r9 % 128;
            r9 = r9 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:66:0x048b, code lost:

            r2[0] = r36;
            r5[0] = r36;
         */
        /* JADX WARN: Code restructure failed: missing block: B:68:0x04bc, code lost:

            r5 = new java.lang.Object[]{java.lang.Integer.valueOf(r38), 0, java.lang.Integer.valueOf(((1098707456 + (((~((-613034117) | (~r36))) | (~((-305185540) | r36))) * (-272))) + (((~((-747515109) | r36)) | 134480992) * (-272))) + (((~(747515108 | r36)) | (-439666532)) * 272))};
            r4 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:69:0x04e0, code lost:

            if (r4 == null) goto L71;
         */
        /* JADX WARN: Code restructure failed: missing block: B:71:0x04e3, code lost:

            r2 = (java.lang.Class) o.onCameraWillChange.read((char) (android.text.TextUtils.indexOf((java.lang.CharSequence) "", '0', 0) + 1), android.view.KeyEvent.normalizeMetaState(0) + 1715, 23 - android.text.TextUtils.indexOf((java.lang.CharSequence) "", '0', 0, 0));
            r4 = (byte) (o.projectedMetersForLatLng.AnonymousClass15.$$a[12] - 1);
            r9 = r4;
            r11 = new java.lang.Object[1];
            a(r4, r9, (byte) (r9 - 1), r11);
            r4 = r2.getMethod((java.lang.String) r11[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r4);
         */
        /* JADX WARN: Code restructure failed: missing block: B:74:0x0546, code lost:

            ((int[]) r1[2])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r4).invoke(null, r5)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:75:0x054d, code lost:

            return r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:76:0x054e, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:77:0x054f, code lost:

            r2 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:78:0x0554, code lost:

            if (r2 != null) goto L79;
         */
        /* JADX WARN: Code restructure failed: missing block: B:79:0x0556, code lost:

            throw r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:7:0x002a, code lost:

            if (r34 == null) goto L8;
         */
        /* JADX WARN: Code restructure failed: missing block: B:80:0x0557, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:81:0x0558, code lost:

            r4 = new byte[r23][];
            r5 = 0;
            r9 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:82:0x055e, code lost:

            if (r5 >= r23) goto L370;
         */
        /* JADX WARN: Code restructure failed: missing block: B:83:0x0560, code lost:

            r10 = r6[r5];
         */
        /* JADX WARN: Code restructure failed: missing block: B:85:0x0567, code lost:

            if (r10.capacity() != 4) goto L96;
         */
        /* JADX WARN: Code restructure failed: missing block: B:86:0x0569, code lost:

            r11 = o.projectedMetersForLatLng.AnonymousClass15.asInterface + 121;
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r11 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:87:0x0573, code lost:

            if ((r11 % 2) != 0) goto L91;
         */
        /* JADX WARN: Code restructure failed: missing block: B:89:0x0577, code lost:

            r11 = java.nio.ByteBuffer.allocate(58);
         */
        /* JADX WARN: Code restructure failed: missing block: B:8:0x002c, code lost:

            r1 = new java.lang.Object[]{new int[1], new int[1], new int[1]};
            ((int[]) r1[0])[0] = r36;
            r7 = r7 + 107;
            r2 = r7 % 128;
            o.projectedMetersForLatLng.AnonymousClass15.RemoteActionCompatParcelizer = r2;
            r7 = r7 % 2;
            ((int[]) r1[1])[0] = r36;
            r5 = (r2 & 95) + (r2 | 95);
            o.projectedMetersForLatLng.AnonymousClass15.asInterface = r5 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:90:0x057b, code lost:

            r12 = r11.asLongBuffer();
         */
        /* JADX WARN: Code restructure failed: missing block: B:91:0x0580, code lost:

            r11 = java.nio.ByteBuffer.allocate(32);
         */
        /* JADX WARN: Code restructure failed: missing block: B:92:0x0585, code lost:

            r10 = r10.array();
            r13 = r10.length;
            r15 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:93:0x058b, code lost:

            if (r15 >= r13) goto L373;
         */
        /* JADX WARN: Code restructure failed: missing block: B:94:0x058d, code lost:

            r12.put(r10[r15]);
            r15 = ((r15 | 1) << 1) - (r15 ^ 1);
            r9 = r9;
         */
        /* JADX WARN: Code restructure failed: missing block: B:95:0x059f, code lost:

            r35 = r9;
            r9 = r35 + 100;
            r4[r35] = r11.array();
            r9 = (r9 ^ (-99)) + ((r9 & (-99)) << 1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:97:0x05b4, code lost:

            r8 = ((r5 | 49) << 1) - (r5 ^ 49);
            r5 = (r8 & (-48)) + (r8 | (-48));
         */
        /* JADX WARN: Code restructure failed: missing block: B:98:0x05c1, code lost:

            r35 = r9;
         */
        /* JADX WARN: Code restructure failed: missing block: B:99:0x05c3, code lost:

            if (r35 <= 0) goto L194;
         */
        /* JADX WARN: Code restructure failed: missing block: B:9:0x0053, code lost:

            if ((r5 % 2) == 0) goto L18;
         */
        /* JADX WARN: Multi-variable type inference failed */
        /* JADX WARN: Type inference failed for: r8v0 */
        /* JADX WARN: Type inference failed for: r8v175 */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        public static java.lang.Object[] asBinder(android.content.Context r34, java.lang.String[] r35, int r36, int r37, int r38) throws java.lang.Throwable {
            /*
                Method dump skipped, instructions count: 5138
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass15.asBinder(android.content.Context, java.lang.String[], int, int, int):java.lang.Object[]");
        }

        private static void b(byte[] bArr, int[] iArr, boolean z, Object[] objArr) throws Throwable {
            int i;
            int i2 = 2;
            int i3 = 2 % 2;
            addOnDidBecomeIdleListener addondidbecomeidlelistener = new addOnDidBecomeIdleListener();
            int i4 = 0;
            int i5 = iArr[0];
            int i6 = 1;
            int i7 = iArr[1];
            int i8 = iArr[2];
            int i9 = iArr[3];
            char[] cArr = read;
            float f = 0.0f;
            int i10 = -1;
            if (cArr != null) {
                int length = cArr.length;
                char[] cArr2 = new char[length];
                int i11 = 0;
                while (i11 < length) {
                    int i12 = $11 + 3;
                    $10 = i12 % 128;
                    if (i12 % i2 != 0) {
                        try {
                            Object[] objArr2 = new Object[i6];
                            objArr2[i4] = Integer.valueOf(cArr[i11]);
                            Object method = onCameraWillChange.PlaybackStateCompat.get(-1605641787);
                            if (method == null) {
                                Class cls = (Class) onCameraWillChange.read((char) (37361 - (ViewConfiguration.getDoubleTapTimeout() >> 16)), KeyEvent.getDeadChar(i4, i4) + 1300, 12 - (AudioTrack.getMinVolume() > f ? 1 : (AudioTrack.getMinVolume() == f ? 0 : -1)));
                                byte b = (byte) i4;
                                Object[] objArr3 = new Object[1];
                                d(b, (byte) (b | 19), (byte) i10, objArr3);
                                method = cls.getMethod((String) objArr3[0], Integer.TYPE);
                                onCameraWillChange.PlaybackStateCompat.put(-1605641787, method);
                            }
                            cArr2[i11] = ((Character) ((Method) method).invoke(null, objArr2)).charValue();
                        } catch (Throwable th) {
                            Throwable cause = th.getCause();
                            if (cause == null) {
                                throw th;
                            }
                            throw cause;
                        }
                    } else {
                        Object[] objArr4 = {Integer.valueOf(cArr[i11])};
                        Object method2 = onCameraWillChange.PlaybackStateCompat.get(-1605641787);
                        if (method2 == null) {
                            Class cls2 = (Class) onCameraWillChange.read((char) (37361 - Color.green(0)), 1300 - View.MeasureSpec.getMode(0), 12 - ExpandableListView.getPackedPositionType(0L));
                            byte b2 = (byte) 0;
                            Object[] objArr5 = new Object[1];
                            d(b2, (byte) (b2 | 19), (byte) (-1), objArr5);
                            method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-1605641787, method2);
                        }
                        cArr2[i11] = ((Character) ((Method) method2).invoke(null, objArr4)).charValue();
                        i11++;
                    }
                    i2 = 2;
                    i4 = 0;
                    i6 = 1;
                    f = 0.0f;
                    i10 = -1;
                }
                cArr = cArr2;
            }
            char[] cArr3 = new char[i7];
            System.arraycopy(cArr, i5, cArr3, 0, i7);
            if (bArr != null) {
                char[] cArr4 = new char[i7];
                addondidbecomeidlelistener.onTransact = 0;
                char c = 0;
                while (addondidbecomeidlelistener.onTransact < i7) {
                    if (bArr[addondidbecomeidlelistener.onTransact] == 1) {
                        int i13 = $11 + 69;
                        $10 = i13 % 128;
                        if (i13 % 2 != 0) {
                            int i14 = addondidbecomeidlelistener.onTransact;
                            Object[] objArr6 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                            Object method3 = onCameraWillChange.PlaybackStateCompat.get(-2027528084);
                            if (method3 == null) {
                                Class cls3 = (Class) onCameraWillChange.read((char) (Color.argb(0, 0, 0, 0) + 58526), ((Process.getThreadPriority(0) + 20) >> 6) + 230, View.getDefaultSize(0, 0) + 25);
                                byte b3 = (byte) 0;
                                Object[] objArr7 = new Object[1];
                                d(b3, (byte) (b3 | 15), (byte) (-1), objArr7);
                                method3 = cls3.getMethod((String) objArr7[0], Integer.TYPE, Integer.TYPE);
                                onCameraWillChange.PlaybackStateCompat.put(-2027528084, method3);
                            }
                            cArr4[i14] = ((Character) ((Method) method3).invoke(null, objArr6)).charValue();
                            throw null;
                        }
                        int i15 = addondidbecomeidlelistener.onTransact;
                        Object[] objArr8 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                        Object method4 = onCameraWillChange.PlaybackStateCompat.get(-2027528084);
                        if (method4 == null) {
                            Class cls4 = (Class) onCameraWillChange.read((char) (View.resolveSize(0, 0) + 58526), 231 - (SystemClock.elapsedRealtimeNanos() > 0L ? 1 : (SystemClock.elapsedRealtimeNanos() == 0L ? 0 : -1)), Color.argb(0, 0, 0, 0) + 25);
                            byte b4 = (byte) 0;
                            Object[] objArr9 = new Object[1];
                            d(b4, (byte) (b4 | 15), (byte) (-1), objArr9);
                            method4 = cls4.getMethod((String) objArr9[0], Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-2027528084, method4);
                        }
                        cArr4[i15] = ((Character) ((Method) method4).invoke(null, objArr8)).charValue();
                    } else {
                        int i16 = addondidbecomeidlelistener.onTransact;
                        Object[] objArr10 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                        Object method5 = onCameraWillChange.PlaybackStateCompat.get(613310274);
                        if (method5 == null) {
                            Class cls5 = (Class) onCameraWillChange.read((char) KeyEvent.keyCodeFromString(""), (ViewConfiguration.getScrollFriction() > 0.0f ? 1 : (ViewConfiguration.getScrollFriction() == 0.0f ? 0 : -1)) + 1287, 12 - Color.green(0));
                            byte b5 = (byte) 0;
                            Object[] objArr11 = new Object[1];
                            d(b5, (byte) (b5 | 24), (byte) (-1), objArr11);
                            method5 = cls5.getMethod((String) objArr11[0], Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(613310274, method5);
                        }
                        cArr4[i16] = ((Character) ((Method) method5).invoke(null, objArr10)).charValue();
                    }
                    c = cArr4[addondidbecomeidlelistener.onTransact];
                    Object[] objArr12 = {addondidbecomeidlelistener, addondidbecomeidlelistener};
                    Object method6 = onCameraWillChange.PlaybackStateCompat.get(207891030);
                    if (method6 == null) {
                        Class cls6 = (Class) onCameraWillChange.read((char) (View.resolveSizeAndState(0, 0, 0) + 38149), 1873 - (ExpandableListView.getPackedPositionForChild(0, 0) > 0L ? 1 : (ExpandableListView.getPackedPositionForChild(0, 0) == 0L ? 0 : -1)), 23 - (ViewConfiguration.getScrollBarFadeDuration() >> 16));
                        byte b6 = (byte) 0;
                        Object[] objArr13 = new Object[1];
                        d(b6, (byte) (b6 | 22), (byte) (-1), objArr13);
                        method6 = cls6.getMethod((String) objArr13[0], Object.class, Object.class);
                        onCameraWillChange.PlaybackStateCompat.put(207891030, method6);
                    }
                    ((Method) method6).invoke(null, objArr12);
                }
                cArr3 = cArr4;
            }
            if (i9 > 0) {
                char[] cArr5 = new char[i7];
                i = 0;
                System.arraycopy(cArr3, 0, cArr5, 0, i7);
                int i17 = i7 - i9;
                System.arraycopy(cArr5, 0, cArr3, i17, i9);
                System.arraycopy(cArr5, i9, cArr3, 0, i17);
            } else {
                i = 0;
            }
            if (z) {
                char[] cArr6 = new char[i7];
                while (true) {
                    addondidbecomeidlelistener.onTransact = i;
                    if (addondidbecomeidlelistener.onTransact >= i7) {
                        break;
                    }
                    cArr6[addondidbecomeidlelistener.onTransact] = cArr3[(i7 - addondidbecomeidlelistener.onTransact) - 1];
                    i = addondidbecomeidlelistener.onTransact + 1;
                }
                cArr3 = cArr6;
            }
            if (i8 > 0) {
                int i18 = $10 + 53;
                $11 = i18 % 128;
                int i19 = i18 % 2;
                int i20 = 0;
                while (true) {
                    addondidbecomeidlelistener.onTransact = i20;
                    if (addondidbecomeidlelistener.onTransact >= i7) {
                        break;
                    }
                    cArr3[addondidbecomeidlelistener.onTransact] = (char) (cArr3[addondidbecomeidlelistener.onTransact] - iArr[2]);
                    i20 = addondidbecomeidlelistener.onTransact + 1;
                }
            }
            objArr[0] = new String(cArr3);
        }

        private static void c(int i, char[] cArr, byte b, Object[] objArr) throws Throwable {
            int i2;
            Object obj;
            int i3;
            int i4 = 2;
            int i5 = 2 % 2;
            addOnStyleImageMissingListener addonstyleimagemissinglistener = new addOnStyleImageMissingListener();
            char[] cArr2 = asBinder;
            Object obj2 = null;
            long j = 0;
            if (cArr2 != null) {
                int length = cArr2.length;
                char[] cArr3 = new char[length];
                int i6 = 0;
                while (i6 < length) {
                    int i7 = $10 + 77;
                    $11 = i7 % 128;
                    if (i7 % i4 == 0) {
                        try {
                            Object[] objArr2 = {Integer.valueOf(cArr2[i6])};
                            Object method = onCameraWillChange.PlaybackStateCompat.get(-1517798586);
                            if (method == null) {
                                Class cls = (Class) onCameraWillChange.read((char) (1 - (ViewConfiguration.getScrollFriction() > 0.0f ? 1 : (ViewConfiguration.getScrollFriction() == 0.0f ? 0 : -1))), 1463 - (ViewConfiguration.getGlobalActionKeyTimeout() > j ? 1 : (ViewConfiguration.getGlobalActionKeyTimeout() == j ? 0 : -1)), 23 - (ViewConfiguration.getGlobalActionKeyTimeout() > j ? 1 : (ViewConfiguration.getGlobalActionKeyTimeout() == j ? 0 : -1)));
                                byte b2 = (byte) 0;
                                byte b3 = b2;
                                Object[] objArr3 = new Object[1];
                                d(b2, b3, (byte) (b3 - 1), objArr3);
                                method = cls.getMethod((String) objArr3[0], Integer.TYPE);
                                onCameraWillChange.PlaybackStateCompat.put(-1517798586, method);
                            }
                            cArr3[i6] = ((Character) ((Method) method).invoke(null, objArr2)).charValue();
                        } catch (Throwable th) {
                            Throwable cause = th.getCause();
                            if (cause == null) {
                                throw th;
                            }
                            throw cause;
                        }
                    } else {
                        Object[] objArr4 = {Integer.valueOf(cArr2[i6])};
                        Object method2 = onCameraWillChange.PlaybackStateCompat.get(-1517798586);
                        if (method2 == null) {
                            Class cls2 = (Class) onCameraWillChange.read((char) (ImageFormat.getBitsPerPixel(0) + 1), 1463 - (SystemClock.elapsedRealtime() > 0L ? 1 : (SystemClock.elapsedRealtime() == 0L ? 0 : -1)), 21 - ImageFormat.getBitsPerPixel(0));
                            byte b4 = (byte) 0;
                            byte b5 = b4;
                            Object[] objArr5 = new Object[1];
                            d(b4, b5, (byte) (b5 - 1), objArr5);
                            method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-1517798586, method2);
                        }
                        cArr3[i6] = ((Character) ((Method) method2).invoke(null, objArr4)).charValue();
                        i6++;
                    }
                    i4 = 2;
                    j = 0;
                }
                cArr2 = cArr3;
            }
            Object[] objArr6 = {Integer.valueOf(onTransact)};
            Object method3 = onCameraWillChange.PlaybackStateCompat.get(-1517798586);
            if (method3 == null) {
                Class cls3 = (Class) onCameraWillChange.read((char) View.combineMeasuredStates(0, 0), 1463 - (SystemClock.uptimeMillis() > 0L ? 1 : (SystemClock.uptimeMillis() == 0L ? 0 : -1)), (ViewConfiguration.getWindowTouchSlop() >> 8) + 22);
                byte b6 = (byte) 0;
                byte b7 = b6;
                Object[] objArr7 = new Object[1];
                d(b6, b7, (byte) (b7 - 1), objArr7);
                method3 = cls3.getMethod((String) objArr7[0], Integer.TYPE);
                onCameraWillChange.PlaybackStateCompat.put(-1517798586, method3);
            }
            char cCharValue = ((Character) ((Method) method3).invoke(null, objArr6)).charValue();
            char[] cArr4 = new char[i];
            if (i % 2 != 0) {
                i2 = i - 1;
                cArr4[i2] = (char) (cArr[i2] - b);
            } else {
                i2 = i;
            }
            if (i2 > 1) {
                addonstyleimagemissinglistener.asBinder = 0;
                while (addonstyleimagemissinglistener.asBinder < i2) {
                    int i8 = $11 + 105;
                    $10 = i8 % 128;
                    int i9 = i8 % 2;
                    addonstyleimagemissinglistener.asInterface = cArr[addonstyleimagemissinglistener.asBinder];
                    addonstyleimagemissinglistener.onTransact = cArr[addonstyleimagemissinglistener.asBinder + 1];
                    if (addonstyleimagemissinglistener.asInterface == addonstyleimagemissinglistener.onTransact) {
                        cArr4[addonstyleimagemissinglistener.asBinder] = (char) (addonstyleimagemissinglistener.asInterface - b);
                        cArr4[addonstyleimagemissinglistener.asBinder + 1] = (char) (addonstyleimagemissinglistener.onTransact - b);
                        obj = obj2;
                        i3 = 2;
                    } else {
                        Object[] objArr8 = {addonstyleimagemissinglistener, addonstyleimagemissinglistener, Integer.valueOf(cCharValue), addonstyleimagemissinglistener, addonstyleimagemissinglistener, Integer.valueOf(cCharValue), addonstyleimagemissinglistener, addonstyleimagemissinglistener, Integer.valueOf(cCharValue), addonstyleimagemissinglistener, addonstyleimagemissinglistener, Integer.valueOf(cCharValue), addonstyleimagemissinglistener};
                        Object method4 = onCameraWillChange.PlaybackStateCompat.get(416277665);
                        if (method4 == null) {
                            Class cls4 = (Class) onCameraWillChange.read((char) KeyEvent.normalizeMetaState(0), (Process.getElapsedCpuTime() > 0L ? 1 : (Process.getElapsedCpuTime() == 0L ? 0 : -1)) + 1714, ExpandableListView.getPackedPositionGroup(0L) + 24);
                            byte length2 = (byte) $$d.length;
                            Object[] objArr9 = new Object[1];
                            d((byte) 0, length2, (byte) (length2 - 5), objArr9);
                            method4 = cls4.getMethod((String) objArr9[0], Object.class, Object.class, Integer.TYPE, Object.class, Object.class, Integer.TYPE, Object.class, Object.class, Integer.TYPE, Object.class, Object.class, Integer.TYPE, Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(416277665, method4);
                        }
                        if (((Integer) ((Method) method4).invoke(null, objArr8)).intValue() == addonstyleimagemissinglistener.IconCompatParcelizer) {
                            Object[] objArr10 = {addonstyleimagemissinglistener, addonstyleimagemissinglistener, Integer.valueOf(cCharValue), Integer.valueOf(cCharValue), addonstyleimagemissinglistener, addonstyleimagemissinglistener, Integer.valueOf(cCharValue), Integer.valueOf(cCharValue), addonstyleimagemissinglistener, Integer.valueOf(cCharValue), addonstyleimagemissinglistener};
                            Object method5 = onCameraWillChange.PlaybackStateCompat.get(-27880545);
                            if (method5 == null) {
                                Class cls5 = (Class) onCameraWillChange.read((char) (Process.getGidForName("") + 4815), 1688 - Color.red(0), 27 - View.MeasureSpec.makeMeasureSpec(0, 0));
                                byte b8 = (byte) 0;
                                byte b9 = (byte) (b8 + 1);
                                Object[] objArr11 = new Object[1];
                                d(b8, b9, (byte) (-b9), objArr11);
                                method5 = cls5.getMethod((String) objArr11[0], Object.class, Object.class, Integer.TYPE, Integer.TYPE, Object.class, Object.class, Integer.TYPE, Integer.TYPE, Object.class, Integer.TYPE, Object.class);
                                onCameraWillChange.PlaybackStateCompat.put(-27880545, method5);
                            }
                            obj = null;
                            int iIntValue = ((Integer) ((Method) method5).invoke(null, objArr10)).intValue();
                            int i10 = (addonstyleimagemissinglistener.RemoteActionCompatParcelizer * cCharValue) + addonstyleimagemissinglistener.IconCompatParcelizer;
                            cArr4[addonstyleimagemissinglistener.asBinder] = cArr2[iIntValue];
                            cArr4[addonstyleimagemissinglistener.asBinder + 1] = cArr2[i10];
                        } else {
                            obj = null;
                            if (addonstyleimagemissinglistener.read == addonstyleimagemissinglistener.RemoteActionCompatParcelizer) {
                                addonstyleimagemissinglistener.AudioAttributesImplApi21Parcelizer = ((addonstyleimagemissinglistener.AudioAttributesImplApi21Parcelizer + cCharValue) - 1) % cCharValue;
                                addonstyleimagemissinglistener.IconCompatParcelizer = ((addonstyleimagemissinglistener.IconCompatParcelizer + cCharValue) - 1) % cCharValue;
                                int i11 = (addonstyleimagemissinglistener.read * cCharValue) + addonstyleimagemissinglistener.AudioAttributesImplApi21Parcelizer;
                                int i12 = (addonstyleimagemissinglistener.RemoteActionCompatParcelizer * cCharValue) + addonstyleimagemissinglistener.IconCompatParcelizer;
                                cArr4[addonstyleimagemissinglistener.asBinder] = cArr2[i11];
                                cArr4[addonstyleimagemissinglistener.asBinder + 1] = cArr2[i12];
                            } else {
                                int i13 = (addonstyleimagemissinglistener.read * cCharValue) + addonstyleimagemissinglistener.IconCompatParcelizer;
                                int i14 = (addonstyleimagemissinglistener.RemoteActionCompatParcelizer * cCharValue) + addonstyleimagemissinglistener.AudioAttributesImplApi21Parcelizer;
                                cArr4[addonstyleimagemissinglistener.asBinder] = cArr2[i13];
                                cArr4[addonstyleimagemissinglistener.asBinder + 1] = cArr2[i14];
                                int i15 = $10 + 47;
                                $11 = i15 % 128;
                                i3 = 2;
                                int i16 = i15 % 2;
                            }
                        }
                        i3 = 2;
                    }
                    addonstyleimagemissinglistener.asBinder += i3;
                    obj2 = obj;
                }
            }
            int i17 = 0;
            while (i17 < i) {
                cArr4[i17] = (char) (cArr4[i17] ^ 13722);
                i17++;
                int i18 = $11 + 87;
                $10 = i18 % 128;
                int i19 = i18 % 2;
            }
            objArr[0] = new String(cArr4);
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0023  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001b  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0023 -> B:11:0x002d). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void d(byte r6, byte r7, short r8, java.lang.Object[] r9) {
            /*
                int r6 = r6 * 2
                int r0 = 1 - r6
                byte[] r1 = o.projectedMetersForLatLng.AnonymousClass15.$$d
                int r8 = r8 + 4
                int r7 = r7 + 97
                byte[] r0 = new byte[r0]
                r2 = 0
                int r6 = 0 - r6
                if (r1 != 0) goto L15
                r7 = r6
                r3 = r8
                r4 = r2
                goto L2d
            L15:
                r3 = r2
            L16:
                byte r4 = (byte) r7
                r0[r3] = r4
                if (r3 != r6) goto L23
                java.lang.String r6 = new java.lang.String
                r6.<init>(r0, r2)
                r9[r2] = r6
                return
            L23:
                int r8 = r8 + 1
                int r3 = r3 + 1
                r4 = r1[r8]
                r5 = r3
                r3 = r8
                r8 = r4
                r4 = r5
            L2d:
                int r7 = r7 + r8
                r8 = r3
                r3 = r4
                goto L16
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass15.d(byte, byte, short, java.lang.Object[]):void");
        }
    };
    public static Map<String, Object> read = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.25
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/AssignToken");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.25.3
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.25.1
                {
                    put("CustomerID", "user:customerId:required");
                }
            });
        }
    };
    public static Map<String, Object> setExpandedFormat = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.33
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/IsPhoneRegistered");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.33.4
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.33.3
                {
                    put("PhoneNumber", "request:phoneNumber:required");
                }
            });
        }
    };
    public static Map<String, Object> setTransitioning = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.42
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/RegisterUsername");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.42.5
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.42.1
                {
                    put("Title", "request:title:required");
                    put("FirstName", "request:firstName:required");
                    put("LastName", "request:lastName:required");
                    put("DateOfBirthYear", "request:birthYear:required");
                    put("DateOfBirthMonth", "request:birthMonth:required");
                    put("DateOfBirthDay", "request:birthDay:required");
                    put("PinNumber", "request:pin:required");
                    put("PhoneNumber", "request:phoneNumber:required");
                }
            });
        }
    };
    public static Map<String, Object> setSubtitle = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.59
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ResendActivationCode");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.59.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.59.5
                {
                    put("To", "request:phoneNumber:required");
                }
            });
        }
    };
    public static Map<String, Object> asBinder = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.67
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ActivateAccount");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.67.4
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.67.2
                {
                    put("ActivationCode", "request:activationCode:required");
                    put("PhoneNumber", "request:phoneNumber:required");
                }
            });
        }
    };
    public static Map<String, Object> setHasNonEmbeddedTabs = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.71
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/SendVerificationCode");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.71.1
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.71.5
                {
                    put("PlayerId", "request:playerId:required");
                }
            });
        }
    };
    public static Map<String, Object> setMenu = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.72
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/SendResetPINSMS");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.72.4
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.72.2
                {
                    put("First_Name", "request:firstName:required");
                    put("Last_Name", "request:lastName:required");
                    put("Birthday", "request:birthday:required");
                    put("PlayerId", "request:playerId:required");
                    put("IsSpecialResetPINFlag", "request:isSpecialResetPINFlag:required");
                    put("UniqueKey", "user:uniqueKey:required");
                }
            });
        }
    };
    public static Map<String, Object> setWindowTitle = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.5

        /* renamed from: o.projectedMetersForLatLng$5$4, reason: invalid class name */
        public class AnonymousClass4 extends HashMap<String, String> {
            private static final byte[] $$d = {65, -121, 99, -66};
            private static final int $$e = 180;
            private static int $10 = 0;
            private static int $11 = 1;
            private static final byte[] $$a = {94, 119, 119, -74, 8, -2, 0, 23, -44, 44, 10, -5, 6, 18, 8, 5, 4, -21, 35, -12, 18, 10, -13, 7, 22};
            private static final int $$b = 156;
            private static int IconCompatParcelizer = 0;
            private static int AudioAttributesCompatParcelizer = 1;
            private static long RemoteActionCompatParcelizer = -1864964313293061584L;
            private static int onTransact = 1207138088;
            private static char asBinder = 560;
            private static char[] read = {30392, 30521, 30439, 30434, 30413, 30400, 30402, 30404, 30405, 30400, 30402, 30208, 30288, 30302, 30289, 30300, 30295, 30215, 30393, 30395, 30276, 30275, 30277, 30394, 30395, 30208, 30281, 30288, 30293, 30293, 30290, 30312, 30324, 30302, 30302, 30280, 30292, 30298, 30299, 30290, 30285, 30282, 30290, 30290, 30283, 30281, 30327, 30326, 30499, 30444, 30498, 30515, 30501, 30514, 30511, 30496, 30510, 30444, 30511, 30496, 30496, 30517, 30496, 30501, 30498, 30515, 30513, 30516, 30501, 30508, 30513, 30509, 30444, 30509, 30517, 30498, 30499, 30489, 30283, 30429, 30424, 30439, 30429, 30428, 30463, 30452, 30430, 30463, 30462, 30416, 30417, 30463, 30448, 30417, 30417, 30418, 30455, 30451, 30416, 30417, 30429, 30460, 30460, 30424, 30425, 30417, 30286, 30411, 30408, 30418, 30423, 30408, 30401, 30412, 30420, 30423, 30442, 30433, 30403, 30374, 30386, 30376, 30396, 30385, 30387, 30398, 30368, 30221, 30290, 30290, 30295, 30313, 30321, 30301, 30298, 30290, 30295, 30323, 30313, 30291, 30280, 30405, 30501, 30498, 30499, 30501, 30280, 30429, 30426, 30436, 30446, 30437, 30425, 30438, 30434, 30446, 30439, 30438, 30216, 30290, 30290, 30301, 30289, 30293, 30292, 30288, 30301, 30291, 30281, 30280, 30295, 30281, 30331, 30385, 30388, 30376, 30377, 30377, 30379, 30208, 30283, 30295, 30291, 30295, 30293, 30325, 30211, 30280, 30288, 30303, 30301, 30303, 30302, 30288, 30292, 30300, 30298, 30295, 30295, 30281, 30290, 30288, 30282, 30288, 30291, 30282, 30219, 30301, 30299, 30288, 30282, 30295, 30295, 30291, 30289, 30273, 30415, 30413, 30415, 30403, 30434, 30424, 30406, 30412, 30423, 30211, 30282, 30288, 30299, 30301, 30290, 30281, 30283, 30285, 30293, 30324, 30332, 30398, 30385, 30399, 30392, 30278, 30286, 30279, 30392, 30277, 30272, 30275, 30392, 30393, 30393, 30305, 30347, 30347, 30353, 30353, 30344, 30390, 30385, 30366, 30367, 30355, 30390, 30398, 30366, 30359, 30358, 30388, 30254, 30312, 30287, 30287, 30282, 30293, 30288, 30327, 30321, 30300, 30290, 30210, 30292, 30288, 30288, 30288, 30281, 30313, 30321, 30300, 30290, 30327, 30208, 30281, 30327, 30321, 30290, 30294, 30291, 30289, 30320, 30322, 30290, 30280, 30282, 30386, 30499, 30498, 30498, 30503, 30488, 30490, 30254, 30327, 30290, 30300, 30321, 30324, 30303, 30299, 30288, 30292, 30324, 30321, 30291, 30291, 30299, 30320, 30217, 30299, 30320, 30230, 30327, 30290, 30300, 30292, 30314, 30324, 30303, 30299, 30288, 30292, 30324, 30321, 30291, 30373, 30479, 30504, 30422, 30504, 30479, 30479, 30474, 30485, 30480, 30519, 30513, 30492, 30482, 30519, 30423, 30512, 30227, 30282, 30377, 30387, 30379, 30273, 30295, 30377, 30287, 30282, 30391, 30376, 30369, 30370, 30370, 30287, 30326, 30456, 30424, 30438, 30425, 30342, 30337, 30445, 30444, 30432, 30340, 30336, 30439, 30458, 30457, 30427, 30429, 30459, 30343, 30432, 30437, 30426, 30431, 30431, 30456, 30323, 30285, 30316, 30286, 30373, 30373, 30368, 30379, 30390, 30285, 30272, 30378, 30386, 30222, 30290, 30300, 30321, 30315, 30285, 30312, 30230, 30216, 30320, 30312, 30293, 30289, 30288, 30323, 30327, 30295, 30283, 30280, 30280, 30282, 30312, 30326, 30280, 30281, 30210, 30284, 30275, 30379, 30386, 30387, 30312, 30362, 30366, 30367, 30367, 30353, 30399, 30219, 30299, 30298, 30290, 30292, 30311, 30328, 30323, 30291, 30302, 30303, 30324, 30334, 30290, 30290, 30300};

            AnonymousClass4() throws Throwable {
                Object[] objArr = new Object[1];
                a(new char[]{7350, 51773, 60742, 38067}, new char[]{0, 0, 0, 0}, Color.alpha(0), (char) ('0' - AndroidCharacter.getMirror('0')), new char[]{1921, 55869, 22631, 50786, 25803, 2706, 20250, 56493}, objArr);
                put((String) objArr[0], "request:playerId:required");
                put("VerificationCode", "request:verificationCode:required");
            }

            /*  JADX ERROR: NoSuchElementException in pass: ReplaceNewArray
                java.util.NoSuchElementException
                        at java.base/java.util.TreeMap.key(TreeMap.java:1637)
                        at java.base/java.util.TreeMap.lastKey(TreeMap.java:309)
                        at jadx.core.dex.visitors.ReplaceNewArray.processNewArray(ReplaceNewArray.java:171)
                        at jadx.core.dex.visitors.ReplaceNewArray.processInsn(ReplaceNewArray.java:72)
                        at jadx.core.dex.visitors.ReplaceNewArray.visit(ReplaceNewArray.java:53)
                */
            public static java.lang.Object[] RemoteActionCompatParcelizer$3e717610(int r67, int r68, java.lang.Object r69, int r70) throws java.lang.Throwable {
                /*
                    Method dump skipped, instructions count: 22009
                    To view this dump add '--comments-level debug' option
                */
                throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass5.AnonymousClass4.RemoteActionCompatParcelizer$3e717610(int, int, java.lang.Object, int):java.lang.Object[]");
            }

            private static void a(char[] cArr, char[] cArr2, int i, char c, char[] cArr3, Object[] objArr) throws Throwable {
                int i2;
                int i3 = 2;
                int i4 = 2 % 2;
                addOnDidFinishLoadingStyleListener addondidfinishloadingstylelistener = new addOnDidFinishLoadingStyleListener();
                int length = cArr.length;
                char[] cArr4 = new char[length];
                int length2 = cArr2.length;
                char[] cArr5 = new char[length2];
                System.arraycopy(cArr, 0, cArr4, 0, length);
                System.arraycopy(cArr2, 0, cArr5, 0, length2);
                cArr4[0] = (char) (cArr4[0] ^ c);
                cArr5[2] = (char) (cArr5[2] + ((char) i));
                int length3 = cArr3.length;
                char[] cArr6 = new char[length3];
                addondidfinishloadingstylelistener.asInterface = 0;
                int i5 = $11 + 115;
                $10 = i5 % 128;
                int i6 = i5 % 2;
                while (addondidfinishloadingstylelistener.asInterface < length3) {
                    int i7 = $10 + 21;
                    $11 = i7 % 128;
                    int i8 = i7 % i3;
                    try {
                        Object[] objArr2 = {addondidfinishloadingstylelistener};
                        Object method = onCameraWillChange.PlaybackStateCompat.get(662089593);
                        if (method == null) {
                            Class cls = (Class) onCameraWillChange.read((char) TextUtils.getOffsetAfter("", 0), View.resolveSizeAndState(0, 0, 0) + 1442, 20 - (ViewConfiguration.getKeyRepeatTimeout() >> 16));
                            byte b = (byte) 0;
                            byte b2 = (byte) (b + 1);
                            Object[] objArr3 = new Object[1];
                            d(b, b2, (byte) (-b2), objArr3);
                            method = cls.getMethod((String) objArr3[0], Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(662089593, method);
                        }
                        int iIntValue = ((Integer) ((Method) method).invoke(null, objArr2)).intValue();
                        Object[] objArr4 = {addondidfinishloadingstylelistener};
                        Object method2 = onCameraWillChange.PlaybackStateCompat.get(-105134515);
                        if (method2 == null) {
                            Class cls2 = (Class) onCameraWillChange.read((char) ((-1) - TextUtils.lastIndexOf("", '0', 0)), 543 - (TypedValue.complexToFloat(0) > 0.0f ? 1 : (TypedValue.complexToFloat(0) == 0.0f ? 0 : -1)), 35 - TextUtils.getCapsMode("", 0, 0));
                            byte b3 = (byte) 0;
                            byte b4 = (byte) (b3 + 3);
                            Object[] objArr5 = new Object[1];
                            d(b3, b4, (byte) (b4 - 4), objArr5);
                            method2 = cls2.getMethod((String) objArr5[0], Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(-105134515, method2);
                        }
                        int iIntValue2 = ((Integer) ((Method) method2).invoke(null, objArr4)).intValue();
                        Object[] objArr6 = {addondidfinishloadingstylelistener, Integer.valueOf(cArr4[addondidfinishloadingstylelistener.asInterface % 4] * 32718), Integer.valueOf(cArr5[iIntValue])};
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(-576167559);
                        if (method3 == null) {
                            method3 = ((Class) onCameraWillChange.read((char) (20854 - ((Process.getThreadPriority(0) + 20) >> 6)), TextUtils.indexOf((CharSequence) "", '0', 0, 0) + 101, TextUtils.indexOf("", "") + 17)).getMethod("u", Object.class, Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-576167559, method3);
                        }
                        ((Method) method3).invoke(null, objArr6);
                        Object[] objArr7 = {Integer.valueOf(cArr4[iIntValue2] * 32718), Integer.valueOf(cArr5[iIntValue])};
                        Object method4 = onCameraWillChange.PlaybackStateCompat.get(1229688017);
                        if (method4 != null) {
                            i2 = 2;
                        } else {
                            i2 = 2;
                            method4 = ((Class) onCameraWillChange.read((char) ((ViewConfiguration.getTouchSlop() >> 8) + 60060), (ViewConfiguration.getScrollBarSize() >> 8) + 79, (AudioTrack.getMaxVolume() > 0.0f ? 1 : (AudioTrack.getMaxVolume() == 0.0f ? 0 : -1)) + 20)).getMethod("z", Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(1229688017, method4);
                        }
                        cArr5[iIntValue2] = ((Character) ((Method) method4).invoke(null, objArr7)).charValue();
                        cArr4[iIntValue2] = addondidfinishloadingstylelistener.read;
                        cArr6[addondidfinishloadingstylelistener.asInterface] = (char) ((((cArr4[iIntValue2] ^ cArr3[addondidfinishloadingstylelistener.asInterface]) ^ (RemoteActionCompatParcelizer ^ (-1864964313293061584L))) ^ ((int) (onTransact ^ (-1864964313293061584L)))) ^ ((char) (asBinder ^ (-1864964313293061584L))));
                        addondidfinishloadingstylelistener.asInterface++;
                        i3 = i2;
                    } catch (Throwable th) {
                        Throwable cause = th.getCause();
                        if (cause == null) {
                            throw th;
                        }
                        throw cause;
                    }
                }
                objArr[0] = new String(cArr6);
            }

            /* JADX WARN: Removed duplicated region for block: B:10:0x0024  */
            /* JADX WARN: Removed duplicated region for block: B:8:0x001c  */
            /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0024 -> B:11:0x002b). Please report as a decompilation issue!!! */
            /*
                Code decompiled incorrectly, please refer to instructions dump.
                To view partially-correct add '--show-bad-code' argument
            */
            private static void b(int r6, short r7, byte r8, java.lang.Object[] r9) {
                /*
                    int r6 = 16 - r6
                    int r0 = 10 - r7
                    byte[] r1 = o.projectedMetersForLatLng.AnonymousClass5.AnonymousClass4.$$a
                    int r8 = r8 + 97
                    byte[] r0 = new byte[r0]
                    int r7 = 9 - r7
                    r2 = 0
                    if (r1 != 0) goto L13
                    r4 = r8
                    r3 = r2
                    r8 = r6
                    goto L2b
                L13:
                    r3 = r2
                L14:
                    r5 = r8
                    r8 = r6
                    r6 = r5
                    byte r4 = (byte) r6
                    r0[r3] = r4
                    if (r3 != r7) goto L24
                    java.lang.String r6 = new java.lang.String
                    r6.<init>(r0, r2)
                    r9[r2] = r6
                    return
                L24:
                    int r3 = r3 + 1
                    r4 = r1[r8]
                    r5 = r8
                    r8 = r6
                    r6 = r5
                L2b:
                    int r6 = r6 + 1
                    int r8 = r8 + r4
                    int r8 = r8 + (-5)
                    goto L14
                */
                throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass5.AnonymousClass4.b(int, short, byte, java.lang.Object[]):void");
            }

            private static void c(byte[] bArr, int[] iArr, boolean z, Object[] objArr) throws Throwable {
                int i;
                int i2;
                int i3 = 2 % 2;
                addOnDidBecomeIdleListener addondidbecomeidlelistener = new addOnDidBecomeIdleListener();
                int i4 = 0;
                int i5 = iArr[0];
                int i6 = 1;
                int i7 = iArr[1];
                int i8 = iArr[2];
                int i9 = iArr[3];
                char[] cArr = read;
                int i10 = -1;
                if (cArr != null) {
                    int length = cArr.length;
                    char[] cArr2 = new char[length];
                    int i11 = 0;
                    while (i11 < length) {
                        int i12 = $10 + i6;
                        $11 = i12 % 128;
                        if (i12 % 2 == 0) {
                            try {
                                Object[] objArr2 = new Object[i6];
                                objArr2[i4] = Integer.valueOf(cArr[i11]);
                                Object method = onCameraWillChange.PlaybackStateCompat.get(-1605641787);
                                if (method != null) {
                                    i2 = length;
                                } else {
                                    Class cls = (Class) onCameraWillChange.read((char) ((CdmaCellLocation.convertQuartSecToDecDegrees(i4) > 0.0d ? 1 : (CdmaCellLocation.convertQuartSecToDecDegrees(i4) == 0.0d ? 0 : -1)) + 37361), 1300 - Gravity.getAbsoluteGravity(i4, i4), TextUtils.getCapsMode("", i4, i4) + 12);
                                    byte b = (byte) i4;
                                    i2 = length;
                                    Object[] objArr3 = new Object[1];
                                    d(b, (byte) (b + 5), (byte) i10, objArr3);
                                    method = cls.getMethod((String) objArr3[0], Integer.TYPE);
                                    onCameraWillChange.PlaybackStateCompat.put(-1605641787, method);
                                }
                                cArr2[i11] = ((Character) ((Method) method).invoke(null, objArr2)).charValue();
                            } catch (Throwable th) {
                                Throwable cause = th.getCause();
                                if (cause == null) {
                                    throw th;
                                }
                                throw cause;
                            }
                        } else {
                            i2 = length;
                            Object[] objArr4 = {Integer.valueOf(cArr[i11])};
                            Object method2 = onCameraWillChange.PlaybackStateCompat.get(-1605641787);
                            if (method2 == null) {
                                Class cls2 = (Class) onCameraWillChange.read((char) (TextUtils.lastIndexOf("", '0') + 37362), 1300 - Color.argb(0, 0, 0, 0), 12 - (CdmaCellLocation.convertQuartSecToDecDegrees(0) > 0.0d ? 1 : (CdmaCellLocation.convertQuartSecToDecDegrees(0) == 0.0d ? 0 : -1)));
                                byte b2 = (byte) 0;
                                Object[] objArr5 = new Object[1];
                                d(b2, (byte) (b2 + 5), (byte) (-1), objArr5);
                                method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE);
                                onCameraWillChange.PlaybackStateCompat.put(-1605641787, method2);
                            }
                            cArr2[i11] = ((Character) ((Method) method2).invoke(null, objArr4)).charValue();
                            i11++;
                        }
                        length = i2;
                        i4 = 0;
                        i6 = 1;
                        i10 = -1;
                    }
                    cArr = cArr2;
                }
                char[] cArr3 = new char[i7];
                System.arraycopy(cArr, i5, cArr3, 0, i7);
                if (bArr != null) {
                    int i13 = $10 + 17;
                    $11 = i13 % 128;
                    int i14 = i13 % 2;
                    char[] cArr4 = new char[i7];
                    addondidbecomeidlelistener.onTransact = 0;
                    char c = 0;
                    while (addondidbecomeidlelistener.onTransact < i7) {
                        if (bArr[addondidbecomeidlelistener.onTransact] == 1) {
                            int i15 = addondidbecomeidlelistener.onTransact;
                            Object[] objArr6 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                            Object method3 = onCameraWillChange.PlaybackStateCompat.get(-2027528084);
                            if (method3 == null) {
                                Class cls3 = (Class) onCameraWillChange.read((char) ((TypedValue.complexToFraction(0, 0.0f, 0.0f) > 0.0f ? 1 : (TypedValue.complexToFraction(0, 0.0f, 0.0f) == 0.0f ? 0 : -1)) + 58526), (ViewConfiguration.getTapTimeout() >> 16) + 230, 25 - (ViewConfiguration.getTapTimeout() >> 16));
                                byte b3 = (byte) 0;
                                Object[] objArr7 = new Object[1];
                                d(b3, (byte) (b3 | 9), (byte) (-1), objArr7);
                                method3 = cls3.getMethod((String) objArr7[0], Integer.TYPE, Integer.TYPE);
                                onCameraWillChange.PlaybackStateCompat.put(-2027528084, method3);
                            }
                            cArr4[i15] = ((Character) ((Method) method3).invoke(null, objArr6)).charValue();
                        } else {
                            int i16 = addondidbecomeidlelistener.onTransact;
                            Object[] objArr8 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                            Object method4 = onCameraWillChange.PlaybackStateCompat.get(613310274);
                            if (method4 == null) {
                                Class cls4 = (Class) onCameraWillChange.read((char) (MotionEvent.axisFromString("") + 1), Process.getGidForName("") + 1289, 12 - TextUtils.indexOf("", "", 0));
                                byte b4 = (byte) 0;
                                byte b5 = b4;
                                Object[] objArr9 = new Object[1];
                                d(b4, b5, (byte) (b5 - 1), objArr9);
                                method4 = cls4.getMethod((String) objArr9[0], Integer.TYPE, Integer.TYPE);
                                onCameraWillChange.PlaybackStateCompat.put(613310274, method4);
                            }
                            cArr4[i16] = ((Character) ((Method) method4).invoke(null, objArr8)).charValue();
                        }
                        c = cArr4[addondidbecomeidlelistener.onTransact];
                        try {
                            Object[] objArr10 = {addondidbecomeidlelistener, addondidbecomeidlelistener};
                            Object method5 = onCameraWillChange.PlaybackStateCompat.get(207891030);
                            if (method5 == null) {
                                Class cls5 = (Class) onCameraWillChange.read((char) (38149 - (ViewConfiguration.getKeyRepeatDelay() >> 16)), (KeyEvent.getMaxKeyCode() >> 16) + 1874, 24 - (ViewConfiguration.getZoomControlsTimeout() > 0L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 0L ? 0 : -1)));
                                byte b6 = (byte) 0;
                                byte b7 = (byte) (b6 + 2);
                                Object[] objArr11 = new Object[1];
                                d(b6, b7, (byte) (b7 - 3), objArr11);
                                method5 = cls5.getMethod((String) objArr11[0], Object.class, Object.class);
                                onCameraWillChange.PlaybackStateCompat.put(207891030, method5);
                            }
                            ((Method) method5).invoke(null, objArr10);
                        } catch (Throwable th2) {
                            Throwable cause2 = th2.getCause();
                            if (cause2 == null) {
                                throw th2;
                            }
                            throw cause2;
                        }
                    }
                    cArr3 = cArr4;
                }
                if (i9 > 0) {
                    int i17 = $11 + 65;
                    $10 = i17 % 128;
                    int i18 = i17 % 2;
                    char[] cArr5 = new char[i7];
                    i = 0;
                    System.arraycopy(cArr3, 0, cArr5, 0, i7);
                    int i19 = i7 - i9;
                    System.arraycopy(cArr5, 0, cArr3, i19, i9);
                    System.arraycopy(cArr5, i9, cArr3, 0, i19);
                } else {
                    i = 0;
                }
                if (z) {
                    char[] cArr6 = new char[i7];
                    while (true) {
                        addondidbecomeidlelistener.onTransact = i;
                        if (addondidbecomeidlelistener.onTransact >= i7) {
                            break;
                        }
                        cArr6[addondidbecomeidlelistener.onTransact] = cArr3[(i7 - addondidbecomeidlelistener.onTransact) - 1];
                        i = addondidbecomeidlelistener.onTransact + 1;
                    }
                    cArr3 = cArr6;
                }
                if (i8 > 0) {
                    int i20 = $11 + 5;
                    $10 = i20 % 128;
                    int i21 = i20 % 2 != 0 ? 1 : 0;
                    while (true) {
                        addondidbecomeidlelistener.onTransact = i21;
                        if (addondidbecomeidlelistener.onTransact >= i7) {
                            break;
                        }
                        cArr3[addondidbecomeidlelistener.onTransact] = (char) (cArr3[addondidbecomeidlelistener.onTransact] - iArr[2]);
                        i21 = addondidbecomeidlelistener.onTransact + 1;
                    }
                }
                objArr[0] = new String(cArr3);
            }

            private static void d(byte b, int i, byte b2, Object[] objArr) {
                byte[] bArr = $$d;
                int i2 = b2 + 4;
                int i3 = 121 - i;
                int i4 = b * 3;
                byte[] bArr2 = new byte[1 - i4];
                int i5 = 0 - i4;
                int i6 = -1;
                if (bArr == null) {
                    i3 += i2;
                    i2 = i2;
                    i6 = -1;
                }
                while (true) {
                    int i7 = i6 + 1;
                    int i8 = i2 + 1;
                    bArr2[i7] = (byte) i3;
                    if (i7 == i5) {
                        objArr[0] = new String(bArr2, 0);
                        return;
                    } else {
                        i3 += bArr[i8];
                        i2 = i8;
                        i6 = i7;
                    }
                }
            }
        }

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ValidateResetPINInfo");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.5.1
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new AnonymousClass4());
        }
    };
    public static Map<String, Object> setCustomView = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.3
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ResetPIN");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.3.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.3.4
                {
                    put("PlayerId", "request:playerId:required");
                    put("PIN", "request:pin:required");
                    put("AgreementFlag", "request:agreementFlag:required");
                    put("IsSpecialResetPINFlag", "request:isSpecialResetPINFlag:required");
                }
            });
        }
    };
    public static Map<String, Object> setActionBarVisibilityCallback = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.1
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ResetLoginPlayerPIN");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.1.3
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.1.4
                {
                    put("OldPIN", "request:oldPin:required");
                    put("PIN", "request:pin:required");
                    put("PlayerId", "request:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                }
            });
        }
    };
    public static Map<String, Object> setPopupCallback = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.2
        private static short[] asInterface;
        private static final byte[] $$d = {126, -51, 24, 78};
        private static final int $$e = 74;
        private static int $10 = 0;
        private static int $11 = 1;
        private static final byte[] $$a = {4, -116, 64, -60, 8, -1, -8, -23, 37, -42, -11, 10, -18, 7, 0, -7, -7, -4, 21, -35, MqttWireMessage.MESSAGE_TYPE_PINGREQ, -18, -10, MqttWireMessage.MESSAGE_TYPE_PINGRESP, -7, -22, -23, 44, -44, -10, 5, -6, -18, 0, -8, 2};
        private static final int $$b = 57;
        private static int AudioAttributesImplApi26Parcelizer = 0;
        private static int write = 1;
        private static int asBinder = 1830850961;
        private static int read = 1831610344;
        private static int RemoteActionCompatParcelizer = 1133555546;
        private static byte[] onTransact = {127, -59, 42, -56, 63, -58, 21, 44, -125, 63, 48, -56, 63, -58, 53, MqttWireMessage.MESSAGE_TYPE_PINGREQ, -13, -62, -61, -60, 55, -49, 52, 0, 24, -23, 52, -54, -18, 23, -28, 2, -17, -21, -20, -19, 17, 62, -36, 30, -17, 112, -17, 30, -61, 61, 25, -32, 19, -11, 24, 28, 27, 26, -26, -55, -11, 39, 27, -92, 92, -32, -17, 23, -32, 25, -22, -45, 44, 29, 28, 27, -24, 16, -21, MqttWireMessage.MESSAGE_TYPE_PINGRESP, -4, -10, 5, -10, 122, -16, 69, -56, -8, MqttWireMessage.MESSAGE_TYPE_UNSUBACK, 0, -5, 1, -13, 18, -4, 0, 54, -56, -8, -2, 1, 60, -70, 10, -6, 4, 59, -51, -18, MqttWireMessage.MESSAGE_TYPE_DISCONNECT, 55, 5, -100, 111, 100, -97, 101, -105, 118, -104, 100, 83, -38, -104, 17};

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/IsMember");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.2.3
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "request:playerId:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.2.5
            });
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0024  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001c  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0024 -> B:11:0x0028). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void a(byte r6, int r7, int r8, java.lang.Object[] r9) {
            /*
                int r8 = 34 - r8
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass2.$$a
                int r1 = r7 + 2
                int r6 = r6 + 97
                byte[] r1 = new byte[r1]
                int r7 = r7 + 1
                r2 = 0
                if (r0 != 0) goto L13
                r4 = r7
                r6 = r8
                r3 = r2
                goto L28
            L13:
                r3 = r2
                r5 = r8
                r8 = r6
                r6 = r5
            L17:
                byte r4 = (byte) r8
                r1[r3] = r4
                if (r3 != r7) goto L24
                java.lang.String r6 = new java.lang.String
                r6.<init>(r1, r2)
                r9[r2] = r6
                return
            L24:
                int r3 = r3 + 1
                r4 = r0[r6]
            L28:
                int r4 = -r4
                int r8 = r8 + r4
                int r8 = r8 + (-5)
                int r6 = r6 + 1
                goto L17
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass2.a(byte, int, int, java.lang.Object[]):void");
        }

        /* JADX WARN: Removed duplicated region for block: B:75:0x033b  */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void b(int r17, int r18, byte r19, short r20, int r21, java.lang.Object[] r22) throws java.lang.Throwable {
            /*
                Method dump skipped, instructions count: 937
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass2.b(int, int, byte, short, int, java.lang.Object[]):void");
        }

        private static void c(int i, int i2, short s, Object[] objArr) {
            int i3 = 3 - (i2 * 2);
            byte[] bArr = $$d;
            int i4 = i * 2;
            int i5 = s + 99;
            byte[] bArr2 = new byte[1 - i4];
            int i6 = 0 - i4;
            int i7 = -1;
            if (bArr == null) {
                i7 = -1;
                i5 = (-i3) + i6;
                i3 = i3;
            }
            while (true) {
                int i8 = i7 + 1;
                bArr2[i8] = (byte) i5;
                if (i8 == i6) {
                    objArr[0] = new String(bArr2, 0);
                    return;
                }
                int i9 = i3 + 1;
                i7 = i8;
                i5 = (-bArr[i9]) + i5;
                i3 = i9;
            }
        }

        /* JADX WARN: Code restructure failed: missing block: B:100:0x0c56, code lost:

            if (r1 != null) goto L101;
         */
        /* JADX WARN: Code restructure failed: missing block: B:101:0x0c58, code lost:

            throw r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:102:0x0c59, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:103:0x0c5a, code lost:

            r23 = r5;
            r0 = android.view.KeyEvent.normalizeMetaState(0);
            r1 = r0 * 141;
            r2 = ((r1 | 11954) << 1) - (r1 ^ 11954);
            r1 = ~r0;
            r2 = r2 + (((~(r1 | (-86))) | (~(r1 | r29))) * (-280));
            r3 = ~r0;
            r3 = ~((r3 & r29) | (r3 ^ r29));
            r10 = ~((85 ^ r29) | (85 & r29));
            r2 = (r2 - (~(-(-(((r3 & r10) | (r3 ^ r10)) * 140))))) - 1;
            r3 = ~((r1 | 85) | r29);
            r1 = (r1 & r7) | (r1 ^ r7);
            r1 = ~((r1 & (-86)) | (r1 ^ (-86)));
            r1 = (r1 & r3) | (r3 ^ r1);
            r0 = ~(r0 | ((85 ^ r7) | (85 & r7)));
            r0 = -(-(((r0 & r1) | (r1 ^ r0)) * 140));
            r10 = (r2 & r0) + (r0 | r2);
            r0 = android.os.Process.getThreadPriority(0);
            r0 = -(((r0 & 20) + (r0 | 20)) >> 6);
            r1 = (r0 * 881) + 690906459;
            r2 = ~r0;
            r3 = ~((784107636 & r2) | (r2 ^ 784107636));
            r5 = ~((r2 ^ r29) | (r2 & r29));
            r3 = (r3 & r5) | (r3 ^ r5);
            r5 = ~((784107636 & r29) | (784107636 ^ r29));
            r3 = ((r3 & r5) | (r3 ^ r5)) * (-880);
            r5 = (r1 & r3) + (r1 | r3);
            r1 = ~((r2 ^ r7) | (r2 & r7));
            r1 = (r1 & (-784107637)) | (r1 ^ (-784107637));
            r0 = (r0 & r29) | (r0 ^ r29);
            r2 = ~r0;
            r1 = -(-(((r1 & r2) | (r1 ^ r2)) * (-880)));
            r11 = ((r5 & r1) + (r1 | r5)) + ((~r0) * 880);
         */
        /* JADX WARN: Code restructure failed: missing block: B:104:0x0d16, code lost:

            r0 = -(android.view.ViewConfiguration.getWindowTouchSlop() >> 8);
            r1 = r0 * 471;
            r2 = (((r1 | (-18840)) << 1) - (r1 ^ (-18840))) + ((r0 | (-40)) * (-470));
            r1 = ~r0;
            r1 = ~((r1 & 39) | (r1 ^ 39));
            r3 = ~((39 & r29) | (39 ^ r29));
            r1 = (r1 & r3) | (r1 ^ r3);
            r3 = (r23 ^ r0) | (r23 & r0);
            r3 = ~((r3 & (-40)) | (r3 ^ (-40)));
            r2 = (r2 - (~(-(-(((r1 & r3) | (r1 ^ r3)) * (-470)))))) - 1;
            r1 = 39 | r0;
            r1 = ~((r1 & r29) | (r1 ^ r29));
            r3 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer + 93;
            o.projectedMetersForLatLng.AnonymousClass2.write = r3 % 128;
            r3 = r3 % 2;
            r0 = (r0 & r7) | (r7 ^ r0);
            r0 = ~((r0 & (-40)) | (r0 ^ (-40)));
            r0 = -(-(470 * ((r0 & r1) | (r1 ^ r0))));
            r12 = (byte) (((r2 | r0) << 1) - (r0 ^ r2));
         */
        /* JADX WARN: Code restructure failed: missing block: B:105:0x0d7f, code lost:

            r13 = (short) android.view.View.combineMeasuredStates(0, 0);
            r0 = android.graphics.Color.alpha(0);
            r14 = (r0 & (-832960)) + (r0 | (-832960));
            r0 = new java.lang.Object[1];
            b(r10, r11, r12, r13, r14, r0);
         */
        /* JADX WARN: Code restructure failed: missing block: B:106:0x0d9c, code lost:

            r0 = new java.lang.Object[]{(java.lang.String) r0[0]};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-1098276363);
         */
        /* JADX WARN: Code restructure failed: missing block: B:107:0x0dad, code lost:

            if (r1 == null) goto L109;
         */
        /* JADX WARN: Code restructure failed: missing block: B:109:0x0db0, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) android.text.TextUtils.getTrimmedLength(""), 1312 - (android.view.ViewConfiguration.getMaximumDrawingCacheSize() >> 24), (android.os.SystemClock.elapsedRealtime() > 0 ? 1 : (android.os.SystemClock.elapsedRealtime() == 0 ? 0 : -1)) + 19);
            r10 = new java.lang.Object[1];
            a(r4[4], r4[14], (byte) (-r4[5]), r10);
            r1 = r1.getMethod((java.lang.String) r10[0], java.lang.String.class);
            o.onCameraWillChange.PlaybackStateCompat.put(-1098276363, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:10:0x007d, code lost:

            r1 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 0, java.lang.Integer.valueOf(r10)};
            r3 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:110:0x0dfa, code lost:

            r0 = ((java.lang.reflect.Method) r1).invoke(null, r0);
         */
        /* JADX WARN: Code restructure failed: missing block: B:113:0x0e06, code lost:

            r1 = (android.widget.ExpandableListView.getPackedPositionForChild(0, 0) > 0 ? 1 : (android.widget.ExpandableListView.getPackedPositionForChild(0, 0) == 0 ? 0 : -1));
            r2 = r1 * (-751);
            r4 = ((r2 | 63835) << 1) - (r2 ^ 63835);
            r2 = ~r1;
            r3 = ~((r2 ^ 84) | (r2 & 84));
            r5 = o.projectedMetersForLatLng.AnonymousClass2.write;
            r8 = (r5 ^ 71) + ((r5 & 71) << 1);
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r8 % 128;
            r8 = r8 % 2;
            r5 = ~((r2 ^ r29) | (r2 & r29));
            r4 = r4 + (1504 * ((r3 & r5) | (r3 ^ r5)));
            r3 = (~r1) | (-85);
            r3 = (~((r3 & r29) | (r3 ^ r29))) * (-1504);
            r2 = ~((r2 & (-85)) | (r2 ^ (-85)));
            r1 = ~((r1 & 84) | (84 ^ r1));
            r8 = (((r4 ^ r3) + ((r3 & r4) << 1)) - (~(((r1 & r2) | (r2 ^ r1)) * 752))) - 1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:114:0x0e61, code lost:

            r3 = android.view.KeyEvent.normalizeMetaState(0);
            r2 = r3 * (-464);
            r5 = (r2 ^ (-1708385162)) + ((r2 & (-1708385162)) << 1);
            r1 = ~r3;
            r3 = ~(r29 | (-784107702));
            r3 = -(-(((r3 & r1) | (r1 ^ r3)) * (-465)));
            r4 = (r5 & r3) + (r3 | r5);
            r3 = ~((r1 ^ r29) | (r1 & r29));
            r4 = (r4 - (~(-(-(((r3 & (-784107702)) | (r3 ^ (-784107702))) * 930))))) - 1;
            r1 = (r1 | ((r29 & (-784107702)) | (r29 ^ (-784107702)))) * 465;
            r1 = android.view.MotionEvent.axisFromString("");
            r11 = (short) ((r1 & 1) + (r1 | 1));
            r1 = -(android.view.ViewConfiguration.getTapTimeout() >> 16);
            r2 = r1 * (-183);
            r4 = ((r2 | (-154095195)) << 1) - (r2 ^ (-154095195));
            r2 = ~r1;
            r4 = (r4 - (~(-(-(((r2 ^ (-832947)) | (r2 & (-832947))) * (-368)))))) - 1;
            r12 = r1 | 832946;
            r12 = ((r12 & r7) | (r12 ^ r7)) * 184;
            r13 = ((r4 | r12) << 1) - (r4 ^ r12);
            r2 = ~((r2 & 832946) | (r2 ^ 832946));
            r4 = ~((r7 ^ r1) | (r7 & r1));
            r12 = r13 + (((~((r1 & (-832947)) | (r1 ^ (-832947)))) | ((r2 & r4) | (r2 ^ r4))) * 184);
            r2 = new java.lang.Object[1];
            b(r8, (r4 & r1) + (r1 | r4), (byte) (android.view.KeyEvent.keyCodeFromString("") - 113), r11, r12, r2);
            r0 = r0.equals((java.lang.String) r2[0]);
         */
        /* JADX WARN: Code restructure failed: missing block: B:115:0x0f10, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:116:0x0f11, code lost:

            r1 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:117:0x0f15, code lost:

            if (r1 != null) goto L118;
         */
        /* JADX WARN: Code restructure failed: missing block: B:118:0x0f17, code lost:

            throw r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:119:0x0f18, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:11:0x009b, code lost:

            if (r3 == null) goto L13;
         */
        /* JADX WARN: Code restructure failed: missing block: B:120:0x0f19, code lost:

            r23 = r5;
         */
        /* JADX WARN: Code restructure failed: missing block: B:121:0x0f1b, code lost:

            r0 = false;
         */
        /* JADX WARN: Code restructure failed: missing block: B:122:0x0f1c, code lost:

            r1 = true;
         */
        /* JADX WARN: Code restructure failed: missing block: B:124:0x0f1e, code lost:

            if ((r0 ^ r1) != r1) goto L125;
         */
        /* JADX WARN: Code restructure failed: missing block: B:125:0x0f20, code lost:

            r1 = (-918227048) | r23;
            r1 = (~((r1 & 238193465) | (r1 ^ 238193465))) * 433;
            r3 = ((-1240344366) ^ r1) + ((r1 & (-1240344366)) << 1);
            r1 = ~(((-238193466) & r29) | ((-238193466) ^ r29));
            r0 = ~(((-918227048) & r29) | ((-918227048) ^ r29));
            r3 = ((r3 + (((r1 & (-918227048)) | ((-918227048) ^ r1)) * (-433))) - (~(-(-(((r0 & (-1052478336)) | (r0 ^ (-1052478336))) * 433))))) - 1;
            r0 = ~((1277398127 & r29) | (1277398127 ^ r29));
            r0 = ((r0 & 274227840) | (274227840 ^ r0)) * (-566);
            r2 = (((1958753572 | r0) << 1) - (r0 ^ 1958753572)) - (-1378591368);
            r0 = (~((1551625967 & r29) | (1551625967 ^ r29))) * 566;
         */
        /* JADX WARN: Code restructure failed: missing block: B:126:0x0f90, code lost:

            if (r3 <= ((r2 ^ r0) + ((r0 & r2) << 1))) goto L127;
         */
        /* JADX WARN: Code restructure failed: missing block: B:127:0x0f92, code lost:

            r0 = r29 ^ 31;
            r2 = new java.lang.Object[5];
            r1 = 1;
            r17 = 1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:128:0x0f9b, code lost:

            r0 = (r29 & (-11)) | (r7 & 10);
            r2 = new java.lang.Object[4];
            r1 = 1;
            r17 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:129:0x0fa6, code lost:

            r2[r17] = new int[r1];
            r3 = new int[r1];
            r2[r1] = r3;
            r4 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer;
            r5 = ((r4 | 93) << r1) - (r4 ^ 93);
            r1 = r5 % 128;
            o.projectedMetersForLatLng.AnonymousClass2.write = r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:130:0x0fbd, code lost:

            if ((r5 % 2) == 0) goto L131;
         */
        /* JADX WARN: Code restructure failed: missing block: B:131:0x0fbf, code lost:

            r2[5] = new int[0];
            r5 = 1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:132:0x0fc6, code lost:

            r5 = 1;
            r2[3] = new int[1];
         */
        /* JADX WARN: Code restructure failed: missing block: B:133:0x0fcc, code lost:

            r6 = r2[0];
            ((int[]) r6)[0] = r29;
            r4 = ((r1 | 73) << r5) - (r1 ^ 73);
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r4 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:134:0x0fdf, code lost:

            if ((r4 % 2) != 0) goto L135;
         */
        /* JADX WARN: Code restructure failed: missing block: B:135:0x0fe1, code lost:

            ((int[]) r6)[0] = r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:136:0x0fe7, code lost:

            r3[0] = r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:137:0x0fec, code lost:

            r2[2] = null;
            r0 = (~((-638102933) | r7)) | 33564944;
            r1 = ~(909946844 | r29);
         */
        /* JADX WARN: Code restructure failed: missing block: B:138:0x100f, code lost:

            r3 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 16, java.lang.Integer.valueOf((((r0 | r1) * (-252)) + 811943084) + ((r1 | (~((-604537989) | r7))) * 252))};
            r0 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:139:0x1035, code lost:

            if (r0 != null) goto L140;
         */
        /* JADX WARN: Code restructure failed: missing block: B:13:0x009e, code lost:

            r3 = (java.lang.Class) o.onCameraWillChange.read((char) (android.graphics.PointF.length(0.0f, 0.0f) > 0.0f ? 1 : (android.graphics.PointF.length(0.0f, 0.0f) == 0.0f ? 0 : -1)), android.view.View.combineMeasuredStates(0, 0) + 1715, 24 - (android.view.ViewConfiguration.getScrollDefaultDelay() >> 16));
            r7 = new java.lang.Object[1];
            a(r4[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r4[4], r7);
            r3 = r3.getMethod((java.lang.String) r7[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r3);
         */
        /* JADX WARN: Code restructure failed: missing block: B:141:0x1038, code lost:

            r0 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getTouchSlop() >> 8), (android.view.ViewConfiguration.getLongPressTimeout() >> 16) + 1715, (android.view.ViewConfiguration.getEdgeSlop() >> 16) + 24);
            r7 = new java.lang.Object[1];
            a(r1[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r1[4], r7);
            r0 = r0.getMethod((java.lang.String) r7[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r0);
         */
        /* JADX WARN: Code restructure failed: missing block: B:142:0x1093, code lost:

            r0 = ((java.lang.Integer) ((java.lang.reflect.Method) r0).invoke(null, r3)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:143:0x10a0, code lost:

            r1 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer + 1;
            o.projectedMetersForLatLng.AnonymousClass2.write = r1 % 128;
            r1 = r1 % 2;
            ((int[]) r2[3])[0] = r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:144:0x10b2, code lost:

            return r2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:145:0x10b3, code lost:

            r0 = new java.lang.Object[4];
            r0[0] = new int[]{r29};
            r3 = o.projectedMetersForLatLng.AnonymousClass2.write;
            r4 = (r3 ^ 63) + ((r3 & 63) << 1);
            r3 = r4 % 128;
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r3;
            r4 = r4 % 2;
            r0[1] = new int[]{r29};
            r0[3] = new int[1];
            r2 = (r3 & 1) + (r3 | 1);
            o.projectedMetersForLatLng.AnonymousClass2.write = r2 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:146:0x10e6, code lost:

            if ((r2 % 2) == 0) goto L147;
         */
        /* JADX WARN: Code restructure failed: missing block: B:147:0x10e8, code lost:

            r0[2] = null;
         */
        /* JADX WARN: Code restructure failed: missing block: B:148:0x1110, code lost:

            r3 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 1, java.lang.Integer.valueOf((((-180083984) + ((r29 | (-321004037)) * (-627))) + (((~((-617471465) | r29)) | 326040324) * (-627))) + (((~(617471464 | r7)) | (~(r29 | 326040324))) * 627))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:149:0x1134, code lost:

            if (r1 != null) goto L150;
         */
        /* JADX WARN: Code restructure failed: missing block: B:151:0x1137, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) android.view.Gravity.getAbsoluteGravity(0, 0), 1715 - (android.view.ViewConfiguration.getScrollBarFadeDuration() >> 16), 24 - android.graphics.Color.green(0));
            r7 = new java.lang.Object[1];
            a(r2[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r2[4], r7);
            r1 = r1.getMethod((java.lang.String) r7[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:152:0x118e, code lost:

            r1 = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r3)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:153:0x119b, code lost:

            r2 = r0[2];
         */
        /* JADX WARN: Code restructure failed: missing block: B:154:0x11a0, code lost:

            r0[2] = null;
         */
        /* JADX WARN: Code restructure failed: missing block: B:155:0x11be, code lost:

            r3 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 0, java.lang.Integer.valueOf(((((~((-538574857) | r29)) | 396404420) * 449) + 152686428) + ((396404420 | (~((-538574857) | r7))) * 449))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:156:0x11e2, code lost:

            if (r1 != null) goto L157;
         */
        /* JADX WARN: Code restructure failed: missing block: B:158:0x11e5, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getDoubleTapTimeout() >> 16), (android.view.ViewConfiguration.getTapTimeout() >> 16) + 1715, (android.graphics.PointF.length(0.0f, 0.0f) > 0.0f ? 1 : (android.graphics.PointF.length(0.0f, 0.0f) == 0.0f ? 0 : -1)) + 24);
            r7 = new java.lang.Object[1];
            a(r2[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r2[4], r7);
            r1 = r1.getMethod((java.lang.String) r7[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:159:0x1241, code lost:

            r1 = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r3)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:15:0x00f7, code lost:

            ((int[]) r0[4])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r3).invoke(null, r1)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:160:0x124e, code lost:

            r2 = r0[3];
         */
        /* JADX WARN: Code restructure failed: missing block: B:161:0x1251, code lost:

            ((int[]) r2)[0] = r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:162:0x1256, code lost:

            return r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:167:0x125f, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:168:0x1260, code lost:

            r1 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:169:0x1264, code lost:

            if (r1 != null) goto L170;
         */
        /* JADX WARN: Code restructure failed: missing block: B:16:0x0100, code lost:

            r1 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 0, java.lang.Integer.valueOf(r10)};
            r3 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:170:0x1266, code lost:

            throw r1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:171:0x1267, code lost:

            throw r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:17:0x011e, code lost:

            if (r3 == null) goto L19;
         */
        /* JADX WARN: Code restructure failed: missing block: B:19:0x0121, code lost:

            r3 = (java.lang.Class) o.onCameraWillChange.read((char) android.view.KeyEvent.keyCodeFromString(""), (android.view.ViewConfiguration.getMaximumFlingVelocity() >> 16) + 1715, (android.view.KeyEvent.getMaxKeyCode() >> 16) + 24);
            r7 = new java.lang.Object[1];
            a(r4[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r4[4], r7);
            r3 = r3.getMethod((java.lang.String) r7[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r3);
         */
        /* JADX WARN: Code restructure failed: missing block: B:21:0x0179, code lost:

            ((int[]) r0[3])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r3).invoke(null, r1)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:22:0x017f, code lost:

            return r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:25:0x0183, code lost:

            r3 = ((r4 | 81) << 1) - (r4 ^ 81);
            o.projectedMetersForLatLng.AnonymousClass2.write = r3 % 128;
            r3 = r3 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:26:0x018e, code lost:

            r16 = (-87) - (~(-(-(android.view.ViewConfiguration.getTouchSlop() >> 8))));
            r3 = android.os.Process.myTid() >> 22;
            r4 = (r3 * 70) + 1779712920;
            r5 = ~r3;
            r17 = (r5 ^ 784107653) | (r5 & 784107653);
            r7 = ~((r17 ^ r29) | (r17 & r29));
            r18 = (r3 ^ (-784107654)) | (r3 & (-784107654));
            r9 = ~((r18 ^ r29) | (r18 & r29));
            r7 = -(-(((r7 ^ r9) | (r7 & r9)) * 69));
            r9 = ((r4 | r7) << 1) - (r4 ^ r7);
            r4 = ~((~r3) | (-784107654));
            r5 = ~((r5 & r29) | (r5 ^ r29));
            r4 = (r4 & r5) | (r4 ^ r5);
            r5 = ~((r29 ^ (-784107654)) | (r29 & (-784107654)));
            r4 = -(-(((r4 & r5) | (r4 ^ r5)) * (-69)));
            r17 = (((r9 & r4) + (r4 | r9)) - (~((~(r3 | 784107653)) * 69))) - 1;
            r3 = -(android.view.KeyEvent.getMaxKeyCode() >> 16);
            r5 = ~r3;
            r7 = ~r29;
            r5 = ~((r5 & r7) | (r5 ^ r7));
            r4 = ((r3 * 934) - (-115568)) + (((r5 & 123) | (123 ^ r5)) * (-933));
            r5 = ~r29;
            r10 = ~(123 | r5);
            r9 = ~(123 | r3);
            r3 = (byte) (((r4 + (((r10 ^ r9) | (r9 & r10)) * 933)) - (~((~((r3 & (-124)) | (r3 ^ (-124)))) * 933))) - 1);
            r4 = (short) (android.view.ViewConfiguration.getScrollBarSize() >> 8);
            r9 = android.view.ViewConfiguration.getMaximumFlingVelocity() >> 16;
            r10 = r9 * 491;
            r19 = (r10 ^ 407370252) + ((r10 & 407370252) << 1);
            r10 = ~r9;
            r13 = ((r10 | 833067) | r7) * (-490);
            r20 = ((r19 | r13) << 1) - (r19 ^ r13);
            r9 = ~((833067 & r9) | (833067 ^ r9));
            r13 = ~(833067 | r29);
            r20 = r20 + (((r9 ^ r13) | (r9 & r13)) * 490);
            r10 = r10 * 490;
            r9 = new java.lang.Object[1];
            b(r16, r17, r3, r4, ((r20 | r10) << 1) - (r20 ^ r10), r9);
            r3 = java.lang.Class.forName((java.lang.String) r9[0]);
            r4 = android.view.ViewConfiguration.getMinimumFlingVelocity() >> 16;
            r16 = ((r4 | (-86)) << 1) - (r4 ^ (-86));
            r4 = -android.view.View.combineMeasuredStates(0, 0);
            r9 = r4 * 319;
            r13 = (r9 ^ (-545978752)) + ((r9 & (-545978752)) << 1);
            r9 = ~r4;
            r9 = ~((r9 & r29) | (r9 ^ r29));
            r9 = -(-(((784107647 ^ r9) | (r9 & 784107647)) * (-318)));
            r13 = r5 | r4;
            r17 = (((r13 ^ r9) + ((r9 & r13) << 1)) - (~(((~((784107647 ^ r29) | (784107647 & r29))) | (~((r13 ^ (-784107648)) | (r13 & (-784107648))))) * 318))) - 1;
            r13 = 784107647 | r7;
            r13 = ~((r13 ^ r4) | (r13 & r4));
            r4 = ~((r4 | (-784107648)) | r29);
            r4 = ((r13 ^ r4) | (r4 & r13)) * 318;
            r17 = (r17 & r4) + (r17 | r4);
            r4 = android.view.ViewConfiguration.getWindowTouchSlop() >> 8;
            r13 = (short) (android.view.ViewConfiguration.getMinimumFlingVelocity() >> 16);
            r10 = android.graphics.Color.green(0);
            r9 = r10 * (-661);
            r19 = (r9 & 550642745) + (r9 | 550642745);
            r9 = ~r10;
            r9 = ~((r9 ^ 833044) | (r9 & 833044));
            r9 = -(-(((r7 ^ r9) | (r9 & r7)) * 1324));
            r20 = (r19 & r9) + (r19 | r9);
            r9 = ~((r10 ^ r29) | (r10 & r29));
            r8 = ~((r29 ^ (-833045)) | (r29 & (-833045)));
            r20 = r20 + (((r9 ^ r8) | (r8 & r9)) * (-1324));
            r8 = ~r10;
            r8 = ~((r8 & (-833045)) | (r8 ^ (-833045)));
            r9 = ~(833044 | r10);
            r20 = (r20 - (~(((r8 & r9) | (r8 ^ r9)) * 662))) - 1;
            r8 = new java.lang.Object[1];
            b(r16, r17, (byte) ((r4 & (-84)) + (r4 | (-84))), r13, r20, r8);
            r0 = r3.getMethod((java.lang.String) r8[0], null).invoke(r28, null);
         */
        /* JADX WARN: Code restructure failed: missing block: B:27:0x0375, code lost:

            r3 = android.view.ViewConfiguration.getScrollDefaultDelay() >> 16;
            r4 = (((r3 * (-1965)) - 84624) - (~((r3 | 85) * 983))) - 1;
            r8 = ~r3;
            r9 = ~((85 & r5) | (85 ^ r5));
            r9 = -(-(((r9 & r8) | (r8 ^ r9)) * (-983)));
            r10 = (r4 & r9) + (r4 | r9);
            r3 = ~r3;
            r3 = ~((r3 & r5) | (r3 ^ r5));
            r4 = ~((r8 ^ (-86)) | (r8 & (-86)));
            r3 = -(-(((r3 & r4) | (r3 ^ r4)) * 983));
            r16 = ((r10 | r3) << 1) - (r3 ^ r10);
            r3 = -android.text.TextUtils.lastIndexOf("", '0', 0);
            r4 = r3 * (-300);
            r9 = (r4 ^ (-577310530)) + ((r4 & (-577310530)) << 1);
            r4 = (-784107655) | r3;
            r4 = (~((r4 & r29) | (r4 ^ r29))) * (-301);
            r8 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer;
            r10 = ((r8 | 63) << 1) - (r8 ^ 63);
            o.projectedMetersForLatLng.AnonymousClass2.write = r10 % 128;
            r10 = r10 % 2;
            r9 = r9 + r4;
            r8 = ~((784107654 ^ r29) | (784107654 & r29));
            r10 = ~(r7 | r3);
            r8 = -(-(((r8 & r10) | (r8 ^ r10)) * (-301)));
            r3 = ~r3;
            r3 = ~((r3 & r29) | (r3 ^ r29));
            r17 = ((r9 & r8) + (r8 | r9)) + (((r3 & 784107654) | (784107654 ^ r3)) * com.mapxus.map.mapxusmap.api.services.constant.RoutePlanningInstructionSign.PASS_AREA);
            r3 = -android.graphics.ImageFormat.getBitsPerPixel(0);
            r4 = r3 * 85;
            r8 = (r4 & 7650) + (r4 | 7650);
            r4 = ~r3;
            r4 = ~((r4 & (-91)) | (r4 ^ (-91)));
            r9 = ~r3;
            r4 = r4 | (~((r9 & r7) | (r9 ^ r7)));
            r9 = ~(((-91) & r7) | ((-91) ^ r7));
            r4 = (r4 & r9) | (r4 ^ r9);
            r9 = (r3 ^ 90) | (r3 & 90);
            r10 = ~(r9 | r29);
            r4 = ((r4 & r10) | (r4 ^ r10)) * (-84);
            r10 = (r8 ^ r4) + ((r4 & r8) << 1);
            r3 = r3 | (~(((-91) & r29) | ((-91) ^ r29)));
            r4 = ~((r7 ^ 90) | (r7 & 90));
            r3 = ((r3 & r4) | (r3 ^ r4)) * (-84);
            r4 = ((r10 | r3) << 1) - (r3 ^ r10);
            r3 = ~((r7 ^ 90) | (r7 & 90));
            r8 = ~r9;
            r3 = (byte) (r4 + (((r3 & r8) | (r3 ^ r8)) * 84));
            r4 = (short) android.text.TextUtils.getCapsMode("", 0, 0);
            r8 = (android.telephony.cdma.CdmaCellLocation.convertQuartSecToDecDegrees(0) > 0.0d ? 1 : (android.telephony.cdma.CdmaCellLocation.convertQuartSecToDecDegrees(0) == 0.0d ? 0 : -1));
            r9 = (r8 * 1773) + 737228895;
            r10 = ~r8;
            r10 = ~((r10 ^ 833026) | (r10 & 833026));
            r13 = ~((833026 ^ r29) | (833026 & r29));
            r10 = (r10 ^ r13) | (r10 & r13);
            r13 = (r7 ^ r8) | (r7 & r8);
            r13 = ~((r13 ^ (-833027)) | (r13 & (-833027)));
            r10 = ((r10 ^ r13) | (r10 & r13)) * 886;
            r13 = (r9 & r10) + (r9 | r10);
            r9 = ~((r5 ^ (-833027)) | (r5 & (-833027)));
            r9 = ((r9 & r8) | (r8 ^ r9)) * (-1772);
            r10 = (r13 & r9) + (r9 | r13);
            r8 = -(-((~((r8 & r7) | (r7 ^ r8))) * 886));
            r20 = ((r10 | r8) << 1) - (r8 ^ r10);
            r8 = new java.lang.Object[1];
            b(r16, r17, r3, r4, r20, r8);
            r3 = java.lang.Class.forName((java.lang.String) r8[0]);
            r4 = -(-(android.view.ViewConfiguration.getTapTimeout() >> 16));
            r16 = (r4 ^ (-86)) + ((r4 & (-86)) << 1);
            r4 = -(android.media.AudioTrack.getMaxVolume() > 0.0f ? 1 : (android.media.AudioTrack.getMaxVolume() == 0.0f ? 0 : -1));
            r8 = r4 * 615;
            r10 = ((r8 | (-378348928)) << 1) - (r8 ^ (-378348928));
            r8 = ~r4;
            r13 = ~((r8 ^ (-784107648)) | (r8 & (-784107648)));
            r13 = (r29 ^ r13) | (r13 & r29);
            r12 = ~((784107647 ^ r4) | (784107647 & r4));
            r10 = r10 + (((r13 ^ r12) | (r12 & r13)) * 614);
            r12 = ~r4;
            r12 = (~((r12 & r5) | (r12 ^ r5))) | (~(r8 | (-784107648)));
            r13 = ~((r7 ^ (-784107648)) | (r7 & (-784107648)));
            r12 = ((r12 ^ r13) | (r12 & r13)) * (-1228);
            r13 = (r10 & r12) + (r10 | r12);
            r8 = (r8 & 784107647) | (r8 ^ 784107647);
            r8 = ~((r8 & r7) | (r8 ^ r7));
            r4 = (r4 & r5) | (r5 ^ r4);
            r4 = ~((r4 & (-784107648)) | (r4 ^ (-784107648)));
            r4 = ((r4 & r8) | (r8 ^ r4)) * 614;
            r17 = (r13 & r4) + (r4 | r13);
            r4 = -(android.view.ViewConfiguration.getMaximumDrawingCacheSize() >> 24);
            r8 = r4 * (-344);
            r9 = (r8 ^ (-26488)) + ((r8 & (-26488)) << 1);
            r8 = ~r4;
            r10 = -(-(((~(r8 | (-78))) | (~(r8 | r29))) * 345));
            r12 = (r9 ^ r10) + ((r9 & r10) << 1);
            r9 = ~((r8 ^ r7) | (r8 & r7));
            r4 = ~(r4 | (-78));
            r4 = ((r4 & r9) | (r9 ^ r4)) * 345;
            r9 = ((r12 | r4) << 1) - (r4 ^ r12);
            r4 = r8 | (-78);
            r4 = (byte) ((r9 - (~(-(-((~((r4 & r29) | (r4 ^ r29))) * 345))))) - 1);
            r8 = (short) (android.view.KeyEvent.getMaxKeyCode() >> 16);
            r10 = (android.graphics.PointF.length(0.0f, 0.0f) > 0.0f ? 1 : (android.graphics.PointF.length(0.0f, 0.0f) == 0.0f ? 0 : -1));
            r12 = ~r10;
            r9 = ((r10 * (-496)) - (-413164528)) + ((~((r12 ^ 832992) | (r12 & 832992))) * 497);
            r18 = r12 | 832992;
            r2 = ~((r18 ^ r29) | (r18 & r29));
            r13 = ~(((832992 ^ r7) | (832992 & r7)) | r10);
            r9 = (r9 - (~(-(-(((r2 ^ r13) | (r2 & r13)) * 497))))) - 1;
            r2 = ~((r12 ^ r7) | (r12 & r7));
            r12 = ~((r12 ^ (-832993)) | (r12 & (-832993)));
            r2 = (((r2 & r12) | (r2 ^ r12)) | (~(((r10 & 832992) | (832992 ^ r10)) | r29))) * 497;
            r20 = (r9 & r2) + (r2 | r9);
            r2 = new java.lang.Object[1];
            b(r16, r17, r4, r8, r20, r2);
         */
        /* JADX WARN: Code restructure failed: missing block: B:28:0x0619, code lost:

            if ((r3.getField((java.lang.String) r2[0]).getInt(r0) & 2) == 0) goto L43;
         */
        /* JADX WARN: Code restructure failed: missing block: B:29:0x061b, code lost:

            r0 = o.projectedMetersForLatLng.AnonymousClass2.write;
            r4 = r0 + 35;
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r4 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:30:0x0624, code lost:

            if ((r4 % 2) == 0) goto L32;
         */
        /* JADX WARN: Code restructure failed: missing block: B:31:0x0626, code lost:

            r4 = new java.lang.Object[3];
            r2 = r29;
            r10 = 1;
         */
        /* JADX WARN: Code restructure failed: missing block: B:32:0x062c, code lost:

            r2 = (~(r29 & 1)) & (r29 | 1);
            r4 = new java.lang.Object[4];
            r10 = 0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:33:0x0637, code lost:

            r4[r10] = new int[1];
            r4[1] = new int[]{r2};
            r4[3] = new int[1];
            ((int[]) r4[0])[0] = r29;
            r11 = (r0 ^ 57) + ((r0 & 57) << 1);
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r11 % 128;
            r11 = r11 % 2;
            r4[2] = null;
         */
        /* JADX WARN: Code restructure failed: missing block: B:34:0x0675, code lost:

            r10 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 16, java.lang.Integer.valueOf(((((~((-634726908) | r29)) | 630194442) * (-566)) + 1151280392) + ((~((-4532466) | r29)) * 566))};
            r0 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:35:0x0699, code lost:

            if (r0 == null) goto L37;
         */
        /* JADX WARN: Code restructure failed: missing block: B:37:0x069c, code lost:

            r0 = (java.lang.Class) o.onCameraWillChange.read((char) ((android.os.SystemClock.uptimeMillis() > 0 ? 1 : (android.os.SystemClock.uptimeMillis() == 0 ? 0 : -1)) - 1), android.view.Gravity.getAbsoluteGravity(0, 0) + 1715, (android.view.ViewConfiguration.getLongPressTimeout() >> 16) + 24);
            r13 = new java.lang.Object[1];
            a(r2[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r2[4], r13);
            r0 = r0.getMethod((java.lang.String) r13[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r0);
         */
        /* JADX WARN: Code restructure failed: missing block: B:38:0x06f3, code lost:

            r0 = ((java.lang.Integer) ((java.lang.reflect.Method) r0).invoke(null, r10)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:39:0x0700, code lost:

            r2 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer + 81;
            o.projectedMetersForLatLng.AnonymousClass2.write = r2 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:40:0x070a, code lost:

            if ((r2 % 2) != 0) goto L42;
         */
        /* JADX WARN: Code restructure failed: missing block: B:41:0x070c, code lost:

            ((int[]) r4[2])[0] = r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:42:0x0714, code lost:

            ((int[]) r4[3])[0] = r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:43:0x071d, code lost:

            r4 = new java.lang.Object[]{new int[]{r29}, new int[]{r29}, null, new int[1]};
            r10 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer + 63;
            o.projectedMetersForLatLng.AnonymousClass2.write = r10 % 128;
            r10 = r10 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:44:0x0761, code lost:

            r0 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 0, java.lang.Integer.valueOf(((1080968692 + (((~(r29 | 779413030)) | (-164098759)) * (-668))) + ((779413030 | (~((-164098759) | r29))) * 1336)) + (((-25366721) | r29) * 668))};
            r2 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:45:0x0783, code lost:

            if (r2 == null) goto L47;
         */
        /* JADX WARN: Code restructure failed: missing block: B:47:0x0786, code lost:

            r2 = (java.lang.Class) o.onCameraWillChange.read((char) ((-1) - (android.widget.ExpandableListView.getPackedPositionForChild(0, 0) > 0 ? 1 : (android.widget.ExpandableListView.getPackedPositionForChild(0, 0) == 0 ? 0 : -1))), android.graphics.Color.blue(0) + 1715, 24 - android.view.View.getDefaultSize(0, 0));
            r13 = new java.lang.Object[1];
            a(r10[14], (byte) (-o.projectedMetersForLatLng.AnonymousClass2.$$a[31]), r10[4], r13);
            r2 = r2.getMethod((java.lang.String) r13[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r2);
         */
        /* JADX WARN: Code restructure failed: missing block: B:49:0x07e8, code lost:

            ((int[]) r4[3])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r2).invoke(null, r0)).intValue();
            r0 = o.projectedMetersForLatLng.AnonymousClass2.write;
            r2 = ((r0 | 31) << 1) - (r0 ^ 31);
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r2 % 128;
            r2 = r2 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:51:0x0804, code lost:

            if (((int[]) r4[1])[0] == r29) goto L57;
         */
        /* JADX WARN: Code restructure failed: missing block: B:52:0x0806, code lost:

            r0 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer + 113;
            o.projectedMetersForLatLng.AnonymousClass2.write = r0 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:53:0x0810, code lost:

            if ((r0 % 2) == 0) goto L55;
         */
        /* JADX WARN: Code restructure failed: missing block: B:54:0x0812, code lost:

            return r4;
         */
        /* JADX WARN: Code restructure failed: missing block: B:56:0x0814, code lost:

            throw null;
         */
        /* JADX WARN: Code restructure failed: missing block: B:57:0x0815, code lost:

            r0 = o.onCameraWillChange.PlaybackStateCompat.get(-1175796510);
         */
        /* JADX WARN: Code restructure failed: missing block: B:58:0x0822, code lost:

            if (r0 == null) goto L60;
         */
        /* JADX WARN: Code restructure failed: missing block: B:5:0x0024, code lost:

            if (r28 == null) goto L8;
         */
        /* JADX WARN: Code restructure failed: missing block: B:60:0x0825, code lost:

            r0 = (java.lang.Class) o.onCameraWillChange.read((char) (android.graphics.Color.argb(0, 0, 0, 0) + 37361), android.text.AndroidCharacter.getMirror('0') + 1252, android.graphics.ImageFormat.getBitsPerPixel(0) + 13);
            r2 = (byte) (o.projectedMetersForLatLng.AnonymousClass2.$$b & 87);
            r4 = o.projectedMetersForLatLng.AnonymousClass2.$$a[35];
            r11 = new java.lang.Object[1];
            a(r2, r4, (byte) (r4 | 28), r11);
            r0 = r0.getMethod((java.lang.String) r11[0], null);
            o.onCameraWillChange.PlaybackStateCompat.put(-1175796510, r0);
         */
        /* JADX WARN: Code restructure failed: missing block: B:61:0x086b, code lost:

            r0 = (java.util.Set) ((java.lang.reflect.Method) r0).invoke(null, null);
         */
        /* JADX WARN: Code restructure failed: missing block: B:62:0x0874, code lost:

            r2 = (java.lang.Class) o.onCameraWillChange.read((char) (android.os.Process.getGidForName("") + 37362), 1299 - android.text.TextUtils.indexOf((java.lang.CharSequence) "", '0', 0, 0), (android.media.AudioTrack.getMaxVolume() > 0.0f ? 1 : (android.media.AudioTrack.getMaxVolume() == 0.0f ? 0 : -1)) + 11);
            r4 = o.projectedMetersForLatLng.AnonymousClass2.$$a;
            r10 = r4[14];
            r11 = (byte) (r10 | 9);
            r13 = new java.lang.Object[1];
            a(r10, r11, (byte) (r11 | 18), r13);
         */
        /* JADX WARN: Code restructure failed: missing block: B:63:0x08b7, code lost:

            if (r0.contains(r2.getField((java.lang.String) r13[0]).get(null)) != false) goto L66;
         */
        /* JADX WARN: Code restructure failed: missing block: B:64:0x08b9, code lost:

            r2 = (java.lang.Class) o.onCameraWillChange.read((char) ((android.view.ViewConfiguration.getPressedStateDuration() >> 16) + 37361), android.view.View.resolveSizeAndState(0, 0, 0) + 1300, 12 - (android.view.ViewConfiguration.getKeyRepeatDelay() >> 16));
            r10 = o.projectedMetersForLatLng.AnonymousClass2.$$b;
            r13 = new java.lang.Object[1];
            a((byte) (r10 >>> 2), r4[4], (byte) (r10 & 87), r13);
         */
        /* JADX WARN: Code restructure failed: missing block: B:65:0x08fa, code lost:

            if (r0.contains(r2.getField((java.lang.String) r13[0]).get(null)) == false) goto L177;
         */
        /* JADX WARN: Code restructure failed: missing block: B:67:0x0900, code lost:

            if (android.os.Build.VERSION.SDK_INT != 30) goto L177;
         */
        /* JADX WARN: Code restructure failed: missing block: B:68:0x0902, code lost:

            r0 = new java.lang.Object[]{new int[]{r29}, new int[]{r29}, null, new int[1]};
         */
        /* JADX WARN: Code restructure failed: missing block: B:69:0x0959, code lost:

            r2 = new java.lang.Object[]{java.lang.Integer.valueOf(r30), 0, java.lang.Integer.valueOf((((-12704628) + ((((~((-613850241) | r7)) | 8788992) | (~((-329661549) | r7))) * (-1136))) + ((((~((-613850241) | r29)) | (~((-329661549) | r29))) | (~(934722796 | r7))) * (-568))) + (((~(r29 | (-8788993))) | ((~(613850240 | r7)) | (~(329661548 | r7)))) * 568))};
            r1 = o.onCameraWillChange.PlaybackStateCompat.get(-554193431);
         */
        /* JADX WARN: Code restructure failed: missing block: B:70:0x097b, code lost:

            if (r1 == null) goto L72;
         */
        /* JADX WARN: Code restructure failed: missing block: B:72:0x097e, code lost:

            r1 = (java.lang.Class) o.onCameraWillChange.read((char) (android.view.ViewConfiguration.getKeyRepeatTimeout() >> 16), android.view.MotionEvent.axisFromString("") + 1716, android.view.View.resolveSize(0, 0) + 24);
            r6 = new java.lang.Object[1];
            a(r4[14], (byte) (-r4[31]), r4[4], r6);
            r1 = r1.getMethod((java.lang.String) r6[0], java.lang.Integer.TYPE, java.lang.Integer.TYPE, java.lang.Integer.TYPE);
            o.onCameraWillChange.PlaybackStateCompat.put(-554193431, r1);
         */
        /* JADX WARN: Code restructure failed: missing block: B:74:0x09dd, code lost:

            ((int[]) r0[3])[0] = ((java.lang.Integer) ((java.lang.reflect.Method) r1).invoke(null, r2)).intValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:75:0x09e4, code lost:

            return r0;
         */
        /* JADX WARN: Code restructure failed: missing block: B:78:0x09e9, code lost:

            if (android.os.Build.VERSION.SDK_INT <= 33) goto L103;
         */
        /* JADX WARN: Code restructure failed: missing block: B:79:0x09eb, code lost:

            r0 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer;
            r10 = (r0 & 65) + (r0 | 65);
            o.projectedMetersForLatLng.AnonymousClass2.write = r10 % 128;
            r10 = r10 % 2;
         */
        /* JADX WARN: Code restructure failed: missing block: B:7:0x0027, code lost:

            if (r28 == null) goto L8;
         */
        /* JADX WARN: Code restructure failed: missing block: B:80:0x09f8, code lost:

            r0 = -(-(android.media.AudioTrack.getMaxVolume() > 0.0f ? 1 : (android.media.AudioTrack.getMaxVolume() == 0.0f ? 0 : -1)));
            r16 = (r0 & (-87)) + (r0 | (-87));
            r0 = -(android.telephony.cdma.CdmaCellLocation.convertQuartSecToDecDegrees(0) > 0.0d ? 1 : (android.telephony.cdma.CdmaCellLocation.convertQuartSecToDecDegrees(0) == 0.0d ? 0 : -1));
            r17 = (r0 ^ (-784107704)) + ((r0 & (-784107704)) << 1);
            r0 = android.widget.ExpandableListView.getPackedPositionChild(0);
            r10 = r0 * (-1529);
            r12 = (r10 & 51188) + (r10 | 51188);
            r10 = ~r0;
            r11 = ~((r10 | 66) | r7);
            r13 = ~r0;
            r18 = r13 | (-67);
            r2 = (~((r18 ^ r29) | (r18 & r29))) | r11;
            r18 = (66 ^ r0) | (66 & r0);
            r3 = ~((r18 ^ r29) | (r18 & r29));
            r2 = ((r2 ^ r3) | (r2 & r3)) * 765;
            r3 = ((r12 | r2) << 1) - (r2 ^ r12);
            r2 = ~(r10 | 66);
            r10 = ~((r13 ^ r7) | (r13 & r7));
            r2 = -(-(((r2 & r10) | (r2 ^ r10)) * 1530));
            r10 = ((r3 | r2) << 1) - (r2 ^ r3);
            r2 = ~((r13 ^ r29) | (r13 & r29));
            r3 = (66 ^ r7) | (66 & r7);
            r0 = ~((r0 & r3) | (r3 ^ r0));
            r0 = -(-(((r0 & r2) | (r2 ^ r0)) * 765));
            r0 = (byte) ((r10 ^ r0) + ((r0 & r10) << 1));
         */
        /* JADX WARN: Code restructure failed: missing block: B:81:0x0a88, code lost:

            r2 = -(android.media.AudioTrack.getMaxVolume() > 0.0f ? 1 : (android.media.AudioTrack.getMaxVolume() == 0.0f ? 0 : -1));
            r3 = r2 * 495;
            r10 = (r3 ^ (-493)) + ((r3 & (-493)) << 1);
            r3 = o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer;
            r11 = (r3 & 71) + (r3 | 71);
            o.projectedMetersForLatLng.AnonymousClass2.write = r11 % 128;
            r11 = r11 % 2;
            r11 = -(-((-988) * ((r2 ^ (-2)) | (r2 & (-2)))));
            r12 = (r10 & r11) + (r10 | r11);
            r10 = ~r2;
            r10 = -(-((((r10 & 1) | (1 ^ r10)) | r5) * 494));
            r11 = (r12 & r10) + (r10 | r12);
            r10 = ~r2;
            r12 = ((r3 | 89) << 1) - (r3 ^ 89);
            o.projectedMetersForLatLng.AnonymousClass2.write = r12 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:82:0x0aca, code lost:

            if ((r12 % 2) != 0) goto L86;
         */
        /* JADX WARN: Code restructure failed: missing block: B:83:0x0acc, code lost:

            r2 = ((~((r2 & 1) | (r2 ^ 1))) | ((~((r10 ^ (-2)) | (r10 & (-2)))) | (~((r5 ^ 1) | (r5 & 1))))) * 494;
         */
        /* JADX WARN: Code restructure failed: missing block: B:84:0x0ae7, code lost:

            r3 = new java.lang.Object[1];
            b(r16, r17, r0, (short) (((r11 | r2) << 1) - (r2 ^ r11)), (-832987) >> (android.widget.ExpandableListView.getPackedPositionForChild(1, 1) > 0 ? 1 : (android.widget.ExpandableListView.getPackedPositionForChild(1, 1) == 0 ? 0 : -1)), r3);
            r0 = r3[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:86:0x0b02, code lost:

            r3 = ~(r10 | (-2));
            r10 = ~((r7 ^ 1) | (r7 & 1));
            r3 = (r3 & r10) | (r3 ^ r10);
            r2 = ~(r2 | 1);
            r2 = (short) (r11 + (((r2 & r3) | (r3 ^ r2)) * 494));
            r3 = -(-(android.widget.ExpandableListView.getPackedPositionForChild(0, 0) > 0 ? 1 : (android.widget.ExpandableListView.getPackedPositionForChild(0, 0) == 0 ? 0 : -1)));
            r20 = (r3 ^ (-832987)) + ((r3 & (-832987)) << 1);
            r3 = new java.lang.Object[1];
            b(r16, r17, r0, r2, r20, r3);
            r0 = r3[0];
         */
        /* JADX WARN: Code restructure failed: missing block: B:88:0x0b38, code lost:

            r0 = new java.lang.Object[]{(java.lang.String) r0};
            r2 = o.onCameraWillChange.PlaybackStateCompat.get(1466800587);
         */
        /* JADX WARN: Code restructure failed: missing block: B:89:0x0b49, code lost:

            if (r2 == null) goto L91;
         */
        /* JADX WARN: Code restructure failed: missing block: B:8:0x0029, code lost:

            r0 = new java.lang.Object[]{new int[]{r29}, new int[]{r29}, null, new int[1]};
            r4 = r4 + 27;
            r5 = r4 % 128;
            o.projectedMetersForLatLng.AnonymousClass2.write = r5;
            r4 = r4 % 2;
            r4 = ~r29;
            r10 = ((466282900 + ((r29 | 540614666) * 140)) + ((402823392 | (~(540614666 | r4))) * (-280))) + (((~(r29 | (-402823393))) | ((~(402897122 | r4)) | 540540936)) * 140);
            r1 = ((r5 | 113) << 1) - (r5 ^ 113);
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r1 % 128;
         */
        /* JADX WARN: Code restructure failed: missing block: B:91:0x0b4c, code lost:

            r2 = (java.lang.Class) o.onCameraWillChange.read((char) ((-1) - android.view.MotionEvent.axisFromString("")), 1977 - (android.util.TypedValue.complexToFraction(0, 0.0f, 0.0f) > 0.0f ? 1 : (android.util.TypedValue.complexToFraction(0, 0.0f, 0.0f) == 0.0f ? 0 : -1)), android.widget.ExpandableListView.getPackedPositionChild(0) + 28);
            r8 = new java.lang.Object[1];
            a((byte) (o.projectedMetersForLatLng.AnonymousClass2.$$b & 87), (byte) (-r4[5]), r4[14], r8);
            r2 = r2.getMethod((java.lang.String) r8[0], java.lang.String.class);
            o.onCameraWillChange.PlaybackStateCompat.put(1466800587, r2);
         */
        /* JADX WARN: Code restructure failed: missing block: B:92:0x0b97, code lost:

            r2 = ((java.lang.Long) ((java.lang.reflect.Method) r2).invoke(null, r0)).longValue();
         */
        /* JADX WARN: Code restructure failed: missing block: B:93:0x0ba4, code lost:

            r8 = 430462019;
            r12 = 623;
            r14 = -1;
            r18 = r2 ^ r14;
            r20 = r18 | r8;
            r23 = r5;
            r4 = r29;
            r10 = (((((624 * r8) + ((-622) * r2)) + (((r20 | r4) ^ r14) * r12)) + ((-623) * ((r4 ^ r14) | (((r8 ^ r14) | r2) ^ r14)))) + (r12 * (((r20 ^ r14) | ((r18 | r4) ^ r14)) | ((r8 | r4) ^ r14)))) + 1461411558;
            r1 = true;
         */
        /* JADX WARN: Code restructure failed: missing block: B:94:0x0c39, code lost:

            if (((((int) (r10 >> 32)) & (((617067410 + ((((~(946032953 | r7)) | 1911707931) | (~((-946032954) | r29))) * (-564))) + ((~((-134283297) | r29)) * 1128)) + (((~(1911707931 | r7)) | 811749657) * 564))) | (((int) r10) & (((-694036859) + ((((~(r7 | 461272937)) | 1610647570) | (~((-173421161) | r29))) * 717)) + (((~(461272937 | r29)) | ((~((-173421161) | r7)) | 1610647570)) * 717)))) != 1) goto L96;
         */
        /* JADX WARN: Code restructure failed: missing block: B:95:0x0c3b, code lost:

            r0 = o.projectedMetersForLatLng.AnonymousClass2.write;
            r2 = (r0 ^ 99) + ((r0 & 99) << 1);
            o.projectedMetersForLatLng.AnonymousClass2.AudioAttributesImplApi26Parcelizer = r2 % 128;
            r2 = r2 % 2;
            r0 = true;
         */
        /* JADX WARN: Code restructure failed: missing block: B:96:0x0c4c, code lost:

            r0 = false;
         */
        /* JADX WARN: Code restructure failed: missing block: B:97:0x0c4f, code lost:

            r0 = move-exception;
         */
        /* JADX WARN: Code restructure failed: missing block: B:99:0x0c52, code lost:

            r1 = r0.getCause();
         */
        /* JADX WARN: Code restructure failed: missing block: B:9:0x007b, code lost:

            if ((r1 % 2) == 0) goto L16;
         */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        public static java.lang.Object[] read(android.content.Context r28, int r29, int r30) throws java.lang.Throwable {
            /*
                Method dump skipped, instructions count: 4712
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass2.read(android.content.Context, int, int):java.lang.Object[]");
        }
    };
    public static Map<String, Object> RemoteActionCompatParcelizer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.8
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ActivateBindingAccount");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.8.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.8.5
                {
                    put("PlayerId", "request:playerId:required");
                    put("ActivationCode", "request:activationCode:required");
                }
            });
        }
    };
    public static Map<String, Object> setActionBarHideOffset = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.7
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/SaveTokenInfo");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.7.3
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.7.1
                {
                    put("NotificationToken", "request:deviceToken:required");
                    put("PlatformType", "request:platformType:required");
                    put("PreferLanguage", "request:language:required");
                }
            });
        }
    };
    public static Map<String, Object> setHideOnContentScrollEnabled = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.6
        private static final byte[] $$a = {83, -51, -30, 125, -21, -10, -4, -7, MqttWireMessage.MESSAGE_TYPE_PINGRESP, 34, -36, -19, 9, -8, -1, 41, -46, 0, -5, MqttWireMessage.MESSAGE_TYPE_PINGRESP, -21, 34, -19, -19, MqttWireMessage.MESSAGE_TYPE_PINGRESP, -4, -9, 1, -19, 19, -15, -20, 47, -41, -7, 8, -3, -15, -5, 5};
        private static final int $$b = 102;
        private static int RemoteActionCompatParcelizer = 0;
        private static int onTransact = 1;

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/SendVerificationCodeNewPhone");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.6.4
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.6.2
                {
                    put("PlayerId", "request:playerId:required");
                    put("DateOfBirthYear", "request:birthYear:required");
                    put("DateOfBirthMonth", "request:birthMonth:required");
                    put("DateOfBirthDay", "request:birthDay:required");
                    put("PinNumber", "request:pin:required");
                    put("PhoneNumber", "request:phoneNumber:required");
                }
            });
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0022  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001a  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0022 -> B:11:0x0026). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void a(byte r6, short r7, short r8, java.lang.Object[] r9) {
            /*
                int r8 = r8 + 4
                int r6 = r6 * 5
                int r6 = 28 - r6
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass6.$$a
                int r7 = r7 + 82
                byte[] r1 = new byte[r6]
                r2 = 0
                if (r0 != 0) goto L12
                r3 = r6
                r4 = r2
                goto L26
            L12:
                r3 = r2
            L13:
                int r4 = r3 + 1
                byte r5 = (byte) r7
                r1[r3] = r5
                if (r4 != r6) goto L22
                java.lang.String r6 = new java.lang.String
                r6.<init>(r1, r2)
                r9[r2] = r6
                return
            L22:
                int r8 = r8 + 1
                r3 = r0[r8]
            L26:
                int r3 = -r3
                int r7 = r7 + r3
                int r7 = r7 + (-2)
                r3 = r4
                goto L13
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass6.a(byte, short, short, java.lang.Object[]):void");
        }

        /*  JADX ERROR: NoSuchElementException in pass: ReplaceNewArray
            java.util.NoSuchElementException
                at java.base/java.util.TreeMap.key(TreeMap.java:1637)
                at java.base/java.util.TreeMap.lastKey(TreeMap.java:309)
                at jadx.core.dex.visitors.ReplaceNewArray.processNewArray(ReplaceNewArray.java:171)
                at jadx.core.dex.visitors.ReplaceNewArray.processInsn(ReplaceNewArray.java:72)
                at jadx.core.dex.visitors.ReplaceNewArray.visit(ReplaceNewArray.java:53)
            */
        public static java.lang.Object[] read(android.content.Context r27, int r28, int r29) {
            /*
                Method dump skipped, instructions count: 1658
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass6.read(android.content.Context, int, int):java.lang.Object[]");
        }
    };
    public static Map<String, Object> onTransact = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.9
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ActivateBindingAccountNewPhone");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.9.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.9.5
                {
                    put("PlayerId", "request:playerId:required");
                    put("ActivationCode", "request:activationCode:required");
                    put("AgreementFlag", "request:agreementFlag:required");
                }
            });
        }
    };
    public static Map<String, Object> ActivityResultRegistry1 = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.10
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayerProfile");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.10.5
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaSessionCompatToken = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.14
        {
            put("url", "https://mgm-app-dev.itehk-services.com/api/mlifeApp/v1.0/IsWithinGamingArea");
            put("method", "GET");
            put("connect_timeout", 20000);
            put("read_timeout", 20000);
            put("background", Boolean.TRUE);
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.14.3
                {
                    put("X-DEVICE-ID", "user:mapDeviceId:required");
                }
            });
        }
    };
    public static Map<String, Object> PlaybackStateCompatCustomAction = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.12
        private static short[] onTransact;
        private static final byte[] $$d = {62, -36, -46, 59};
        private static final int $$e = 41;
        private static int $10 = 0;
        private static int $11 = 1;
        private static final byte[] $$a = {28, -42, -18, 19, -23, 44, -44, -10, 5, -6, -18};
        private static final int $$b = 171;
        private static int AudioAttributesImplApi26Parcelizer = 0;
        private static int write = 1;
        private static int RemoteActionCompatParcelizer = 81399378;
        private static int asInterface = 1831610353;
        private static int asBinder = -2030321750;
        private static byte[] read = {103, -73, 77, -69, -70, 73, -71, 75, -98, -100, -68, 71, 97, -106, 66, -68, 71, 1, -10, 122, 72, 67, -88, -113, 9, -71, -73, 75, 65, -82, 66, 78, -7, 10, -85, 87, -87, 75, 110, 42, -53, 37, -7, -4, 100, 35, 34, 37, -42, 46, -11, -36, 55, -45, -49, 16, 35, 34, 37, -42, 46, -11, -36, 54, -5, 1, 38, -64, 34, 118, -83, 66, -96, 87, -82, 125, 68, -21, 87, 88, -96, 87, -82, 93, 100, -101, -86, -85, -84, 95, -89, 92, 127, -105, 99, 124, -122, -111, 105, -103, 103, 109, 126, -77, 96, -111, 127, 104, -103, 68, -123, -97, 103, -105, 105, 99, 112, -67, 110, -97, 4, 15, -3, 1, -48, 107, -4, 30, -13, -9, MqttWireMessage.MESSAGE_TYPE_DISCONNECT, -16, -8, 15, 0, 47, 7, 4, -10, -48, 39, -73, 15, 0, 15, 56, -72, 8, 6, -6, -16, 31, -13, -1, 72, -64, -26, 24, -6};
        private static char[] AudioAttributesCompatParcelizer = {57478, 58238, 57480, 57472, 57504, 57494, 57521, 57567, 57479, 57519, 57548, 58235, 57481, 57554, 57486, 57477, 58239, 57492, 57530, 57538, 57495, 57476, 58232, 57484, 57485, 57505, 57508, 57487, 57516, 57489, 58224, 57507, 57475, 58233, 57515, 57490, 57527, 58234, 57550, 57499, 57510, 58237, 57517, 57473, 57488, 58236, 57522, 57559, 57483};
        private static char AudioAttributesImplApi21Parcelizer = 54655;

        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/IsConnectMGMWiFi");
            put("method", "GET");
            put("background", Boolean.TRUE);
            put("connect_timeout", 20000);
            put("read_timeout", 20000);
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.12.4
                {
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                    put("X-DEVICE-ID", "user:mapDeviceId:required");
                }
            });
            put("PROGRESS_DIALOG_REQUIRED", Boolean.FALSE);
        }

        private static void a(int i, int i2, byte b, short s, int i3, Object[] objArr) throws Throwable {
            int i4;
            long j;
            int i5;
            int i6 = 2 % 2;
            addOnWillStartRenderingMapListener addonwillstartrenderingmaplistener = new addOnWillStartRenderingMapListener();
            StringBuilder sb = new StringBuilder();
            try {
                Object[] objArr2 = {Integer.valueOf(i), Integer.valueOf(asInterface)};
                Object method = onCameraWillChange.PlaybackStateCompat.get(-30937109);
                long j2 = 0;
                if (method == null) {
                    Class cls = (Class) onCameraWillChange.read((char) (ViewConfiguration.getMaximumDrawingCacheSize() >> 24), View.getDefaultSize(0, 0) + 543, (ViewConfiguration.getZoomControlsTimeout() > 0L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 0L ? 0 : -1)) + 34);
                    byte b2 = (byte) 0;
                    byte b3 = (byte) (b2 - 1);
                    Object[] objArr3 = new Object[1];
                    d(b2, b3, (byte) (-b3), objArr3);
                    method = cls.getMethod((String) objArr3[0], Integer.TYPE, Integer.TYPE);
                    onCameraWillChange.PlaybackStateCompat.put(-30937109, method);
                }
                int iIntValue = ((Integer) ((Method) method).invoke(null, objArr2)).intValue();
                if (iIntValue == -1) {
                    int i7 = $11 + 29;
                    $10 = i7 % 128;
                    int i8 = i7 % 2;
                    i4 = 1;
                } else {
                    i4 = 0;
                }
                if (i4 == 0) {
                    j = 3885398344606689213L;
                } else {
                    byte[] bArr = read;
                    if (bArr != null) {
                        int length = bArr.length;
                        byte[] bArr2 = new byte[length];
                        int i9 = 0;
                        while (i9 < length) {
                            try {
                                Object[] objArr4 = {Integer.valueOf(bArr[i9])};
                                Object method2 = onCameraWillChange.PlaybackStateCompat.get(-1076195355);
                                if (method2 == null) {
                                    Class cls2 = (Class) onCameraWillChange.read((char) ((ExpandableListView.getPackedPositionForChild(0, 0) > j2 ? 1 : (ExpandableListView.getPackedPositionForChild(0, 0) == j2 ? 0 : -1)) + 58402), 1371 - (Process.myPid() >> 22), TextUtils.getOffsetAfter("", 0) + 19);
                                    byte b4 = (byte) 0;
                                    byte b5 = (byte) (b4 - 1);
                                    Object[] objArr5 = new Object[1];
                                    d(b4, b5, (byte) (b5 + 3), objArr5);
                                    method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE);
                                    onCameraWillChange.PlaybackStateCompat.put(-1076195355, method2);
                                }
                                bArr2[i9] = ((Byte) ((Method) method2).invoke(null, objArr4)).byteValue();
                                i9++;
                                j2 = 0;
                            } catch (Throwable th) {
                                Throwable cause = th.getCause();
                                if (cause == null) {
                                    throw th;
                                }
                                throw cause;
                            }
                        }
                        int i10 = $11 + 115;
                        $10 = i10 % 128;
                        i5 = 2;
                        int i11 = i10 % 2;
                        bArr = bArr2;
                    } else {
                        i5 = 2;
                    }
                    if (bArr != null) {
                        byte[] bArr3 = read;
                        Object[] objArr6 = new Object[i5];
                        objArr6[1] = Integer.valueOf(RemoteActionCompatParcelizer);
                        objArr6[0] = Integer.valueOf(i3);
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(-30937109);
                        if (method3 == null) {
                            Class cls3 = (Class) onCameraWillChange.read((char) TextUtils.indexOf("", "", 0), (ViewConfiguration.getWindowTouchSlop() >> 8) + 543, TextUtils.indexOf("", "", 0) + 35);
                            byte b6 = (byte) 0;
                            byte b7 = (byte) (b6 - 1);
                            Object[] objArr7 = new Object[1];
                            d(b6, b7, (byte) (-b7), objArr7);
                            method3 = cls3.getMethod((String) objArr7[0], Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-30937109, method3);
                        }
                        iIntValue = (byte) (((byte) (bArr3[((Integer) ((Method) method3).invoke(null, objArr6)).intValue()] ^ 3885398344606689213L)) + ((int) (asInterface ^ 3885398344606689213L)));
                        int i12 = $11 + 85;
                        $10 = i12 % 128;
                        int i13 = i12 % 2;
                        j = 3885398344606689213L;
                    } else {
                        j = 3885398344606689213L;
                        iIntValue = (short) (((short) (onTransact[i3 + ((int) (RemoteActionCompatParcelizer ^ 3885398344606689213L))] ^ 3885398344606689213L)) + ((int) (asInterface ^ 3885398344606689213L)));
                    }
                }
                if (iIntValue > 0) {
                    addonwillstartrenderingmaplistener.asBinder = ((i3 + iIntValue) - 2) + ((int) (RemoteActionCompatParcelizer ^ j)) + i4;
                    Object[] objArr8 = {addonwillstartrenderingmaplistener, Integer.valueOf(i2), Integer.valueOf(asBinder), sb};
                    Object method4 = onCameraWillChange.PlaybackStateCompat.get(-1912037534);
                    if (method4 == null) {
                        method4 = ((Class) onCameraWillChange.read((char) (PointF.length(0.0f, 0.0f) > 0.0f ? 1 : (PointF.length(0.0f, 0.0f) == 0.0f ? 0 : -1)), 2390 - TextUtils.indexOf("", ""), (ViewConfiguration.getKeyRepeatDelay() >> 16) + 21)).getMethod("j", Object.class, Integer.TYPE, Integer.TYPE, Object.class);
                        onCameraWillChange.PlaybackStateCompat.put(-1912037534, method4);
                    }
                    ((StringBuilder) ((Method) method4).invoke(null, objArr8)).append(addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer);
                    addonwillstartrenderingmaplistener.onTransact = addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer;
                    byte[] bArr4 = read;
                    if (bArr4 != null) {
                        int length2 = bArr4.length;
                        byte[] bArr5 = new byte[length2];
                        for (int i14 = 0; i14 < length2; i14++) {
                            bArr5[i14] = (byte) (bArr4[i14] ^ 3885398344606689213L);
                        }
                        bArr4 = bArr5;
                    }
                    boolean z = bArr4 != null;
                    addonwillstartrenderingmaplistener.read = 1;
                    while (addonwillstartrenderingmaplistener.read < iIntValue) {
                        if (z) {
                            int i15 = $11 + 97;
                            $10 = i15 % 128;
                            int i16 = i15 % 2;
                            byte[] bArr6 = read;
                            addonwillstartrenderingmaplistener.asBinder = addonwillstartrenderingmaplistener.asBinder - 1;
                            addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer = (char) (addonwillstartrenderingmaplistener.onTransact + (((byte) (((byte) (bArr6[r8] ^ 3885398344606689213L)) + s)) ^ b));
                        } else {
                            short[] sArr = onTransact;
                            addonwillstartrenderingmaplistener.asBinder = addonwillstartrenderingmaplistener.asBinder - 1;
                            addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer = (char) (addonwillstartrenderingmaplistener.onTransact + (((short) (((short) (sArr[r8] ^ 3885398344606689213L)) + s)) ^ b));
                        }
                        sb.append(addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer);
                        addonwillstartrenderingmaplistener.onTransact = addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer;
                        addonwillstartrenderingmaplistener.read++;
                    }
                }
                objArr[0] = sb.toString();
            } catch (Throwable th2) {
                Throwable cause2 = th2.getCause();
                if (cause2 == null) {
                    throw th2;
                }
                throw cause2;
            }
        }

        /* JADX WARN: Removed duplicated region for block: B:35:0x014e  */
        /* JADX WARN: Removed duplicated region for block: B:36:0x0164  */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void b(int r25, char[] r26, byte r27, java.lang.Object[] r28) throws java.lang.Throwable {
            /*
                Method dump skipped, instructions count: 922
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass12.b(int, char[], byte, java.lang.Object[]):void");
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0027  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001f  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0027 -> B:11:0x002f). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void c(byte r6, int r7, byte r8, java.lang.Object[] r9) {
            /*
                int r6 = r6 * 2
                int r6 = 97 - r6
                int r8 = r8 * 2
                int r0 = 8 - r8
                int r7 = r7 * 4
                int r7 = 4 - r7
                byte[] r1 = o.projectedMetersForLatLng.AnonymousClass12.$$a
                byte[] r0 = new byte[r0]
                int r8 = 7 - r8
                r2 = 0
                if (r1 != 0) goto L19
                r3 = r7
                r6 = r8
                r4 = r2
                goto L2f
            L19:
                r3 = r2
            L1a:
                byte r4 = (byte) r6
                r0[r3] = r4
                if (r3 != r8) goto L27
                java.lang.String r6 = new java.lang.String
                r6.<init>(r0, r2)
                r9[r2] = r6
                return
            L27:
                int r3 = r3 + 1
                r4 = r1[r7]
                r5 = r3
                r3 = r7
                r7 = r4
                r4 = r5
            L2f:
                int r7 = -r7
                int r6 = r6 + r7
                int r6 = r6 + (-5)
                int r7 = r3 + 1
                r3 = r4
                goto L1a
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass12.c(byte, int, byte, java.lang.Object[]):void");
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0025  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001d  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0025 -> B:11:0x002b). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void d(byte r7, int r8, int r9, java.lang.Object[] r10) {
            /*
                int r7 = r7 * 2
                int r7 = r7 + 1
                int r9 = 101 - r9
                int r8 = r8 + 4
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass12.$$d
                byte[] r1 = new byte[r7]
                r2 = 0
                if (r0 != 0) goto L13
                r3 = r9
                r4 = r2
                r9 = r8
                goto L2b
            L13:
                r3 = r2
            L14:
                int r4 = r3 + 1
                byte r5 = (byte) r9
                r1[r3] = r5
                int r8 = r8 + 1
                if (r4 != r7) goto L25
                java.lang.String r7 = new java.lang.String
                r7.<init>(r1, r2)
                r10[r2] = r7
                return
            L25:
                r3 = r0[r8]
                r6 = r9
                r9 = r8
                r8 = r3
                r3 = r6
            L2b:
                int r8 = r8 + r3
                r3 = r4
                r6 = r9
                r9 = r8
                r8 = r6
                goto L14
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass12.d(byte, int, int, java.lang.Object[]):void");
        }

        /*  JADX ERROR: NoSuchElementException in pass: ReplaceNewArray
            java.util.NoSuchElementException
                at java.base/java.util.TreeMap.key(TreeMap.java:1637)
                at java.base/java.util.TreeMap.lastKey(TreeMap.java:309)
                at jadx.core.dex.visitors.ReplaceNewArray.processNewArray(ReplaceNewArray.java:171)
                at jadx.core.dex.visitors.ReplaceNewArray.processInsn(ReplaceNewArray.java:72)
                at jadx.core.dex.visitors.ReplaceNewArray.visit(ReplaceNewArray.java:53)
            */
        public static java.lang.Object[] read(android.content.Context r33, int r34, int r35) {
            /*
                Method dump skipped, instructions count: 4095
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass12.read(android.content.Context, int, int):java.lang.Object[]");
        }
    };
    public static Map<String, Object> RatingCompat = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.11
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/GetEventList");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.11.5
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaControllerCompatMediaControllerImplApi21ExtraBinderRequestResultReceiver = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.13
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/GetEventGroups");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.13.5
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                    put("EventId", "request:eventId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaMetadataCompat = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.18
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/GetEventLuckyDrawList");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.18.5
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                    put("GroupId", "request:groupId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setTitle = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.16
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/GetPointMultiplier");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.16.5
                {
                    put("GroupId", "request:groupId:required");
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> write = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.17
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/EnrollLuckyDrawTicket");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.17.3
                private static final byte[] $$d = {35, -39, -38, 29};
                private static final int $$e = 102;
                private static int $10 = 0;
                private static int $11 = 1;
                private static final byte[] $$a = {75, -71, -122, 28, -23, 44, -44, -10, 5, -6, -18, -4, 21, -35, MqttWireMessage.MESSAGE_TYPE_PINGREQ, -18, -10, MqttWireMessage.MESSAGE_TYPE_PINGRESP, -7, -22, -8, 2, 8, -1, -8, -23, 37, -42, -11, 10, -18, 7, 0, -7, -7, 0};
                private static final int $$b = 162;
                private static int RemoteActionCompatParcelizer = 0;
                private static int AudioAttributesCompatParcelizer = 1;
                private static long onTransact = -1864964313293061584L;
                private static int read = -1956445648;
                private static char asBinder = 22938;

                {
                    Object[] objArr = new Object[1];
                    a(new char[]{11783, 6639, 39596, 37446}, new char[]{0, 0, 0, 0}, (-1407586515) + (AudioTrack.getMaxVolume() > 0.0f ? 1 : (AudioTrack.getMaxVolume() == 0.0f ? 0 : -1)), (char) (18074 - View.resolveSize(0, 0)), new char[]{28500, 40596, 4100, 571, 64724, 13383, 9995, 3108, 19548, 27002, 28216, 30032, 15085}, objArr);
                    put((String) objArr[0], "user:authorization:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }

                private static void a(char[] cArr, char[] cArr2, int i, char c, char[] cArr3, Object[] objArr) throws Throwable {
                    int i2 = 2;
                    int i3 = 2 % 2;
                    addOnDidFinishLoadingStyleListener addondidfinishloadingstylelistener = new addOnDidFinishLoadingStyleListener();
                    int length = cArr.length;
                    char[] cArr4 = new char[length];
                    int length2 = cArr2.length;
                    char[] cArr5 = new char[length2];
                    System.arraycopy(cArr, 0, cArr4, 0, length);
                    System.arraycopy(cArr2, 0, cArr5, 0, length2);
                    cArr4[0] = (char) (cArr4[0] ^ c);
                    cArr5[2] = (char) (cArr5[2] + ((char) i));
                    int length3 = cArr3.length;
                    char[] cArr6 = new char[length3];
                    addondidfinishloadingstylelistener.asInterface = 0;
                    while (addondidfinishloadingstylelistener.asInterface < length3) {
                        int i4 = $11 + 63;
                        $10 = i4 % 128;
                        int i5 = i4 % i2;
                        try {
                            Object[] objArr2 = {addondidfinishloadingstylelistener};
                            Object method = onCameraWillChange.PlaybackStateCompat.get(662089593);
                            if (method == null) {
                                Class cls = (Class) onCameraWillChange.read((char) Color.red(0), (AudioTrack.getMinVolume() > 0.0f ? 1 : (AudioTrack.getMinVolume() == 0.0f ? 0 : -1)) + 1442, (ViewConfiguration.getScrollFriction() > 0.0f ? 1 : (ViewConfiguration.getScrollFriction() == 0.0f ? 0 : -1)) + 19);
                                byte b = (byte) 0;
                                byte b2 = (byte) (b + 1);
                                Object[] objArr3 = new Object[1];
                                c(b, b2, (byte) (b2 - 1), objArr3);
                                method = cls.getMethod((String) objArr3[0], Object.class);
                                onCameraWillChange.PlaybackStateCompat.put(662089593, method);
                            }
                            int iIntValue = ((Integer) ((Method) method).invoke(null, objArr2)).intValue();
                            try {
                                Object[] objArr4 = {addondidfinishloadingstylelistener};
                                Object method2 = onCameraWillChange.PlaybackStateCompat.get(-105134515);
                                if (method2 == null) {
                                    Class cls2 = (Class) onCameraWillChange.read((char) (ViewConfiguration.getMaximumFlingVelocity() >> 16), View.MeasureSpec.getSize(0) + 543, 35 - Color.green(0));
                                    byte b3 = (byte) 0;
                                    byte b4 = b3;
                                    Object[] objArr5 = new Object[1];
                                    c(b3, b4, b4, objArr5);
                                    method2 = cls2.getMethod((String) objArr5[0], Object.class);
                                    onCameraWillChange.PlaybackStateCompat.put(-105134515, method2);
                                }
                                int iIntValue2 = ((Integer) ((Method) method2).invoke(null, objArr4)).intValue();
                                try {
                                    Object[] objArr6 = {addondidfinishloadingstylelistener, Integer.valueOf(cArr4[addondidfinishloadingstylelistener.asInterface % 4] * 32718), Integer.valueOf(cArr5[iIntValue])};
                                    Object method3 = onCameraWillChange.PlaybackStateCompat.get(-576167559);
                                    if (method3 == null) {
                                        method3 = ((Class) onCameraWillChange.read((char) (20854 - (ViewConfiguration.getTouchSlop() >> 8)), Color.green(0) + 100, TextUtils.lastIndexOf("", '0', 0, 0) + 18)).getMethod("u", Object.class, Integer.TYPE, Integer.TYPE);
                                        onCameraWillChange.PlaybackStateCompat.put(-576167559, method3);
                                    }
                                    ((Method) method3).invoke(null, objArr6);
                                    try {
                                        Object[] objArr7 = {Integer.valueOf(cArr4[iIntValue2] * 32718), Integer.valueOf(cArr5[iIntValue])};
                                        Object method4 = onCameraWillChange.PlaybackStateCompat.get(1229688017);
                                        if (method4 == null) {
                                            method4 = ((Class) onCameraWillChange.read((char) (60060 - View.resolveSize(0, 0)), 78 - ImageFormat.getBitsPerPixel(0), 21 - ((Process.getThreadPriority(0) + 20) >> 6))).getMethod("z", Integer.TYPE, Integer.TYPE);
                                            onCameraWillChange.PlaybackStateCompat.put(1229688017, method4);
                                        }
                                        cArr5[iIntValue2] = ((Character) ((Method) method4).invoke(null, objArr7)).charValue();
                                        cArr4[iIntValue2] = addondidfinishloadingstylelistener.read;
                                        cArr6[addondidfinishloadingstylelistener.asInterface] = (char) ((((cArr4[iIntValue2] ^ cArr3[addondidfinishloadingstylelistener.asInterface]) ^ (onTransact ^ (-1864964313293061584L))) ^ ((int) (read ^ (-1864964313293061584L)))) ^ ((char) (asBinder ^ (-1864964313293061584L))));
                                        addondidfinishloadingstylelistener.asInterface++;
                                        int i6 = $10 + 53;
                                        $11 = i6 % 128;
                                        int i7 = i6 % 2;
                                        i2 = 2;
                                    } catch (Throwable th) {
                                        Throwable cause = th.getCause();
                                        if (cause == null) {
                                            throw th;
                                        }
                                        throw cause;
                                    }
                                } catch (Throwable th2) {
                                    Throwable cause2 = th2.getCause();
                                    if (cause2 == null) {
                                        throw th2;
                                    }
                                    throw cause2;
                                }
                            } catch (Throwable th3) {
                                Throwable cause3 = th3.getCause();
                                if (cause3 == null) {
                                    throw th3;
                                }
                                throw cause3;
                            }
                        } catch (Throwable th4) {
                            Throwable cause4 = th4.getCause();
                            if (cause4 == null) {
                                throw th4;
                            }
                            throw cause4;
                        }
                    }
                    objArr[0] = new String(cArr6);
                }

                /*  JADX ERROR: NoSuchElementException in pass: ReplaceNewArray
                    java.util.NoSuchElementException
                        at java.base/java.util.TreeMap.key(TreeMap.java:1637)
                        at java.base/java.util.TreeMap.lastKey(TreeMap.java:309)
                        at jadx.core.dex.visitors.ReplaceNewArray.processNewArray(ReplaceNewArray.java:171)
                        at jadx.core.dex.visitors.ReplaceNewArray.processInsn(ReplaceNewArray.java:72)
                        at jadx.core.dex.visitors.ReplaceNewArray.visit(ReplaceNewArray.java:53)
                    */
                public static java.lang.Object[] asInterface(android.content.Context r30, int r31, int r32) {
                    /*
                        Method dump skipped, instructions count: 3724
                        To view this dump add '--comments-level debug' option
                    */
                    throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass17.AnonymousClass3.asInterface(android.content.Context, int, int):java.lang.Object[]");
                }

                private static void b(int i, int i2, byte b, Object[] objArr) {
                    int i3 = 114 - i;
                    byte[] bArr = $$a;
                    int i4 = b + 4;
                    byte[] bArr2 = new byte[11 - i2];
                    int i5 = 10 - i2;
                    int i6 = -1;
                    if (bArr == null) {
                        i4++;
                        i3 = (i3 + (-i4)) - 5;
                    }
                    while (true) {
                        i6++;
                        bArr2[i6] = (byte) i3;
                        if (i6 == i5) {
                            objArr[0] = new String(bArr2, 0);
                            return;
                        } else {
                            byte b2 = bArr[i4];
                            i4++;
                            i3 = (i3 + (-b2)) - 5;
                        }
                    }
                }

                /* JADX WARN: Removed duplicated region for block: B:10:0x0024  */
                /* JADX WARN: Removed duplicated region for block: B:8:0x001c  */
                /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0024 -> B:11:0x002f). Please report as a decompilation issue!!! */
                /*
                    Code decompiled incorrectly, please refer to instructions dump.
                    To view partially-correct add '--show-bad-code' argument
                */
                private static void c(int r6, byte r7, short r8, java.lang.Object[] r9) {
                    /*
                        int r7 = r7 * 2
                        int r7 = r7 + 118
                        byte[] r0 = o.projectedMetersForLatLng.AnonymousClass17.AnonymousClass3.$$d
                        int r8 = r8 * 2
                        int r8 = 3 - r8
                        int r6 = r6 * 4
                        int r1 = r6 + 1
                        byte[] r1 = new byte[r1]
                        r2 = 0
                        if (r0 != 0) goto L16
                        r3 = r8
                        r4 = r2
                        goto L2f
                    L16:
                        r3 = r2
                    L17:
                        byte r4 = (byte) r7
                        r1[r3] = r4
                        if (r3 != r6) goto L24
                        java.lang.String r6 = new java.lang.String
                        r6.<init>(r1, r2)
                        r9[r2] = r6
                        return
                    L24:
                        int r8 = r8 + 1
                        int r3 = r3 + 1
                        r4 = r0[r8]
                        r5 = r8
                        r8 = r7
                        r7 = r4
                        r4 = r3
                        r3 = r5
                    L2f:
                        int r7 = r7 + r8
                        r8 = r3
                        r3 = r4
                        goto L17
                    */
                    throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass17.AnonymousClass3.c(int, byte, short, java.lang.Object[]):void");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.17.4
                {
                    put("EhostSessionId", "user:sessionId:required");
                    put("LuckyDrawId", "request:luckyDrawId:required");
                    put("PlayerId", "user:playerId:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaBrowserCompatCustomActionResultReceiver = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.20
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAvailableVoucherListForATLPromotion");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.20.4
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PromotionId", "request:promotionId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setCheckable = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.19
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/GetTournamentQualificationInfo");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.19.5
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("GroupId", "request:groupId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setItemInvoker = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.24
        {
            put("url", "https://mobileapp-gaming.mgm.mo/api/mlifeAppGaming/v1.0/Patrons/GetTournamentRankingInfo");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.24.4
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("GroupId", "request:groupId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setForceShowIcon = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.21
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/RedeemATLOffer");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.21.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.21.5
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("OfferId", "request:offerId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setGroupDividerEnabled = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.22
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/RedeemATLOffer");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.22.5
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.22.3
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("OfferId", "request:offerId:required");
                    put("PropertyId", "request:propertyId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setIcon = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.23
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/Logout");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.23.3
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.23.4
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId");
                }
            });
        }
    };
    public static Map<String, Object> setBackgroundResource = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.29
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetTermsAndConditions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.29.2
                {
                    put("Authorization", "user:authorization:required");
                    put("Type", "request:type:required");
                }
            });
            put("remark", "terms");
        }
    };
    public static Map<String, Object> setView = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.30
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetTermsAndConditions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.30.3
                {
                    put("Authorization", "user:authorization:required");
                    put("Type", "request:type:required");
                }
            });
            put("remark", "privacy");
        }
    };
    public static Map<String, Object> ComponentActivity3 = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.26
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetBackgroundImage");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.26.2
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingNumber", "user:ranking");
                }
            });
        }
    };
    public static Map<String, Object> setContentHeight = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.27
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/PopUpPromotions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.27.2
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingNumber", "user:ranking");
                }
            });
        }
    };
    public static Map<String, Object> AudioAttributesCompatParcelizer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.28
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/BannerList");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.28.2
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingNumber", "user:ranking");
                    put("BannerType", "request:bannerType:required");
                }
            });
        }
    };
    public static Map<String, Object> setShortcut = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.32
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/PromotionsDetail");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.32.1
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingNumber", "user:ranking");
                    put("PromotionID", "request:promotionId:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaBrowserCompatItemReceiver = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.35
        private static final byte[] $$d = {45, -22, 60, -58};
        private static final int $$e = 140;
        private static int $10 = 0;
        private static int $11 = 1;
        private static final byte[] $$a = {28, -35, -12, -100, 23, -44, 44, 10, -5, 6, 18};
        private static final int $$b = 22;
        private static int asBinder = 0;
        private static int read = 1;
        private static char[] RemoteActionCompatParcelizer = {30296, 30343, 30461, 30461, 30460, 30357, 30352, 30460, 30340, 30460, 30453, 30463, 30462, 30454, 30357, 30361, 30461, 30452, 30462, 30365, 30357, 30358, 30386, 30384, 30385, 30373, 30374, 30386, 30384, 30368, 30339, 30463, 30461, 30456, 30342, 30460, 30456, 30342, 30217, 30299, 30302, 30303, 30301, 30303, 30304, 30318, 30302, 30288, 30303, 30303, 30293, 30299, 30217, 30302, 30288, 30290, 30281, 30293, 30303, 30320, 30321, 30288, 30295, 30280, 30293, 30288, 30280, 30312, 30326, 30295, 30324, 30214, 30305, 30299, 30302, 30303, 30301, 30303, 30304, 30318, 30302, 30302, 30301, 30303, 30290, 30222, 30291, 30291, 30306, 30318, 30303, 30301, 30303, 30302, 30299, 30305, 30299, 30293, 30303, 30213, 30292, 30288, 30283, 30304, 30314, 30293, 30287, 30308, 30305, 30280, 30219, 30293, 30291, 30299, 30303, 30302, 30302, 30295, 30282, 30290, 30317, 30317, 30293, 30291, 30288, 30290, 30288, 30288, 30303, 30219, 30293, 30291, 30299, 30303, 30302, 30302, 30295, 30282, 30290, 30317, 30215, 30221, 30219, 30335, 30330, 30312, 30282, 30290, 30301, 30321, 30314, 30287, 30295, 30292, 30282, 30293, 30301, 30293, 30313, 30334, 30290, 30290, 30300};
        private static int asInterface = 346264830;

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAvailablePromotions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.35.2
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("RankingNumber", "user:ranking");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0026  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001e  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0026 -> B:11:0x0028). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void a(short r6, byte r7, int r8, java.lang.Object[] r9) {
            /*
                int r6 = r6 * 3
                int r6 = 8 - r6
                int r8 = r8 * 4
                int r8 = 97 - r8
                int r7 = r7 * 3
                int r7 = 4 - r7
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass35.$$a
                byte[] r1 = new byte[r6]
                r2 = 0
                if (r0 != 0) goto L16
                r3 = r6
                r4 = r2
                goto L28
            L16:
                r3 = r2
            L17:
                int r4 = r3 + 1
                byte r5 = (byte) r8
                r1[r3] = r5
                if (r4 != r6) goto L26
                java.lang.String r6 = new java.lang.String
                r6.<init>(r1, r2)
                r9[r2] = r6
                return
            L26:
                r3 = r0[r7]
            L28:
                int r7 = r7 + 1
                int r8 = r8 + r3
                int r8 = r8 + (-5)
                r3 = r4
                goto L17
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass35.a(short, byte, int, java.lang.Object[]):void");
        }

        private static void b(byte[] bArr, int[] iArr, boolean z, Object[] objArr) throws Throwable {
            int i;
            int length;
            char[] cArr;
            int i2;
            int i3 = 2 % 2;
            addOnDidBecomeIdleListener addondidbecomeidlelistener = new addOnDidBecomeIdleListener();
            int i4 = 0;
            int i5 = iArr[0];
            int i6 = iArr[1];
            int i7 = iArr[2];
            int i8 = iArr[3];
            char[] cArr2 = RemoteActionCompatParcelizer;
            if (cArr2 != null) {
                int i9 = $11 + 3;
                $10 = i9 % 128;
                if (i9 % 2 != 0) {
                    length = cArr2.length;
                    cArr = new char[length];
                } else {
                    length = cArr2.length;
                    cArr = new char[length];
                }
                int i10 = 0;
                while (i10 < length) {
                    try {
                        Object[] objArr2 = new Object[1];
                        objArr2[i4] = Integer.valueOf(cArr2[i10]);
                        Object method = onCameraWillChange.PlaybackStateCompat.get(-1605641787);
                        if (method != null) {
                            i2 = length;
                        } else {
                            Class cls = (Class) onCameraWillChange.read((char) (TextUtils.indexOf("", "", i4, i4) + 37361), TextUtils.indexOf("", "", i4) + 1300, (SystemClock.elapsedRealtimeNanos() > 0L ? 1 : (SystemClock.elapsedRealtimeNanos() == 0L ? 0 : -1)) + 11);
                            byte b = (byte) 5;
                            byte b2 = (byte) (b - 5);
                            i2 = length;
                            Object[] objArr3 = new Object[1];
                            d(b, b2, b2, objArr3);
                            method = cls.getMethod((String) objArr3[0], Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-1605641787, method);
                        }
                        cArr[i10] = ((Character) ((Method) method).invoke(null, objArr2)).charValue();
                        i10++;
                        length = i2;
                        i4 = 0;
                    } catch (Throwable th) {
                        Throwable cause = th.getCause();
                        if (cause == null) {
                            throw th;
                        }
                        throw cause;
                    }
                }
                cArr2 = cArr;
            }
            char[] cArr3 = new char[i6];
            System.arraycopy(cArr2, i5, cArr3, 0, i6);
            if (bArr != null) {
                char[] cArr4 = new char[i6];
                addondidbecomeidlelistener.onTransact = 0;
                char c = 0;
                while (addondidbecomeidlelistener.onTransact < i6) {
                    int i11 = $10 + 79;
                    $11 = i11 % 128;
                    if (i11 % 2 != 0 ? bArr[addondidbecomeidlelistener.onTransact] != 1 : bArr[addondidbecomeidlelistener.onTransact] != 0) {
                        int i12 = addondidbecomeidlelistener.onTransact;
                        Object[] objArr4 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                        Object method2 = onCameraWillChange.PlaybackStateCompat.get(613310274);
                        if (method2 == null) {
                            Class cls2 = (Class) onCameraWillChange.read((char) Color.red(0), 1287 - TextUtils.indexOf((CharSequence) "", '0'), 12 - KeyEvent.normalizeMetaState(0));
                            byte b3 = (byte) 0;
                            byte b4 = b3;
                            Object[] objArr5 = new Object[1];
                            d(b3, b4, b4, objArr5);
                            method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(613310274, method2);
                        }
                        cArr4[i12] = ((Character) ((Method) method2).invoke(null, objArr4)).charValue();
                        int i13 = $10 + 115;
                        $11 = i13 % 128;
                        int i14 = i13 % 2;
                    } else {
                        int i15 = addondidbecomeidlelistener.onTransact;
                        Object[] objArr6 = {Integer.valueOf(cArr3[addondidbecomeidlelistener.onTransact]), Integer.valueOf(c)};
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(-2027528084);
                        if (method3 == null) {
                            Class cls3 = (Class) onCameraWillChange.read((char) ((ViewConfiguration.getEdgeSlop() >> 16) + 58526), 230 - (ViewConfiguration.getMaximumDrawingCacheSize() >> 24), 25 - (ViewConfiguration.getDoubleTapTimeout() >> 16));
                            byte b5 = (byte) 0;
                            Object[] objArr7 = new Object[1];
                            d((byte) 9, b5, b5, objArr7);
                            method3 = cls3.getMethod((String) objArr7[0], Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-2027528084, method3);
                        }
                        cArr4[i15] = ((Character) ((Method) method3).invoke(null, objArr6)).charValue();
                    }
                    c = cArr4[addondidbecomeidlelistener.onTransact];
                    Object[] objArr8 = {addondidbecomeidlelistener, addondidbecomeidlelistener};
                    Object method4 = onCameraWillChange.PlaybackStateCompat.get(207891030);
                    if (method4 == null) {
                        Class cls4 = (Class) onCameraWillChange.read((char) (KeyEvent.normalizeMetaState(0) + 38149), 1874 - Color.blue(0), Gravity.getAbsoluteGravity(0, 0) + 23);
                        byte b6 = (byte) 2;
                        byte b7 = (byte) (b6 - 2);
                        Object[] objArr9 = new Object[1];
                        d(b6, b7, b7, objArr9);
                        method4 = cls4.getMethod((String) objArr9[0], Object.class, Object.class);
                        onCameraWillChange.PlaybackStateCompat.put(207891030, method4);
                    }
                    ((Method) method4).invoke(null, objArr8);
                }
                cArr3 = cArr4;
            }
            if (i8 > 0) {
                char[] cArr5 = new char[i6];
                i = 0;
                System.arraycopy(cArr3, 0, cArr5, 0, i6);
                int i16 = i6 - i8;
                System.arraycopy(cArr5, 0, cArr3, i16, i8);
                System.arraycopy(cArr5, i8, cArr3, 0, i16);
            } else {
                i = 0;
            }
            if (z) {
                char[] cArr6 = new char[i6];
                while (true) {
                    addondidbecomeidlelistener.onTransact = i;
                    if (addondidbecomeidlelistener.onTransact >= i6) {
                        break;
                    }
                    cArr6[addondidbecomeidlelistener.onTransact] = cArr3[(i6 - addondidbecomeidlelistener.onTransact) - 1];
                    i = addondidbecomeidlelistener.onTransact + 1;
                }
                cArr3 = cArr6;
            }
            if (i7 > 0) {
                int i17 = 0;
                while (true) {
                    addondidbecomeidlelistener.onTransact = i17;
                    if (addondidbecomeidlelistener.onTransact >= i6) {
                        break;
                    }
                    cArr3[addondidbecomeidlelistener.onTransact] = (char) (cArr3[addondidbecomeidlelistener.onTransact] - iArr[2]);
                    i17 = addondidbecomeidlelistener.onTransact + 1;
                }
            }
            objArr[0] = new String(cArr3);
        }

        private static void c(int i, boolean z, int i2, int i3, char[] cArr, Object[] objArr) throws Throwable {
            int i4 = 2 % 2;
            addOnDidFinishLoadingMapListener addondidfinishloadingmaplistener = new addOnDidFinishLoadingMapListener();
            char[] cArr2 = new char[i];
            addondidfinishloadingmaplistener.read = 0;
            while (addondidfinishloadingmaplistener.read < i) {
                addondidfinishloadingmaplistener.asInterface = cArr[addondidfinishloadingmaplistener.read];
                cArr2[addondidfinishloadingmaplistener.read] = (char) (i3 + addondidfinishloadingmaplistener.asInterface);
                int i5 = addondidfinishloadingmaplistener.read;
                try {
                    Object[] objArr2 = {Integer.valueOf(cArr2[i5]), Integer.valueOf(asInterface)};
                    Object method = onCameraWillChange.PlaybackStateCompat.get(1794346129);
                    if (method == null) {
                        Class cls = (Class) onCameraWillChange.read((char) (ViewConfiguration.getWindowTouchSlop() >> 8), Color.alpha(0) + 1977, (Process.myPid() >> 22) + 27);
                        byte b = (byte) 0;
                        Object[] objArr3 = new Object[1];
                        d((byte) 6, b, b, objArr3);
                        method = cls.getMethod((String) objArr3[0], Integer.TYPE, Integer.TYPE);
                        onCameraWillChange.PlaybackStateCompat.put(1794346129, method);
                    }
                    cArr2[i5] = ((Character) ((Method) method).invoke(null, objArr2)).charValue();
                    try {
                        Object[] objArr4 = {addondidfinishloadingmaplistener, addondidfinishloadingmaplistener};
                        Object method2 = onCameraWillChange.PlaybackStateCompat.get(1725317227);
                        if (method2 == null) {
                            Class cls2 = (Class) onCameraWillChange.read((char) (ViewConfiguration.getScrollDefaultDelay() >> 16), (ViewConfiguration.getTapTimeout() >> 16) + 1570, (ViewConfiguration.getJumpTapTimeout() >> 16) + 23);
                            byte b2 = (byte) 0;
                            Object[] objArr5 = new Object[1];
                            d((byte) 7, b2, b2, objArr5);
                            method2 = cls2.getMethod((String) objArr5[0], Object.class, Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(1725317227, method2);
                        }
                        ((Method) method2).invoke(null, objArr4);
                    } catch (Throwable th) {
                        Throwable cause = th.getCause();
                        if (cause == null) {
                            throw th;
                        }
                        throw cause;
                    }
                } catch (Throwable th2) {
                    Throwable cause2 = th2.getCause();
                    if (cause2 == null) {
                        throw th2;
                    }
                    throw cause2;
                }
            }
            if (i2 > 0) {
                addondidfinishloadingmaplistener.RemoteActionCompatParcelizer = i2;
                char[] cArr3 = new char[i];
                System.arraycopy(cArr2, 0, cArr3, 0, i);
                System.arraycopy(cArr3, 0, cArr2, i - addondidfinishloadingmaplistener.RemoteActionCompatParcelizer, addondidfinishloadingmaplistener.RemoteActionCompatParcelizer);
                System.arraycopy(cArr3, addondidfinishloadingmaplistener.RemoteActionCompatParcelizer, cArr2, 0, i - addondidfinishloadingmaplistener.RemoteActionCompatParcelizer);
            }
            if (z) {
                char[] cArr4 = new char[i];
                addondidfinishloadingmaplistener.read = 0;
                while (addondidfinishloadingmaplistener.read < i) {
                    int i6 = $10 + 39;
                    $11 = i6 % 128;
                    int i7 = i6 % 2;
                    cArr4[addondidfinishloadingmaplistener.read] = cArr2[(i - addondidfinishloadingmaplistener.read) - 1];
                    try {
                        Object[] objArr6 = {addondidfinishloadingmaplistener, addondidfinishloadingmaplistener};
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(1725317227);
                        if (method3 == null) {
                            Class cls3 = (Class) onCameraWillChange.read((char) View.MeasureSpec.makeMeasureSpec(0, 0), 1570 - Color.green(0), 23 - TextUtils.indexOf("", "", 0, 0));
                            byte b3 = (byte) 0;
                            Object[] objArr7 = new Object[1];
                            d((byte) 7, b3, b3, objArr7);
                            method3 = cls3.getMethod((String) objArr7[0], Object.class, Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(1725317227, method3);
                        }
                        ((Method) method3).invoke(null, objArr6);
                    } catch (Throwable th3) {
                        Throwable cause3 = th3.getCause();
                        if (cause3 == null) {
                            throw th3;
                        }
                        throw cause3;
                    }
                }
                int i8 = $11 + 117;
                $10 = i8 % 128;
                int i9 = i8 % 2;
                cArr2 = cArr4;
            }
            String str = new String(cArr2);
            int i10 = $11 + 85;
            $10 = i10 % 128;
            if (i10 % 2 == 0) {
                objArr[0] = str;
            } else {
                Object obj = null;
                obj.hashCode();
                throw null;
            }
        }

        private static void d(int i, int i2, int i3, Object[] objArr) {
            int i4 = i3 * 2;
            int i5 = 4 - (i2 * 2);
            byte[] bArr = $$d;
            int i6 = 121 - i;
            byte[] bArr2 = new byte[1 - i4];
            int i7 = 0 - i4;
            int i8 = -1;
            if (bArr == null) {
                i5++;
                i6 += i5;
            }
            while (true) {
                i8++;
                bArr2[i8] = (byte) i6;
                if (i8 == i7) {
                    objArr[0] = new String(bArr2, 0);
                    return;
                } else {
                    byte b = bArr[i5];
                    i5++;
                    i6 += b;
                }
            }
        }

        public static Object[] onTransact(Context context, int i, int i2) throws Throwable {
            Object objNewInstance;
            int i3;
            int i4;
            boolean z;
            int i5;
            Class<?> cls;
            int i6;
            int i7;
            int i8;
            int i9;
            Object objInvoke;
            int i10;
            int i11;
            Object obj;
            Class<?> cls2;
            int iIndexOf;
            int i12;
            int i13;
            int i14 = 2 % 2;
            int i15 = 1;
            try {
                if (context == null) {
                    Object[] objArr = {new int[]{i}, new int[]{i}, null, new int[1]};
                    int i16 = ~i;
                    Object[] objArr2 = {Integer.valueOf(i2), 0, Integer.valueOf(1709148652 + ((36968584 | i16) * (-192)) + (((~(49766348 | i16)) | 956309553) * (-384)) + (((~(i | (-12797765))) | (~(i16 | 1006075901)) | (~((-956309554) | i))) * 192))};
                    Object method = onCameraWillChange.PlaybackStateCompat.get(-554193431);
                    if (method == null) {
                        Class cls3 = (Class) onCameraWillChange.read((char) (TextUtils.lastIndexOf("", '0', 0) + 1), 1715 - (ViewConfiguration.getKeyRepeatTimeout() >> 16), 23 - ((byte) KeyEvent.getModifierMetaStateMask()));
                        byte b = (byte) 0;
                        byte b2 = b;
                        Object[] objArr3 = new Object[1];
                        a(b, b2, b2, objArr3);
                        method = cls3.getMethod((String) objArr3[0], Integer.TYPE, Integer.TYPE, Integer.TYPE);
                        onCameraWillChange.PlaybackStateCompat.put(-554193431, method);
                    }
                    ((int[]) objArr[3])[0] = ((Integer) ((Method) method).invoke(null, objArr2)).intValue();
                    int i17 = asBinder + 77;
                    read = i17 % 128;
                    if (i17 % 2 != 0) {
                        return objArr;
                    }
                    throw null;
                }
                try {
                    Object[] objArr4 = new Object[1];
                    b(new byte[]{1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 1, 1, 1}, new int[]{0, 38, 89, 0}, false, objArr4);
                    Object[] objArr5 = (Object[]) Array.newInstance(Class.forName((String) objArr4[0]), 2);
                    int i18 = -(ViewConfiguration.getJumpTapTimeout() >> 16);
                    int i19 = i18 * (-963);
                    int i20 = (((i19 | (-964)) << 1) - (i19 ^ (-964))) + 29915;
                    int i21 = ~i18;
                    int i22 = ~(((-32) ^ i) | ((-32) & i));
                    int i23 = (i20 - (~(-(-(((i21 ^ i22) | (i21 & i22)) * (-964)))))) - 1;
                    int i24 = ~i;
                    int i25 = ~((-32) | i24);
                    int i26 = ~(((-32) ^ i18) | (i18 & (-32)));
                    int i27 = ((i25 & i26) | (i25 ^ i26)) * (-964);
                    int i28 = (i23 & i27) + (i27 | i23);
                    int i29 = (ViewConfiguration.getScrollFriction() > 0.0f ? 1 : (ViewConfiguration.getScrollFriction() == 0.0f ? 0 : -1));
                    int i30 = i29 * (-813);
                    int i31 = ~((-11) | i29);
                    int i32 = ~((i29 ^ i) | (i29 & i));
                    int i33 = (((i30 | 4080) << 1) - (i30 ^ 4080)) + (((i31 ^ i32) | (i31 & i32)) * (-814));
                    int i34 = ~(((-11) ^ i24) | ((-11) & i24));
                    int i35 = ~i29;
                    int i36 = ~((i35 ^ 10) | (i35 & 10));
                    int i37 = (i34 ^ i36) | (i36 & i34);
                    int i38 = ((i32 & i37) | (i37 ^ i32)) * 407;
                    int i39 = (i33 & i38) + (i38 | i33);
                    int i40 = (~((i35 & i) | (i35 ^ i))) | (~((i35 ^ 10) | (i35 & 10)));
                    int i41 = ~((i ^ 10) | (i & 10));
                    int i42 = i39 + (((i40 & i41) | (i40 ^ i41)) * 407);
                    int i43 = -Color.rgb(0, 0, 0);
                    int i44 = ((i43 * (-419)) - (-1526818434)) + ((~(i | (-16776998))) * 420);
                    int i45 = ~i43;
                    int i46 = -(-(((i45 ^ (-16776998)) | (i45 & (-16776998))) * (-420)));
                    int i47 = ((i44 | i46) << 1) - (i44 ^ i46);
                    int i48 = ~(i45 | 16776997);
                    int i49 = ~i;
                    int i50 = i48 ^ (~(((-16776998) & i49) | (i49 ^ (-16776998))));
                    Object[] objArr6 = new Object[1];
                    c(i28, true, i42, (i47 - (~(-(-(((i48 & r12) | i50) * 420))))) - 1, new char[]{65483, 15, 20, 26, 29, 15, 25, 65516, 65512, 65529, 65518, 65534, 0, 65512, 65518, 65495, 15, 20, 26, 29, 15, 25, 65516, 65512, 65530, 65495, 18, ' ', '\r', 16, 65519}, objArr6);
                    String str = (String) objArr6[0];
                    int i51 = asBinder;
                    int i52 = ((i51 | 57) << 1) - (i51 ^ 57);
                    read = i52 % 128;
                    try {
                        if (i52 % 2 == 0) {
                            Object[] objArr7 = new Object[1];
                            b(new byte[]{1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 1, 1, 1}, new int[]{0, 38, 89, 0}, true, objArr7);
                            objNewInstance = Class.forName((String) objArr7[0]).getDeclaredConstructor(String.class).newInstance(str);
                        } else {
                            Object[] objArr8 = new Object[1];
                            b(new byte[]{1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 1, 1, 1}, new int[]{0, 38, 89, 0}, false, objArr8);
                            objNewInstance = Class.forName((String) objArr8[0]).getDeclaredConstructor(String.class).newInstance(str);
                        }
                        objArr5[0] = objNewInstance;
                        int i53 = -AndroidCharacter.getMirror('0');
                        int i54 = asBinder;
                        int i55 = ((i54 | 97) << 1) - (i54 ^ 97);
                        read = i55 % 128;
                        int i56 = i55 % 2;
                        int i57 = (i53 * (-721)) - 56959;
                        int i58 = ~i53;
                        int i59 = ~((i58 ^ (-80)) | (i58 & (-80)));
                        int i60 = (i49 ^ i59) | (i59 & i49);
                        int i61 = ~((i53 ^ 79) | (i53 & 79));
                        int i62 = -(-(((i60 ^ i61) | (i60 & i61)) * 1444));
                        int i63 = ((i57 | i62) << 1) - (i57 ^ i62);
                        int i64 = ~(i53 | i);
                        int i65 = (i63 - (~((((i61 & i64) | (i61 ^ i64)) | (~(i | 79))) * (-1444)))) - 1;
                        int i66 = ~(i58 | 79);
                        int i67 = (i54 & 87) + (i54 | 87);
                        read = i67 % 128;
                        if (i67 % 2 == 0) {
                            int i68 = (~(i53 | (-80))) | i66;
                            i3 = -Color.blue(1);
                            z = true;
                            i5 = i65 / ((i68 ^ 722) + ((i68 & 722) << 1));
                            i4 = 4;
                        } else {
                            int i69 = ~((i53 & (-80)) | ((-80) ^ i53));
                            int i70 = -(-(((i69 & i66) | (i66 ^ i69)) * 722));
                            int i71 = (i65 & i70) + (i65 | i70);
                            i3 = -Color.blue(0);
                            i4 = 2;
                            z = false;
                            i5 = i71;
                        }
                        int i72 = 51 * i3;
                        int i73 = i4 * (-49);
                        int i74 = (i72 & i73) + (i72 | i73);
                        int i75 = (i3 | i) * (-50);
                        int i76 = (i74 & i75) + (i75 | i74);
                        int i77 = (~i3) | (~i4);
                        int i78 = ~((i77 & i) | (i77 ^ i));
                        int i79 = read;
                        int i80 = ((i79 | 67) << 1) - (i79 ^ 67);
                        asBinder = i80 % 128;
                        int i81 = i80 % 2;
                        int i82 = ~i4;
                        int i83 = (i82 ^ i24) | (i82 & i24);
                        int i84 = -(-(50 * (i78 | (~((i83 & i3) | (i83 ^ i3))))));
                        int i85 = (i76 & i84) + (i84 | i76);
                        int i86 = ~((i82 ^ i49) | (i82 & i49));
                        int i87 = ~(i82 | i3);
                        int i88 = (i85 - (~(-(-(((~((i3 & i24) | (i24 ^ i3))) | ((i87 & i86) | (i86 ^ i87))) * 50))))) - 1;
                        int i89 = -Gravity.getAbsoluteGravity(0, 0);
                        Object[] objArr9 = new Object[1];
                        c(i5, z, i88, (i89 ^ 218) + ((i89 & 218) << 1), new char[]{' ', 18, 65518, 65512, 0, 65534, 65495, 65530, 65512, 65516, 25, 15, 29, 26, 20, 15, 65495, 65518, 65529, 65512, 65516, 25, 15, 29, 26, 20, 15, 65483, 65519, 16, '\r'}, objArr9);
                        String str2 = (String) objArr9[0];
                        int i90 = asBinder;
                        int i91 = (i90 & 75) + (i90 | 75);
                        read = i91 % 128;
                        int i92 = i91 % 2;
                        int i93 = i90 + 101;
                        read = i93 % 128;
                        int i94 = i93 % 2;
                        try {
                            Object[] objArr10 = new Object[1];
                            b(new byte[]{1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 1, 1, 1}, new int[]{0, 38, 89, 0}, false, objArr10);
                            objArr5[1] = Class.forName((String) objArr10[0]).getDeclaredConstructor(String.class).newInstance(str2);
                            try {
                                int i95 = 22 - (~(ViewConfiguration.getMaximumFlingVelocity() >> 16));
                                int modifierMetaStateMask = 10 - ((byte) KeyEvent.getModifierMetaStateMask());
                                int i96 = -(Process.myPid() >> 22);
                                int i97 = (i96 * 319) - 74178;
                                int i98 = ~i96;
                                int i99 = ~((i98 & i) | (i98 ^ i));
                                int i100 = -(-(((i99 & (-235)) | ((-235) ^ i99)) * (-318)));
                                int i101 = ((i97 | i100) << 1) - (i97 ^ i100);
                                int i102 = ~(((-235) ^ i) | ((-235) & i));
                                int i103 = (i49 ^ i96) | (i49 & i96);
                                int i104 = ~((i103 ^ 234) | (i103 & 234));
                                int i105 = ((i104 & i102) | (i102 ^ i104)) * 318;
                                int i106 = (i101 ^ i105) + ((i105 & i101) << 1);
                                int i107 = ((-235) ^ i24) | ((-235) & i24);
                                int i108 = ~((i107 & i96) | (i107 ^ i96));
                                int i109 = i96 | 234;
                                int i110 = ~((i109 & i) | (i109 ^ i));
                                int i111 = ((i110 & i108) | (i108 ^ i110)) * 318;
                                int i112 = read;
                                int i113 = ((i112 | 75) << 1) - (i112 ^ 75);
                                asBinder = i113 % 128;
                                if (i113 % 2 != 0) {
                                    int i114 = i106 << i111;
                                    Object[] objArr11 = new Object[1];
                                    c(i95, true, modifierMetaStateMask, i114, new char[]{'\t', '\n', 65534, 65481, 65535, 4, '\n', '\r', 65535, '\t', 65532, 15, 19, 0, 15, '\t', '\n', 65502, 65481, 15, '\t', 0, 15}, objArr11);
                                    cls = Class.forName((String) objArr11[0]);
                                    int i115 = -(-View.MeasureSpec.getMode(0));
                                    i6 = (i115 ^ 100) + ((i115 & 100) << 1);
                                    i7 = -(ViewConfiguration.getZoomControlsTimeout() > 1L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 1L ? 0 : -1));
                                    i8 = 18;
                                } else {
                                    Object[] objArr12 = new Object[1];
                                    c(i95, true, modifierMetaStateMask, i106 + i111, new char[]{'\t', '\n', 65534, 65481, 65535, 4, '\n', '\r', 65535, '\t', 65532, 15, 19, 0, 15, '\t', '\n', 65502, 65481, 15, '\t', 0, 15}, objArr12);
                                    cls = Class.forName((String) objArr12[0]);
                                    int i116 = -View.MeasureSpec.getMode(0);
                                    i6 = ((i116 | 17) << 1) - (i116 ^ 17);
                                    i7 = -(ViewConfiguration.getZoomControlsTimeout() > 0L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 0L ? 0 : -1));
                                    i8 = 14;
                                }
                                int i117 = i6;
                                int i118 = 628 * i7;
                                int i119 = -(-(i8 * 628));
                                int i120 = ((i118 | i119) << 1) - (i118 ^ i119);
                                int i121 = (i8 ^ i) | (i8 & i);
                                int i122 = ~i7;
                                int i123 = -(-(((i121 ^ i122) | (i121 & i122)) * (-627)));
                                int i124 = ((i120 | i123) << 1) - (i120 ^ i123);
                                int i125 = ~i8;
                                int i126 = -(-(((~((i125 ^ i) | (i125 & i))) | i7) * (-627)));
                                int i127 = (i124 & i126) + (i126 | i124);
                                int i128 = ~((i49 ^ i8) | (i8 & i49));
                                int i129 = ~((i7 & i) | (i7 ^ i));
                                int i130 = ((i129 & i128) | (i128 ^ i129)) * 627;
                                int i131 = (i127 ^ i130) + ((i127 & i130) << 1);
                                int i132 = -(ViewConfiguration.getScrollBarSize() >> 8);
                                int i133 = (i132 * 784) - 182206;
                                int i134 = ((i133 | 183222) << 1) - (i133 ^ 183222);
                                int i135 = ~i132;
                                int i136 = (i135 & i49) | (i135 ^ i49);
                                int i137 = (~((i136 & 233) | (i136 ^ 233))) * (-783);
                                int i138 = ((i134 | i137) << 1) - (i137 ^ i134);
                                int i139 = ~i132;
                                int i140 = ~(i24 | 233);
                                int i141 = ((i139 & i140) | (i139 ^ i140)) * 783;
                                Object[] objArr13 = new Object[1];
                                c(i117, false, i131, ((i138 | i141) << 1) - (i141 ^ i138), new char[]{65533, 65535, 7, 65533, 3, 1, 65513, 65533, '\n', 65533, 3, 1, 14, 3, 1, 16, 65516}, objArr13);
                                Object objInvoke2 = cls.getMethod((String) objArr13[0], null).invoke(context, null);
                                try {
                                    int iLastIndexOf = TextUtils.lastIndexOf("", '0', 0, 0);
                                    int i142 = (iLastIndexOf * (-661)) - 15864;
                                    int i143 = ~iLastIndexOf;
                                    int i144 = ~((i143 & (-25)) | (i143 ^ (-25)));
                                    int i145 = ((i144 & i49) | (i49 ^ i144)) * 1324;
                                    int i146 = ((i142 | i145) << 1) - (i142 ^ i145);
                                    int i147 = asBinder + 95;
                                    read = i147 % 128;
                                    if (i147 % 2 == 0) {
                                        int i148 = ~((iLastIndexOf ^ i) | (iLastIndexOf & i));
                                        int i149 = ~((i ^ 24) | (i & 24));
                                        i9 = i146 * ((-1324) % ((i148 ^ i149) | (i149 & i148)));
                                    } else {
                                        int i150 = ~((iLastIndexOf ^ i) | (iLastIndexOf & i));
                                        int i151 = ~((i ^ 24) | (i & 24));
                                        int i152 = -(-(((i150 ^ i151) | (i150 & i151)) * (-1324)));
                                        i9 = ((i146 | i152) << 1) - (i152 ^ i146);
                                    }
                                    int i153 = ~iLastIndexOf;
                                    int i154 = ~((i153 & 24) | (i153 ^ 24));
                                    int i155 = ~(iLastIndexOf | (-25));
                                    int i156 = 662 * ((i154 & i155) | (i154 ^ i155));
                                    int iGreen = 11 - Color.green(0);
                                    int i157 = -TextUtils.getOffsetAfter("", 0);
                                    Object[] objArr14 = new Object[1];
                                    c((i9 & i156) + (i156 | i9), true, iGreen, (i157 & 234) + (i157 | 234), new char[]{'\t', '\n', 65534, 65481, 65535, 4, '\n', '\r', 65535, '\t', 65532, 15, 19, 0, 15, '\t', '\n', 65502, 65481, 15, '\t', 0, 15}, objArr14);
                                    Class<?> cls4 = Class.forName((String) objArr14[0]);
                                    Object[] objArr15 = new Object[1];
                                    b(new byte[]{1, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 0, 1, 0}, new int[]{38, 14, 0, 10}, false, objArr15);
                                    String str3 = (String) objArr15[0];
                                    int i158 = asBinder + 75;
                                    read = i158 % 128;
                                    if (i158 % 2 == 0) {
                                        objInvoke = cls4.getMethod(str3, null).invoke(context, null);
                                        i10 = 23;
                                    } else {
                                        objInvoke = cls4.getMethod(str3, null).invoke(context, null);
                                        i10 = 64;
                                    }
                                    int i159 = read;
                                    int i160 = (i159 ^ 37) + ((i159 & 37) << 1);
                                    asBinder = i160 % 128;
                                    int i161 = i160 % 2;
                                    try {
                                        Object[] objArr16 = {objInvoke, Integer.valueOf(i10)};
                                        Object[] objArr17 = new Object[1];
                                        b(new byte[]{1, 1, 0, 0, 1, 0, 1, 0, 1, 0, 1, 0, 1, 1, 0, 0, 0, 1, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 1}, new int[]{52, 33, 0, 0}, false, objArr17);
                                        Class<?> cls5 = Class.forName((String) objArr17[0]);
                                        Object[] objArr18 = new Object[1];
                                        b(new byte[]{1, 1, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0}, new int[]{85, 14, 0, 0}, true, objArr18);
                                        String str4 = (String) objArr18[0];
                                        Class<?>[] clsArr = new Class[2];
                                        clsArr[0] = String.class;
                                        Class<?> cls6 = Integer.TYPE;
                                        int i162 = read;
                                        int i163 = (i162 & 63) + (i162 | 63);
                                        asBinder = i163 % 128;
                                        int i164 = i163 % 2;
                                        clsArr[1] = cls6;
                                        Object objInvoke3 = cls5.getMethod(str4, clsArr).invoke(objInvoke2, objArr16);
                                        int i165 = -ExpandableListView.getPackedPositionType(0L);
                                        int i166 = i165 * (-109);
                                        int i167 = (i166 ^ 3330) + ((i166 & 3330) << 1);
                                        int i168 = ~i165;
                                        int i169 = ~((i ^ 30) | (i & 30));
                                        int i170 = (i168 | i169) * (-220);
                                        int i171 = (((i167 & i170) + (i170 | i167)) - (~(-(-(((~((i165 ^ 30) | (i165 & 30))) | i169) * 220))))) - 1;
                                        int i172 = ~((~i165) | 30);
                                        int i173 = ~((i165 & (-31)) | ((-31) ^ i165));
                                        int i174 = i171 + (((i173 & i172) | (i172 ^ i173)) * 110);
                                        int pressedStateDuration = ViewConfiguration.getPressedStateDuration();
                                        int i175 = asBinder;
                                        int i176 = i175 + 47;
                                        read = i176 % 128;
                                        int i177 = i176 % 2;
                                        int i178 = -(pressedStateDuration >> 16);
                                        int i179 = i178 * (-958);
                                        int i180 = (i179 ^ (-9580)) + ((i179 & (-9580)) << 1);
                                        int i181 = ~(((-11) & i49) | ((-11) ^ i49));
                                        int i182 = ~i178;
                                        int i183 = i181 | (~(i182 | i));
                                        int i184 = ~(i49 | i178);
                                        int i185 = -(-(((i183 & i184) | (i183 ^ i184)) * 959));
                                        int i186 = (i180 & i185) + (i185 | i180);
                                        int i187 = -(-((~((i178 ^ 10) | (i178 & 10))) * (-959)));
                                        int i188 = ((i186 | i187) << 1) - (i187 ^ i186);
                                        int i189 = ~((i182 ^ i49) | (i182 & i49));
                                        int i190 = ~((-11) | i);
                                        int i191 = (i189 & i190) | (i189 ^ i190);
                                        int i192 = i175 + 39;
                                        read = i192 % 128;
                                        int i193 = i192 % 2;
                                        int i194 = ~((i178 & i) | (i178 ^ i));
                                        int i195 = i188 + (959 * ((i194 & i191) | (i191 ^ i194)));
                                        int i196 = -(-(KeyEvent.getMaxKeyCode() >> 16));
                                        Object[] objArr19 = new Object[1];
                                        c(i174, true, i195, ((i196 | 230) << 1) - (i196 ^ 230), new char[]{14, 2, 65485, 3, '\b', 14, 17, 3, '\r', 0, 14, 5, '\r', 65512, 4, 6, 0, '\n', 2, 0, 65519, 65485, '\f', 15, 65485, 19, '\r', 4, 19, '\r'}, objArr19);
                                        Class<?> cls7 = Class.forName((String) objArr19[0]);
                                        int i197 = -ExpandableListView.getPackedPositionType(0L);
                                        int i198 = (i197 & 10) + (i197 | 10);
                                        int i199 = -TextUtils.indexOf("", "", 0, 0);
                                        int i200 = i199 * 491;
                                        int i201 = ((i200 | (-1467)) << 1) - (i200 ^ (-1467));
                                        int i202 = ~i199;
                                        int i203 = ((i202 & (-4)) | (i202 ^ (-4)) | i49) * (-490);
                                        int i204 = (i201 ^ i203) + ((i203 & i201) << 1);
                                        int i205 = ~(((-4) & i199) | ((-4) ^ i199));
                                        int i206 = asBinder;
                                        int i207 = (i206 & 85) + (i206 | 85);
                                        read = i207 % 128;
                                        int i208 = i207 % 2;
                                        int i209 = ~((-4) | i);
                                        int i210 = 490 * ((i205 & i209) | (i205 ^ i209));
                                        int i211 = (i204 ^ i210) + ((i210 & i204) << 1);
                                        int i212 = (~i199) * 490;
                                        int i213 = (i211 & i212) + (i212 | i211);
                                        int i214 = -KeyEvent.normalizeMetaState(0);
                                        Object[] objArr20 = new Object[1];
                                        c(i198, false, i213, (i214 ^ 242) + ((i214 & 242) << 1), new char[]{5, 65528, 6, 6, 65532, 65530, 1, 65524, 7, '\b'}, objArr20);
                                        Object[] objArr21 = (Object[]) cls7.getField((String) objArr20[0]).get(objInvoke3);
                                        int length = objArr21.length;
                                        int i215 = 0;
                                        while (i215 < length) {
                                            Object obj2 = objArr21[i215];
                                            int doubleTapTimeout = ViewConfiguration.getDoubleTapTimeout() >> 16;
                                            int i216 = ~doubleTapTimeout;
                                            int i217 = (i216 ^ (-6)) | (i216 & (-6));
                                            int i218 = (i24 ^ doubleTapTimeout) | (i24 & doubleTapTimeout);
                                            int i219 = (doubleTapTimeout * (-317)) + 1595 + (((~((i218 ^ 5) | (i218 & 5))) | (~((i217 ^ i) | (i217 & i)))) * (-318));
                                            int i220 = ~(((-6) & doubleTapTimeout) | ((-6) ^ doubleTapTimeout));
                                            int i221 = ~((doubleTapTimeout & i) | (doubleTapTimeout ^ i));
                                            int i222 = -(-(((i221 & i220) | (i220 ^ i221)) * (-318)));
                                            int i223 = (i219 ^ i222) + ((i222 & i219) << i15);
                                            int i224 = ~((i216 ^ i) | (i216 & i));
                                            int i225 = (i223 - (~(((i224 & (-6)) | ((-6) ^ i224)) * 318))) - 1;
                                            int touchSlop = ViewConfiguration.getTouchSlop() >> 8;
                                            int i226 = touchSlop * (-1529);
                                            int i227 = ((i226 | (-3820)) << i15) - (i226 ^ (-3820));
                                            int i228 = ~touchSlop;
                                            int i229 = (i228 ^ (-6)) | (i228 & (-6));
                                            int i230 = ~((i229 ^ i49) | (i229 & i49));
                                            int i231 = ~touchSlop;
                                            int i232 = (i231 ^ 5) | (i231 & 5);
                                            int i233 = ~((i232 ^ i) | (i232 & i));
                                            int i234 = (i230 ^ i233) | (i233 & i230);
                                            int i235 = ((-6) ^ touchSlop) | ((-6) & touchSlop);
                                            int i236 = ~((i235 ^ i) | (i235 & i));
                                            int i237 = i227 + (((i234 ^ i236) | (i234 & i236)) * 765);
                                            int i238 = ~((i231 ^ (-6)) | (i231 & (-6)));
                                            int i239 = ~(i231 | i24);
                                            int i240 = -(-(((i238 & i239) | (i238 ^ i239)) * 1530));
                                            int i241 = ~((i228 & i) | (i228 ^ i));
                                            int i242 = ~(touchSlop | ((-6) ^ i49) | ((-6) & i49));
                                            int i243 = (((i237 ^ i240) + ((i240 & i237) << 1)) - (~(-(-(((i242 & i241) | (i241 ^ i242)) * 765))))) - 1;
                                            int maximumDrawingCacheSize = ViewConfiguration.getMaximumDrawingCacheSize() >> 24;
                                            int i244 = maximumDrawingCacheSize * 592;
                                            int i245 = (i244 ^ (-112690)) + ((i244 & (-112690)) << 1);
                                            int i246 = ~maximumDrawingCacheSize;
                                            int i247 = (~(i246 | 191)) * (-1182);
                                            int i248 = (i245 ^ i247) + ((i247 & i245) << 1);
                                            int i249 = (i246 ^ (-192)) | (i246 & (-192));
                                            int i250 = ~((i249 & i49) | (i249 ^ i49));
                                            int i251 = ~((maximumDrawingCacheSize & 191) | (maximumDrawingCacheSize ^ 191));
                                            int i252 = ((i250 & i251) | (i250 ^ i251)) * (-591);
                                            int i253 = ((i248 | i252) << 1) - (i252 ^ i248);
                                            int i254 = i | i246;
                                            int i255 = -(-(((i254 & (-192)) | (i254 ^ (-192))) * 591));
                                            Object[] objArr22 = new Object[1];
                                            c(i225, true, i243, ((i253 | i255) << 1) - (i255 ^ i253), new char[]{65535, 65526, 65531, 65524, 30}, objArr22);
                                            try {
                                                Object[] objArr23 = {(String) objArr22[0]};
                                                int iAxisFromString = MotionEvent.axisFromString("");
                                                int i256 = 30 - (~(-(-(ViewConfiguration.getWindowTouchSlop() >> 8))));
                                                int iRgb = Color.rgb(0, 0, 0);
                                                Object[] objArr24 = new Object[1];
                                                c((iAxisFromString ^ 38) + ((iAxisFromString & 38) << 1), true, i256, (iRgb & 16777449) + (16777449 | iRgb), new char[]{65506, 1, 16, 65533, 65535, 5, 2, 5, 16, 14, 1, 65503, 65482, 16, 14, 1, 65535, 65482, 21, 16, 5, 14, 17, 65535, 1, 15, 65482, 65533, 18, 65533, 6, 21, 14, 11, 16, 65535, 65533}, objArr24);
                                                Class<?> cls8 = Class.forName((String) objArr24[0]);
                                                int i257 = -Drawable.resolveOpacity(0, 0);
                                                int i258 = (i257 * 989) - 10857;
                                                int i259 = (-12) | i49;
                                                int i260 = ~((i259 ^ i257) | (i259 & i257));
                                                int i261 = (i257 ^ 11) | (i257 & 11);
                                                int i262 = (i260 | (~((i261 ^ i) | (i261 & i)))) * 988;
                                                int i263 = (((i258 ^ i262) + ((i262 & i258) << 1)) - (~(-(-((i257 | (-12)) * (-988)))))) - 1;
                                                int i264 = (~((~i257) | (-12))) | (~(((-12) ^ i) | ((-12) & i)));
                                                int i265 = ~((i257 & i24) | (i24 ^ i257) | 11);
                                                int i266 = i263 + (((i265 & i264) | (i264 ^ i265)) * 988);
                                                int iBlue = Color.blue(0);
                                                int i267 = (iBlue * 303) - 1505;
                                                int i268 = ~iBlue;
                                                int i269 = (i268 & i49) | (i268 ^ i49);
                                                int i270 = ~((i269 & 5) | (i269 ^ 5));
                                                int i271 = ~((iBlue ^ 5) | (iBlue & 5) | i);
                                                int i272 = -(-(((i270 & i271) | (i270 ^ i271)) * (-302)));
                                                int i273 = (i267 & i272) + (i267 | i272);
                                                int i274 = ~iBlue;
                                                int i275 = (i274 & 5) | (i274 ^ 5);
                                                int i276 = -(-((~((i275 & i) | (i275 ^ i))) * (-604)));
                                                int i277 = (i273 & i276) + (i276 | i273);
                                                int i278 = ~(((-6) & iBlue) | ((-6) ^ iBlue));
                                                int i279 = ~((i ^ 5) | (i & 5));
                                                int i280 = i277 + (((i278 & i279) | (i278 ^ i279)) * 302);
                                                int i281 = -Color.alpha(0);
                                                Object[] objArr25 = new Object[1];
                                                c(i266, true, i280, (i281 ^ 236) + ((i281 & 236) << 1), new char[]{7, 65506, '\r', 65534, 0, 65534, 65532, 7, 65530, '\r', '\f'}, objArr25);
                                                Object objInvoke4 = cls8.getMethod((String) objArr25[0], String.class).invoke(null, objArr23);
                                                try {
                                                    int minimumFlingVelocity = ViewConfiguration.getMinimumFlingVelocity() >> 16;
                                                    int i282 = minimumFlingVelocity * 522;
                                                    int i283 = asBinder + 79;
                                                    read = i283 % 128;
                                                    int i284 = i283 % 2;
                                                    int i285 = ((i282 | (-14560)) << 1) - (i282 ^ (-14560));
                                                    int i286 = ~((i49 ^ 28) | (i49 & 28));
                                                    int i287 = (i285 - (~(-(-(((i286 & minimumFlingVelocity) | (minimumFlingVelocity ^ i286)) * (-1042)))))) - 1;
                                                    int i288 = ((28 ^ i) | (28 & i)) * 521;
                                                    int i289 = (i287 ^ i288) + ((i287 & i288) << 1);
                                                    int i290 = ~minimumFlingVelocity;
                                                    int i291 = ~((i290 & (-29)) | (i290 ^ (-29)));
                                                    int i292 = ~minimumFlingVelocity;
                                                    int i293 = (minimumFlingVelocity & i24) | (i24 ^ minimumFlingVelocity);
                                                    int i294 = i289 + (((~((i293 & 28) | (i293 ^ 28))) | i291 | (~((i292 & i) | (i292 ^ i)))) * 521);
                                                    int i295 = -(-TextUtils.getTrimmedLength(""));
                                                    int i296 = (i295 & 11) + (i295 | 11);
                                                    char mirror = AndroidCharacter.getMirror('0');
                                                    int i297 = mirror * '3';
                                                    int i298 = ((((i297 | (-9065)) << 1) - (i297 ^ (-9065))) - (~(((mirror ^ i) | (mirror & i)) * (-50)))) - 1;
                                                    int i299 = (~mirror) | (-186);
                                                    int i300 = asBinder;
                                                    int i301 = ((i300 | 93) << 1) - (i300 ^ 93);
                                                    int i302 = i301 % 128;
                                                    read = i302;
                                                    if (i301 % 2 == 0) {
                                                        int i303 = ~(i299 | i);
                                                        int i304 = (-186) | i49;
                                                        int i305 = ~((i304 ^ mirror) | (i304 & mirror));
                                                        i11 = i298 % (50 / ((i303 ^ i305) | (i303 & i305)));
                                                    } else {
                                                        int i306 = ((-186) ^ i49) | ((-186) & i49);
                                                        i11 = (i298 - (~(-(-(((~((i299 & i) | (i299 ^ i))) | (~((i306 ^ mirror) | (i306 & mirror)))) * 50))))) - 1;
                                                    }
                                                    int i307 = (i302 & 15) + (i302 | 15);
                                                    asBinder = i307 % 128;
                                                    if (i307 % 2 != 0) {
                                                        int i308 = ~(((-186) ^ i49) | ((-186) & i49));
                                                        int i309 = ~((65350 ^ mirror) | (65350 & mirror));
                                                        Object[] objArr26 = new Object[1];
                                                        c(i294, true, i296, i11 % (50 / ((~(mirror | i24)) | ((i308 ^ i309) | (i308 & i309)))), new char[]{'\n', 11, 65535, 65482, 0, 5, 11, 14, 0, '\n', 65533, 1, 14, 17, 16, 65533, '\n', 3, 5, 65519, 65482, '\t', '\f', 65482, 16, '\n', 1, 16}, objArr26);
                                                        obj = objArr26[0];
                                                    } else {
                                                        int i310 = ~i;
                                                        int i311 = ~(((-186) ^ i310) | (i310 & (-186)));
                                                        int i312 = ~((65350 ^ mirror) | (65350 & mirror));
                                                        int i313 = (i311 ^ i312) | (i311 & i312);
                                                        int i314 = ~(mirror | i49);
                                                        Object[] objArr27 = new Object[1];
                                                        c(i294, true, i296, (i11 - (~(50 * ((i314 & i313) | (i313 ^ i314))))) - 1, new char[]{'\n', 11, 65535, 65482, 0, 5, 11, 14, 0, '\n', 65533, 1, 14, 17, 16, 65533, '\n', 3, 5, 65519, 65482, '\t', '\f', 65482, 16, '\n', 1, 16}, objArr27);
                                                        obj = objArr27[0];
                                                    }
                                                    Class<?> cls9 = Class.forName((String) obj);
                                                    Object[] objArr28 = new Object[1];
                                                    b(new byte[]{1, 0, 1, 0, 1, 0, 1, 1, 1, 1, 1}, new int[]{99, 11, 0, 0}, true, objArr28);
                                                    try {
                                                        Object[] objArr29 = {new ByteArrayInputStream((byte[]) cls9.getMethod((String) objArr28[0], null).invoke(obj2, null))};
                                                        int i315 = -(ExpandableListView.getPackedPositionForGroup(0) > 0L ? 1 : (ExpandableListView.getPackedPositionForGroup(0) == 0L ? 0 : -1));
                                                        int i316 = read;
                                                        int i317 = (i316 & 13) + (i316 | 13);
                                                        asBinder = i317 % 128;
                                                        int i318 = i317 % 2;
                                                        int i319 = i315 * 881;
                                                        int i320 = ((i319 | 32597) << 1) - (i319 ^ 32597);
                                                        int i321 = ~i315;
                                                        int i322 = ~(i321 | (-38));
                                                        int i323 = ~((i321 ^ i) | (i321 & i));
                                                        int i324 = -(-(((i322 & i323) | (i322 ^ i323) | (~(((-38) & i) | ((-38) ^ i)))) * (-880)));
                                                        int i325 = (i320 & i324) + (i320 | i324);
                                                        int i326 = ~((i321 & i24) | (i321 ^ i24));
                                                        int i327 = (i326 & 37) | (i326 ^ 37);
                                                        int i328 = ~(i315 | i);
                                                        Object[] objArr30 = new Object[1];
                                                        c(i325 + (((i327 & i328) | (i327 ^ i328)) * (-880)) + ((~((i315 & i) | (i315 ^ i))) * 880), true, 31 - (CdmaCellLocation.convertQuartSecToDecDegrees(0) > 0.0d ? 1 : (CdmaCellLocation.convertQuartSecToDecDegrees(0) == 0.0d ? 0 : -1)), (ViewConfiguration.getTapTimeout() >> 16) + 233, new char[]{65506, 1, 16, 65533, 65535, 5, 2, 5, 16, 14, 1, 65503, 65482, 16, 14, 1, 65535, 65482, 21, 16, 5, 14, 17, 65535, 1, 15, 65482, 65533, 18, 65533, 6, 21, 14, 11, 16, 65535, 65533}, objArr30);
                                                        Class<?> cls10 = Class.forName((String) objArr30[0]);
                                                        Object[] objArr31 = new Object[1];
                                                        b(new byte[]{1, 1, 1, 0, 0, 1, 1, 1, 0, 1, 0, 0, 1, 1, 1, 1, 1, 1, 0}, new int[]{110, 19, 0, 0}, true, objArr31);
                                                        Object objInvoke5 = cls10.getMethod((String) objArr31[0], InputStream.class).invoke(objInvoke4, objArr29);
                                                        int length2 = objArr5.length;
                                                        int i329 = 0;
                                                        while (i329 < 2) {
                                                            int i330 = asBinder;
                                                            int i331 = (i330 ^ 99) + ((i330 & 99) << 1);
                                                            int i332 = i331 % 128;
                                                            read = i332;
                                                            if (i331 % 2 == 0) {
                                                                Object obj3 = objArr5[i329];
                                                                Object obj4 = null;
                                                                obj4.hashCode();
                                                                throw null;
                                                            }
                                                            Object obj5 = objArr5[i329];
                                                            int i333 = (i332 ^ 13) + ((i332 & 13) << 1);
                                                            asBinder = i333 % 128;
                                                            if (i333 % 2 != 0) {
                                                                try {
                                                                    Object[] objArr32 = new Object[1];
                                                                    b(new byte[]{1, 1, 1, 0, 0, 1, 1, 1, 0, 1, 0, 0, 1, 1, 1, 0, 0, 0, 1, 0, 1, 1, 1, 1, 1, 1, 0, 0, 0, 1, 1, 1, 1, 1}, new int[]{129, 34, 0, 0}, false, objArr32);
                                                                    cls2 = Class.forName((String) objArr32[0]);
                                                                    iIndexOf = TextUtils.indexOf("", "", 0);
                                                                    i12 = 36;
                                                                } catch (Throwable th) {
                                                                    Throwable cause = th.getCause();
                                                                    if (cause != null) {
                                                                        throw cause;
                                                                    }
                                                                    throw th;
                                                                }
                                                            } else {
                                                                Object[] objArr33 = new Object[1];
                                                                b(new byte[]{1, 1, 1, 0, 0, 1, 1, 1, 0, 1, 0, 0, 1, 1, 1, 0, 0, 0, 1, 0, 1, 1, 1, 1, 1, 1, 0, 0, 0, 1, 1, 1, 1, 1}, new int[]{129, 34, 0, 0}, true, objArr33);
                                                                cls2 = Class.forName((String) objArr33[0]);
                                                                iIndexOf = TextUtils.indexOf("", "", 0);
                                                                i12 = 23;
                                                            }
                                                            int i334 = -iIndexOf;
                                                            int i335 = ((i334 * (-711)) - (~(-(-(i12 * 713))))) - 1;
                                                            int i336 = ~i12;
                                                            Object[] objArr34 = objArr21;
                                                            int i337 = ~((i336 ^ i334) | (i336 & i334));
                                                            int i338 = length;
                                                            int i339 = (i24 ^ i334) | (i24 & i334);
                                                            int i340 = i24;
                                                            int i341 = ~i339;
                                                            int i342 = ((i337 ^ i341) | (i337 & i341)) * (-712);
                                                            int i343 = (i335 & i342) + (i342 | i335);
                                                            int i344 = (i336 ^ i49) | (i336 & i49);
                                                            int i345 = (i344 & i334) | (i344 ^ i334);
                                                            int i346 = asBinder;
                                                            int i347 = ((i346 | 3) << 1) - (i346 ^ 3);
                                                            int i348 = i215;
                                                            read = i347 % 128;
                                                            if (i347 % 2 == 0) {
                                                                int i349 = ~i345;
                                                                int i350 = ~(i334 | i12 | i);
                                                                i13 = i343 >>> ((-712) / ((i349 & i350) | (i349 ^ i350)));
                                                            } else {
                                                                int i351 = (i334 & i12) | (i334 ^ i12);
                                                                i13 = (i343 - (~(((~i345) | (~((i351 & i) | (i351 ^ i)))) * (-712)))) - 1;
                                                            }
                                                            int i352 = ~i339;
                                                            int i353 = -(-(712 * ((i352 & i336) | (i336 ^ i352))));
                                                            int i354 = (i13 ^ i353) + ((i13 & i353) << 1);
                                                            int i355 = -TextUtils.indexOf("", "");
                                                            int i356 = (i355 ^ 8) + ((i355 & 8) << 1);
                                                            int i357 = -(CdmaCellLocation.convertQuartSecToDecDegrees(0) > 0.0d ? 1 : (CdmaCellLocation.convertQuartSecToDecDegrees(0) == 0.0d ? 0 : -1));
                                                            Object[] objArr35 = new Object[1];
                                                            c(i354, true, i356, (i357 & 228) + (i357 | 228), new char[]{6, 11, 3, 22, 65524, 21, 6, '\b', '\r', 2, 17, '\n', 4, 15, '\n', 19, 65521, 65489, 65489, 65494, 65529, 21, 4}, objArr35);
                                                            if (obj5.equals(cls2.getMethod((String) objArr35[0], null).invoke(objInvoke5, null))) {
                                                                int i358 = asBinder;
                                                                int i359 = (i358 & 41) + (i358 | 41);
                                                                read = i359 % 128;
                                                                int i360 = i359 % 2;
                                                                Object[] objArr36 = {new int[]{i}, new int[]{i ^ 1}, null, new int[1]};
                                                                try {
                                                                    Object[] objArr37 = {Integer.valueOf(i2), 16, Integer.valueOf(((((~((-850133009) | i49)) | (~(939308159 | i))) * 988) - 1003969408) + (((~((-854336638) | i)) | 4203629 | (~(i49 | 939308159))) * 988))};
                                                                    Object method2 = onCameraWillChange.PlaybackStateCompat.get(-554193431);
                                                                    if (method2 == null) {
                                                                        Class cls11 = (Class) onCameraWillChange.read((char) View.MeasureSpec.makeMeasureSpec(0, 0), 1714 - TextUtils.lastIndexOf("", '0', 0), 24 - (ViewConfiguration.getFadingEdgeLength() >> 16));
                                                                        byte b3 = (byte) 0;
                                                                        byte b4 = b3;
                                                                        Object[] objArr38 = new Object[1];
                                                                        a(b3, b4, b4, objArr38);
                                                                        method2 = cls11.getMethod((String) objArr38[0], Integer.TYPE, Integer.TYPE, Integer.TYPE);
                                                                        onCameraWillChange.PlaybackStateCompat.put(-554193431, method2);
                                                                    }
                                                                    ((int[]) objArr36[3])[0] = ((Integer) ((Method) method2).invoke(null, objArr37)).intValue();
                                                                    return objArr36;
                                                                } catch (Throwable th2) {
                                                                    Throwable cause2 = th2.getCause();
                                                                    if (cause2 != null) {
                                                                        throw cause2;
                                                                    }
                                                                    throw th2;
                                                                }
                                                            }
                                                            i329 = (i329 ^ 1) + ((i329 & 1) << 1);
                                                            objArr21 = objArr34;
                                                            i24 = i340;
                                                            i215 = i348;
                                                            length = i338;
                                                        }
                                                        i215++;
                                                        i15 = 1;
                                                    } catch (Throwable th3) {
                                                        Throwable cause3 = th3.getCause();
                                                        if (cause3 != null) {
                                                            throw cause3;
                                                        }
                                                        throw th3;
                                                    }
                                                } catch (Throwable th4) {
                                                    Throwable cause4 = th4.getCause();
                                                    if (cause4 != null) {
                                                        throw cause4;
                                                    }
                                                    throw th4;
                                                }
                                            } catch (Throwable th5) {
                                                Throwable cause5 = th5.getCause();
                                                if (cause5 != null) {
                                                    throw cause5;
                                                }
                                                throw th5;
                                            }
                                        }
                                        int i361 = read;
                                        int i362 = (i361 & 95) + (i361 | 95);
                                        asBinder = i362 % 128;
                                        int i363 = i362 % 2;
                                    } catch (Throwable th6) {
                                        Throwable cause6 = th6.getCause();
                                        if (cause6 != null) {
                                            throw cause6;
                                        }
                                        throw th6;
                                    }
                                } catch (Throwable th7) {
                                    Throwable cause7 = th7.getCause();
                                    if (cause7 != null) {
                                        throw cause7;
                                    }
                                    throw th7;
                                }
                            } catch (Throwable th8) {
                                Throwable cause8 = th8.getCause();
                                if (cause8 != null) {
                                    throw cause8;
                                }
                                throw th8;
                            }
                        } catch (Throwable th9) {
                            Throwable cause9 = th9.getCause();
                            if (cause9 != null) {
                                throw cause9;
                            }
                            throw th9;
                        }
                    } catch (Throwable th10) {
                        Throwable cause10 = th10.getCause();
                        if (cause10 != null) {
                            throw cause10;
                        }
                        throw th10;
                    }
                } catch (Throwable unused) {
                }
                Object[] objArr39 = {new int[]{i}, new int[]{i}, null, new int[1]};
                Object[] objArr40 = {Integer.valueOf(i2), 0, Integer.valueOf(((92251052 + (((~((-63140229) | i)) | 4284672) * 1504)) + ((~(i | (-58855557))) * (-1504))) - 1297918656)};
                Object method3 = onCameraWillChange.PlaybackStateCompat.get(-554193431);
                if (method3 == null) {
                    Class cls12 = (Class) onCameraWillChange.read((char) ((-1) - Process.getGidForName("")), 1715 - ((Process.getThreadPriority(0) + 20) >> 6), ((Process.getThreadPriority(0) + 20) >> 6) + 24);
                    byte b5 = (byte) 0;
                    byte b6 = b5;
                    Object[] objArr41 = new Object[1];
                    a(b5, b6, b6, objArr41);
                    method3 = cls12.getMethod((String) objArr41[0], Integer.TYPE, Integer.TYPE, Integer.TYPE);
                    onCameraWillChange.PlaybackStateCompat.put(-554193431, method3);
                }
                ((int[]) objArr39[3])[0] = ((Integer) ((Method) method3).invoke(null, objArr40)).intValue();
                int i364 = asBinder + 69;
                read = i364 % 128;
                if (i364 % 2 != 0) {
                    return objArr39;
                }
                Object obj6 = null;
                obj6.hashCode();
                throw null;
            } catch (Throwable th11) {
                Throwable cause11 = th11.getCause();
                if (cause11 != null) {
                    throw cause11;
                }
                throw th11;
            }
        }
    };
    public static Map<String, Object> AudioAttributesImplBaseParcelizer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.31
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAvailableVoucherListPromotions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.31.2
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PromotionId", "request:promotionId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaBrowserCompatMediaItem = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.34
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAvailablePosterPromotions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.34.2
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PromotionId", "request:promotionId:required");
                }
            });
        }
    };
    public static Map<String, Object> ParcelableVolumeInfo = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.36
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetInventoryCount");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.36.1
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("PromotionId", "request:inventoryPromotionId:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaBrowserCompatSearchResultReceiver = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.37
        private static short[] read;
        private static final byte[] $$d = {59, 105, 26, 44};
        private static final int $$e = 134;
        private static int $10 = 0;
        private static int $11 = 1;
        private static final byte[] $$a = {20, 1, -5, 63, -23, 44, -44, -10, 5, -6, -18, 8, -1, -8, -23, 37, -42, -11, 10, -18, 7, 0, -7, -7, -4, 21, -35, MqttWireMessage.MESSAGE_TYPE_PINGREQ, -18, -10, MqttWireMessage.MESSAGE_TYPE_PINGRESP, -7, -22, 0, -8, 2};
        private static final int $$b = 245;
        private static int IconCompatParcelizer = 0;
        private static int AudioAttributesImplApi21Parcelizer = 1;
        private static int asInterface = 1727380884;
        private static int RemoteActionCompatParcelizer = 1831610329;
        private static int asBinder = -1378996406;
        private static byte[] onTransact = {MqttWireMessage.MESSAGE_TYPE_DISCONNECT, 26, -9, 17, -32, 27, -54, -19, 92, -32, -23, 17, -32, 27, -22, -51, 44, 31, 28, 21, -24, 16, -27, 19, -107, -54, -127, -21, -49, -92, -47, -77, -52, -56, -55, -50, -94, -1, -39, -97, -52, 3, 0, 115, 44, 86, 122, MqttWireMessage.MESSAGE_TYPE_PINGRESP, 124, 30, 117, 113, 116, 119, MqttWireMessage.MESSAGE_TYPE_UNSUBACK, 42, 30, 72, 116, -55, -79, MqttWireMessage.MESSAGE_TYPE_PINGRESP, 0, 120, MqttWireMessage.MESSAGE_TYPE_PINGRESP, 122, 7, 60, 65, 118, 113, 116, 5, 125, 4, 28, 45, 59, -124, 59, 5, 71, 56, -81, -65, -18, -9, -66, -12, 70, -31, 67, -9, -123, -81, -65, -67, -12, -125, 121, -23, -71, -5, -2, -80, 77, -19, -118, 20, -127, -76, -87, -124, -82, -4, -97, -123, -87, 64, -53, -123, 32};

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAvailableProductsPromotions");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.37.5
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PromotionId", "request:promotionId:required");
                    put("FilterCriteriaType", "request:filterCriteriaType:required");
                    put("FilterCriteriaValue", "request:filterCriteriaValue:required");
                }
            });
        }

        private static void a(int i, int i2, byte b, short s, int i3, Object[] objArr) throws Throwable {
            char c;
            int i4 = 2 % 2;
            addOnWillStartRenderingMapListener addonwillstartrenderingmaplistener = new addOnWillStartRenderingMapListener();
            StringBuilder sb = new StringBuilder();
            try {
                Object[] objArr2 = {Integer.valueOf(i), Integer.valueOf(RemoteActionCompatParcelizer)};
                Object method = onCameraWillChange.PlaybackStateCompat.get(-30937109);
                int i5 = -1;
                if (method == null) {
                    Class cls = (Class) onCameraWillChange.read((char) ((SystemClock.currentThreadTimeMillis() > (-1L) ? 1 : (SystemClock.currentThreadTimeMillis() == (-1L) ? 0 : -1)) - 1), 543 - (ViewConfiguration.getScrollBarFadeDuration() >> 16), 35 - (ViewConfiguration.getDoubleTapTimeout() >> 16));
                    byte b2 = (byte) (-1);
                    byte b3 = (byte) (b2 + 1);
                    Object[] objArr3 = new Object[1];
                    c(b2, b3, b3, objArr3);
                    method = cls.getMethod((String) objArr3[0], Integer.TYPE, Integer.TYPE);
                    onCameraWillChange.PlaybackStateCompat.put(-30937109, method);
                }
                int iIntValue = ((Integer) ((Method) method).invoke(null, objArr2)).intValue();
                boolean z = iIntValue == -1;
                if (z) {
                    byte[] bArr = onTransact;
                    if (bArr != null) {
                        int length = bArr.length;
                        byte[] bArr2 = new byte[length];
                        int i6 = 0;
                        while (i6 < length) {
                            try {
                                Object[] objArr4 = {Integer.valueOf(bArr[i6])};
                                Object method2 = onCameraWillChange.PlaybackStateCompat.get(-1076195355);
                                if (method2 == null) {
                                    Class cls2 = (Class) onCameraWillChange.read((char) (58401 - KeyEvent.keyCodeFromString("")), (ViewConfiguration.getKeyRepeatDelay() >> 16) + 1371, (ViewConfiguration.getDoubleTapTimeout() >> 16) + 19);
                                    byte b4 = (byte) i5;
                                    byte b5 = (byte) (b4 + 1);
                                    Object[] objArr5 = new Object[1];
                                    c(b4, b5, (byte) (b5 + 1), objArr5);
                                    method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE);
                                    onCameraWillChange.PlaybackStateCompat.put(-1076195355, method2);
                                }
                                bArr2[i6] = ((Byte) ((Method) method2).invoke(null, objArr4)).byteValue();
                                i6++;
                                i5 = -1;
                            } catch (Throwable th) {
                                Throwable cause = th.getCause();
                                if (cause == null) {
                                    throw th;
                                }
                                throw cause;
                            }
                        }
                        bArr = bArr2;
                    }
                    if (bArr != null) {
                        byte[] bArr3 = onTransact;
                        Object[] objArr6 = {Integer.valueOf(i3), Integer.valueOf(asInterface)};
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(-30937109);
                        if (method3 == null) {
                            Class cls3 = (Class) onCameraWillChange.read((char) KeyEvent.normalizeMetaState(0), (CdmaCellLocation.convertQuartSecToDecDegrees(0) > 0.0d ? 1 : (CdmaCellLocation.convertQuartSecToDecDegrees(0) == 0.0d ? 0 : -1)) + 543, TextUtils.getOffsetBefore("", 0) + 35);
                            byte b6 = (byte) (-1);
                            byte b7 = (byte) (b6 + 1);
                            Object[] objArr7 = new Object[1];
                            c(b6, b7, b7, objArr7);
                            method3 = cls3.getMethod((String) objArr7[0], Integer.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-30937109, method3);
                        }
                        iIntValue = (byte) (((byte) (bArr3[((Integer) ((Method) method3).invoke(null, objArr6)).intValue()] ^ 3885398344606689213L)) + ((int) (RemoteActionCompatParcelizer ^ 3885398344606689213L)));
                    } else {
                        iIntValue = (short) (((short) (read[i3 + ((int) (asInterface ^ 3885398344606689213L))] ^ 3885398344606689213L)) + ((int) (RemoteActionCompatParcelizer ^ 3885398344606689213L)));
                    }
                }
                if (iIntValue > 0) {
                    addonwillstartrenderingmaplistener.asBinder = ((i3 + iIntValue) - 2) + ((int) (asInterface ^ 3885398344606689213L)) + (!z ? 0 : 1);
                    Object[] objArr8 = {addonwillstartrenderingmaplistener, Integer.valueOf(i2), Integer.valueOf(asBinder), sb};
                    Object method4 = onCameraWillChange.PlaybackStateCompat.get(-1912037534);
                    if (method4 == null) {
                        method4 = ((Class) onCameraWillChange.read((char) KeyEvent.normalizeMetaState(0), 2390 - (TypedValue.complexToFloat(0) > 0.0f ? 1 : (TypedValue.complexToFloat(0) == 0.0f ? 0 : -1)), (ViewConfiguration.getKeyRepeatDelay() >> 16) + 21)).getMethod("j", Object.class, Integer.TYPE, Integer.TYPE, Object.class);
                        onCameraWillChange.PlaybackStateCompat.put(-1912037534, method4);
                    }
                    ((StringBuilder) ((Method) method4).invoke(null, objArr8)).append(addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer);
                    addonwillstartrenderingmaplistener.onTransact = addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer;
                    byte[] bArr4 = onTransact;
                    if (bArr4 != null) {
                        int length2 = bArr4.length;
                        byte[] bArr5 = new byte[length2];
                        for (int i7 = 0; i7 < length2; i7++) {
                            bArr5[i7] = (byte) (bArr4[i7] ^ 3885398344606689213L);
                        }
                        bArr4 = bArr5;
                    }
                    boolean z2 = bArr4 != null;
                    addonwillstartrenderingmaplistener.read = 1;
                    while (addonwillstartrenderingmaplistener.read < iIntValue) {
                        int i8 = $11;
                        int i9 = i8 + 73;
                        $10 = i9 % 128;
                        if (i9 % 2 != 0) {
                            Object obj = null;
                            obj.hashCode();
                            throw null;
                        }
                        if (z2) {
                            int i10 = i8 + 91;
                            $10 = i10 % 128;
                            if (i10 % 2 != 0) {
                                byte[] bArr6 = onTransact;
                                addonwillstartrenderingmaplistener.asBinder = addonwillstartrenderingmaplistener.asBinder + 1;
                                c = (char) (addonwillstartrenderingmaplistener.onTransact >>> (((byte) (((byte) (bArr6[r7] * 3885398344606689213L)) >> s)) ^ b));
                            } else {
                                byte[] bArr7 = onTransact;
                                addonwillstartrenderingmaplistener.asBinder = addonwillstartrenderingmaplistener.asBinder - 1;
                                c = (char) (addonwillstartrenderingmaplistener.onTransact + (((byte) (((byte) (bArr7[r7] ^ 3885398344606689213L)) + s)) ^ b));
                            }
                            addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer = c;
                        } else {
                            short[] sArr = read;
                            addonwillstartrenderingmaplistener.asBinder = addonwillstartrenderingmaplistener.asBinder - 1;
                            addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer = (char) (addonwillstartrenderingmaplistener.onTransact + (((short) (((short) (sArr[r7] ^ 3885398344606689213L)) + s)) ^ b));
                        }
                        sb.append(addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer);
                        addonwillstartrenderingmaplistener.onTransact = addonwillstartrenderingmaplistener.RemoteActionCompatParcelizer;
                        addonwillstartrenderingmaplistener.read++;
                    }
                }
                String string = sb.toString();
                int i11 = $10 + 53;
                $11 = i11 % 128;
                int i12 = i11 % 2;
                objArr[0] = string;
            } catch (Throwable th2) {
                Throwable cause2 = th2.getCause();
                if (cause2 == null) {
                    throw th2;
                }
                throw cause2;
            }
        }

        /*  JADX ERROR: NoSuchElementException in pass: ReplaceNewArray
            java.util.NoSuchElementException
                at java.base/java.util.TreeMap.key(TreeMap.java:1637)
                at java.base/java.util.TreeMap.lastKey(TreeMap.java:309)
                at jadx.core.dex.visitors.ReplaceNewArray.processNewArray(ReplaceNewArray.java:171)
                at jadx.core.dex.visitors.ReplaceNewArray.processInsn(ReplaceNewArray.java:72)
                at jadx.core.dex.visitors.ReplaceNewArray.visit(ReplaceNewArray.java:53)
            */
        public static java.lang.Object[] asBinder(android.content.Context r33, int r34, int r35) {
            /*
                Method dump skipped, instructions count: 3823
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass37.asBinder(android.content.Context, int, int):java.lang.Object[]");
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0023  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001b  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0023 -> B:11:0x0028). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void b(short r7, byte r8, int r9, java.lang.Object[] r10) {
            /*
                int r8 = 11 - r8
                int r9 = 34 - r9
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass37.$$a
                int r7 = 114 - r7
                byte[] r1 = new byte[r8]
                r2 = 0
                if (r0 != 0) goto L10
                r3 = r9
                r4 = r2
                goto L28
            L10:
                r3 = r2
                r6 = r9
                r9 = r7
                r7 = r6
            L14:
                int r4 = r3 + 1
                byte r5 = (byte) r9
                r1[r3] = r5
                if (r4 != r8) goto L23
                java.lang.String r7 = new java.lang.String
                r7.<init>(r1, r2)
                r10[r2] = r7
                return
            L23:
                r3 = r0[r7]
                r6 = r3
                r3 = r7
                r7 = r6
            L28:
                int r7 = -r7
                int r9 = r9 + r7
                int r9 = r9 + (-5)
                int r7 = r3 + 1
                r3 = r4
                goto L14
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass37.b(short, byte, int, java.lang.Object[]):void");
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0023  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001b  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0023 -> B:11:0x002d). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void c(short r6, short r7, int r8, java.lang.Object[] r9) {
            /*
                int r6 = r6 + 4
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass37.$$d
                int r8 = 100 - r8
                int r7 = r7 * 3
                int r1 = r7 + 1
                byte[] r1 = new byte[r1]
                r2 = 0
                if (r0 != 0) goto L12
                r3 = r6
                r4 = r2
                goto L2d
            L12:
                r3 = r2
                r5 = r8
                r8 = r6
                r6 = r5
            L16:
                byte r4 = (byte) r6
                r1[r3] = r4
                if (r3 != r7) goto L23
                java.lang.String r6 = new java.lang.String
                r6.<init>(r1, r2)
                r9[r2] = r6
                return
            L23:
                int r3 = r3 + 1
                int r8 = r8 + 1
                r4 = r0[r8]
                r5 = r3
                r3 = r8
                r8 = r4
                r4 = r5
            L2d:
                int r8 = -r8
                int r6 = r6 + r8
                r8 = r3
                r3 = r4
                goto L16
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass37.c(short, short, int, java.lang.Object[]):void");
        }
    };
    public static Map<String, Object> create = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.38
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayDayFilter");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.38.5
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                }
            });
        }
    };
    public static Map<String, Object> setProgress = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.39
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/GetSupportingDatas");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.39.2
                {
                    put("Authorization", "user:authorization:required");
                    put("Type", "request:type:required");
                }
            });
        }
    };
    public static Map<String, Object> IconCompatParcelizer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.40
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAllCategory");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.40.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
        }
    };
    public static Map<String, Object> setNegativeButton = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.41
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetProductDetail");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.41.2
                {
                    put("Authorization", "user:authorization:required");
                    put("ProductId", "request:productId:required");
                }
            });
        }
    };
    public static Map<String, Object> setStackedBackground = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.44
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/RedeemPlayerOffer");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.44.2
                {
                    put("Authorization", "user:authorization:required");
                    put("IsCustomQuantity", "request:isCustomQuantity");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.44.5
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("OfferId", "request:offerId:required");
                    put("Quantity", "request:quantity:required");
                }
            });
        }
    };
    public static Map<String, Object> setSplitBackground = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.45
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/RedeemPlayerPointRedemption");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.45.2
                {
                    put("Authorization", "user:authorization:required");
                    put("IsCustomQuantity", "request:isCustomQuantity");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.45.5
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PointRedemptionId", "request:offerId:required");
                    put("Quantity", "request:quantity:required");
                    put("PIN", "request:pin:required");
                }
            });
        }
    };
    public static Map<String, Object> setPrimaryBackground = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.43
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/RedeemProduct");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.43.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.43.1
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("ProductID", "request:productId:required");
                }
            });
        }
    };
    public static Map<String, Object> setLogo = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.47
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/TurbojetGetVoyageList");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.47.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.47.3
                {
                    put("route", "request:route:required");
                    put("departure_date_time", "request:departureDateTime:required");
                    put("seat_class", "request:seatClass:required");
                    put("no_of_ticket", "request:noOfTicket:required");
                }
            });
        }
    };
    public static Map<String, Object> setMenuPrepared = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.50
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/TurbojetGetBookingAll");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.50.1
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.50.2
                {
                    put("flight_date_time", "request:flightDateTime:required");
                    put("route", "request:route:required");
                    put("seat_class", "request:seatClass:required");
                    put("collector", "request:collector:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PIN", "request:pin");
                    put("Quantity", "request:quantity:required");
                    put("PointRedemptionOrOfferId", "request:offerId:required");
                    put("VesselClass", "request:vesselClass");
                    put("Source", "request:source:required");
                }
            });
        }
    };
    public static Map<String, Object> ComponentActivity4 = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.48
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayerNotificationList");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.48.3
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                }
            });
        }
    };
    public static Map<String, Object> ComponentActivity2 = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.46
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPEPInfo");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.46.4
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                }
            });
        }
    };
    public static Map<String, Object> setHasDecor = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.49
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayerTransactionHistory");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.49.5
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> Keep = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.53
        private static final byte[] $$d = {7, -116, 69, -58};
        private static final int $$e = 35;
        private static int $10 = 0;
        private static int $11 = 1;
        private static final byte[] $$a = {84, -23, 65, -114, -23, 44, -44, -10, 5, -6, -18};
        private static final int $$b = 96;
        private static int asInterface = 0;
        private static int onTransact = 1;
        private static int[] RemoteActionCompatParcelizer = {47574095, -1390638109, 569802084, 1368679477, 1335706630, 1886870596, 679895026, 276884574, -1483965132, -1321469208, 730505703, 470082264, 1850878971, -1826518195, -1419549148, -1687587059, -30724318, -1630594070};
        private static char[] asBinder = {61879, 35394, 1593, 33373, 7802, 39496, 5718, 37459, 11869, 43560, 9828, 41496, 15921, 47630, 13841, 45595, 20056, 51907, 18105, 49885, 24314, 56008, 22230, 53971, 28381, 60072, 26344, 58015, 32489, 64185, 30391, 33149, 64251, 30363, 62085, 28402, 60073, 26323, 58039, 24208, 56034, 22268, 54009, 20215, 51906, 18050, 49909, 16112, 47739, 13839, 45624, 11834, 43540, 9729, 41503, 7706, 39462, 5706, 37491, 3708, 35411, 1609, 51468, 45819, 16121, 47863, 9954, 41692, 11993, 43659, 5838, 37562, 7859, 39601, 1704, 33435, 3721, 35531, 30382, 62074, 32371, 64113, 26216, 57933, 28233, 46973, 52359, 16542, 50338, 22683, 56481, 20641, 54451, 26813, 60615, 24807, 58579, 30932, 64739, 28909, 62711, 2280, 33113, 64163, 30394, 62086, 28351, 60037, 26245, 58007, 24217, 56035, 22208, 54007, 20211, 51907, 42608, 56711, 20869, 54667, 18846, 52640, 16805, 50679, 31154, 64966, 29135, 62925, 27092, 60903, 25077, 58807, 6625, 40196, 4431, 38185, 2320, 36138, 298, 34104, 14646, 48460, 12648, 46423, 10583, 44390, 33126, 64232, 30459, 62182, 28391, 21685, 12111, 41814, 10089, 47943, 16232, 45928, 14207, 35697, 3870, 33594, 1871, 39746, 8058, 37650, 5928, 60219, 28612, 58305, 26579, 64450, 32747, 62446};
        private static long read = 5793057566916278982L;

        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayerTierMaintenanceCondition");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.53.4
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                }
            });
        }

        private static void a(int i, int[] iArr, Object[] objArr) throws Throwable {
            int[] iArr2;
            int i2;
            int i3 = 2 % 2;
            addOnWillStartRenderingFrameListener addonwillstartrenderingframelistener = new addOnWillStartRenderingFrameListener();
            char[] cArr = new char[4];
            char[] cArr2 = new char[iArr.length * 2];
            int[] iArr3 = RemoteActionCompatParcelizer;
            int i4 = 56768;
            int i5 = -375379530;
            int i6 = 1;
            int i7 = 0;
            if (iArr3 != null) {
                int i8 = $11 + 101;
                $10 = i8 % 128;
                int i9 = i8 % 2;
                int length = iArr3.length;
                int[] iArr4 = new int[length];
                int i10 = 0;
                while (i10 < length) {
                    try {
                        Object[] objArr2 = new Object[1];
                        objArr2[i7] = Integer.valueOf(iArr3[i10]);
                        Object method = onCameraWillChange.PlaybackStateCompat.get(Integer.valueOf(i5));
                        if (method == null) {
                            Class cls = (Class) onCameraWillChange.read((char) (i4 - (PointF.length(0.0f, 0.0f) > 0.0f ? 1 : (PointF.length(0.0f, 0.0f) == 0.0f ? 0 : -1))), 910 - ImageFormat.getBitsPerPixel(i7), 39 - TextUtils.getOffsetAfter("", i7));
                            byte b = (byte) ($$e & 5);
                            byte b2 = (byte) (b - 1);
                            Object[] objArr3 = new Object[1];
                            d(b, b2, b2, objArr3);
                            method = cls.getMethod((String) objArr3[0], Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-375379530, method);
                        }
                        iArr4[i10] = ((Integer) ((Method) method).invoke(null, objArr2)).intValue();
                        i10++;
                        i4 = 56768;
                        i5 = -375379530;
                        i7 = 0;
                    } catch (Throwable th) {
                        Throwable cause = th.getCause();
                        if (cause == null) {
                            throw th;
                        }
                        throw cause;
                    }
                }
                iArr3 = iArr4;
            }
            int length2 = iArr3.length;
            int[] iArr5 = new int[length2];
            int[] iArr6 = RemoteActionCompatParcelizer;
            int i11 = 16;
            if (iArr6 != null) {
                int length3 = iArr6.length;
                int[] iArr7 = new int[length3];
                int i12 = 0;
                while (i12 < length3) {
                    Object[] objArr4 = new Object[i6];
                    objArr4[0] = Integer.valueOf(iArr6[i12]);
                    Object method2 = onCameraWillChange.PlaybackStateCompat.get(-375379530);
                    if (method2 != null) {
                        iArr2 = iArr6;
                        i2 = length3;
                    } else {
                        Class cls2 = (Class) onCameraWillChange.read((char) (56768 - (KeyEvent.getMaxKeyCode() >> i11)), (Process.myPid() >> 22) + 911, (ViewConfiguration.getMinimumFlingVelocity() >> 16) + 39);
                        byte b3 = (byte) ($$e & 5);
                        byte b4 = (byte) (b3 - 1);
                        iArr2 = iArr6;
                        i2 = length3;
                        Object[] objArr5 = new Object[1];
                        d(b3, b4, b4, objArr5);
                        method2 = cls2.getMethod((String) objArr5[0], Integer.TYPE);
                        onCameraWillChange.PlaybackStateCompat.put(-375379530, method2);
                    }
                    iArr7[i12] = ((Integer) ((Method) method2).invoke(null, objArr4)).intValue();
                    i12++;
                    int i13 = $11 + 113;
                    $10 = i13 % 128;
                    int i14 = i13 % 2;
                    iArr6 = iArr2;
                    length3 = i2;
                    i11 = 16;
                    i6 = 1;
                }
                iArr6 = iArr7;
            }
            char c = 0;
            System.arraycopy(iArr6, 0, iArr5, 0, length2);
            addonwillstartrenderingframelistener.read = 0;
            while (addonwillstartrenderingframelistener.read < iArr.length) {
                cArr[c] = (char) (iArr[addonwillstartrenderingframelistener.read] >> 16);
                cArr[1] = (char) iArr[addonwillstartrenderingframelistener.read];
                cArr[2] = (char) (iArr[addonwillstartrenderingframelistener.read + 1] >> 16);
                cArr[3] = (char) iArr[addonwillstartrenderingframelistener.read + 1];
                addonwillstartrenderingframelistener.RemoteActionCompatParcelizer = (cArr[0] << 16) + cArr[1];
                addonwillstartrenderingframelistener.onTransact = (cArr[2] << 16) + cArr[3];
                addOnWillStartRenderingFrameListener.read(iArr5);
                int i15 = 0;
                for (int i16 = 16; i15 < i16; i16 = 16) {
                    int i17 = $11 + 93;
                    $10 = i17 % 128;
                    if (i17 % 2 != 0) {
                        addonwillstartrenderingframelistener.RemoteActionCompatParcelizer ^= iArr5[i15];
                        Object[] objArr6 = {addonwillstartrenderingframelistener, Integer.valueOf(addOnWillStartRenderingFrameListener.RemoteActionCompatParcelizer(addonwillstartrenderingframelistener.RemoteActionCompatParcelizer)), addonwillstartrenderingframelistener, addonwillstartrenderingframelistener};
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(-1594259774);
                        if (method3 == null) {
                            Class cls3 = (Class) onCameraWillChange.read((char) Color.blue(0), 578 - Gravity.getAbsoluteGravity(0, 0), 40 - (SystemClock.uptimeMillis() > 0L ? 1 : (SystemClock.uptimeMillis() == 0L ? 0 : -1)));
                            byte b5 = (byte) 0;
                            byte b6 = b5;
                            Object[] objArr7 = new Object[1];
                            d(b5, b6, b6, objArr7);
                            method3 = cls3.getMethod((String) objArr7[0], Object.class, Integer.TYPE, Object.class, Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(-1594259774, method3);
                        }
                        int iIntValue = ((Integer) ((Method) method3).invoke(null, objArr6)).intValue();
                        addonwillstartrenderingframelistener.RemoteActionCompatParcelizer = addonwillstartrenderingframelistener.onTransact;
                        addonwillstartrenderingframelistener.onTransact = iIntValue;
                        i15 += 2;
                    } else {
                        addonwillstartrenderingframelistener.RemoteActionCompatParcelizer ^= iArr5[i15];
                        Object[] objArr8 = {addonwillstartrenderingframelistener, Integer.valueOf(addOnWillStartRenderingFrameListener.RemoteActionCompatParcelizer(addonwillstartrenderingframelistener.RemoteActionCompatParcelizer)), addonwillstartrenderingframelistener, addonwillstartrenderingframelistener};
                        Object method4 = onCameraWillChange.PlaybackStateCompat.get(-1594259774);
                        if (method4 == null) {
                            Class cls4 = (Class) onCameraWillChange.read((char) TextUtils.getOffsetAfter("", 0), 577 - ((byte) KeyEvent.getModifierMetaStateMask()), 40 - (ViewConfiguration.getZoomControlsTimeout() > 0L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 0L ? 0 : -1)));
                            byte b7 = (byte) 0;
                            byte b8 = b7;
                            Object[] objArr9 = new Object[1];
                            d(b7, b8, b8, objArr9);
                            method4 = cls4.getMethod((String) objArr9[0], Object.class, Integer.TYPE, Object.class, Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(-1594259774, method4);
                        }
                        int iIntValue2 = ((Integer) ((Method) method4).invoke(null, objArr8)).intValue();
                        addonwillstartrenderingframelistener.RemoteActionCompatParcelizer = addonwillstartrenderingframelistener.onTransact;
                        addonwillstartrenderingframelistener.onTransact = iIntValue2;
                        i15++;
                    }
                }
                int i18 = addonwillstartrenderingframelistener.RemoteActionCompatParcelizer;
                addonwillstartrenderingframelistener.RemoteActionCompatParcelizer = addonwillstartrenderingframelistener.onTransact;
                addonwillstartrenderingframelistener.onTransact = i18;
                addonwillstartrenderingframelistener.onTransact ^= iArr5[16];
                addonwillstartrenderingframelistener.RemoteActionCompatParcelizer ^= iArr5[17];
                int i19 = addonwillstartrenderingframelistener.RemoteActionCompatParcelizer;
                int i20 = addonwillstartrenderingframelistener.onTransact;
                cArr[0] = (char) (addonwillstartrenderingframelistener.RemoteActionCompatParcelizer >>> 16);
                cArr[1] = (char) addonwillstartrenderingframelistener.RemoteActionCompatParcelizer;
                cArr[2] = (char) (addonwillstartrenderingframelistener.onTransact >>> 16);
                cArr[3] = (char) addonwillstartrenderingframelistener.onTransact;
                addOnWillStartRenderingFrameListener.read(iArr5);
                cArr2[addonwillstartrenderingframelistener.read * 2] = cArr[0];
                cArr2[(addonwillstartrenderingframelistener.read * 2) + 1] = cArr[1];
                cArr2[(addonwillstartrenderingframelistener.read * 2) + 2] = cArr[2];
                cArr2[(addonwillstartrenderingframelistener.read * 2) + 3] = cArr[3];
                Object[] objArr10 = {addonwillstartrenderingframelistener, addonwillstartrenderingframelistener};
                Object method5 = onCameraWillChange.PlaybackStateCompat.get(1291649188);
                if (method5 == null) {
                    Class cls5 = (Class) onCameraWillChange.read((char) (ViewConfiguration.getWindowTouchSlop() >> 8), TextUtils.indexOf((CharSequence) "", '0', 0, 0) + 1652, 21 - (Process.getElapsedCpuTime() > 0L ? 1 : (Process.getElapsedCpuTime() == 0L ? 0 : -1)));
                    byte b9 = (byte) ($$e & 15);
                    byte b10 = (byte) (b9 - 3);
                    Object[] objArr11 = new Object[1];
                    d(b9, b10, b10, objArr11);
                    method5 = cls5.getMethod((String) objArr11[0], Object.class, Object.class);
                    onCameraWillChange.PlaybackStateCompat.put(1291649188, method5);
                }
                ((Method) method5).invoke(null, objArr10);
                c = 0;
            }
            objArr[0] = new String(cArr2, 0, i);
        }

        private static void b(char c, int i, int i2, Object[] objArr) throws Throwable {
            int i3 = 2;
            int i4 = 2 % 2;
            addOnSourceChangedListener addonsourcechangedlistener = new addOnSourceChangedListener();
            long[] jArr = new long[i2];
            int i5 = 0;
            addonsourcechangedlistener.asBinder = 0;
            int i6 = $10 + 99;
            $11 = i6 % 128;
            int i7 = i6 % 2;
            while (addonsourcechangedlistener.asBinder < i2) {
                int i8 = $11 + 1;
                $10 = i8 % 128;
                if (i8 % i3 != 0) {
                    int i9 = addonsourcechangedlistener.asBinder;
                    try {
                        Object[] objArr2 = new Object[1];
                        objArr2[i5] = Integer.valueOf(asBinder[i / addonsourcechangedlistener.asBinder]);
                        Object method = onCameraWillChange.PlaybackStateCompat.get(-876601150);
                        if (method == null) {
                            Class cls = (Class) onCameraWillChange.read((char) (ExpandableListView.getPackedPositionChild(0L) + 58527), 231 - (ViewConfiguration.getZoomControlsTimeout() > 0L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 0L ? 0 : -1)), 25 - Color.blue(i5));
                            byte b = (byte) i5;
                            Object[] objArr3 = new Object[1];
                            d((byte) ($$e + i3), b, b, objArr3);
                            String str = (String) objArr3[i5];
                            Class<?>[] clsArr = new Class[1];
                            clsArr[i5] = Integer.TYPE;
                            method = cls.getMethod(str, clsArr);
                            onCameraWillChange.PlaybackStateCompat.put(-876601150, method);
                        }
                        Object[] objArr4 = {Long.valueOf(((Long) ((Method) method).invoke(null, objArr2)).longValue()), Long.valueOf(addonsourcechangedlistener.asBinder), Long.valueOf(read), Integer.valueOf(c)};
                        Object method2 = onCameraWillChange.PlaybackStateCompat.get(-454823659);
                        if (method2 == null) {
                            Class cls2 = (Class) onCameraWillChange.read((char) (3825 - (KeyEvent.getMaxKeyCode() >> 16)), TextUtils.lastIndexOf("", '0', 0) + 951, Process.getGidForName("") + 49);
                            byte b2 = (byte) 0;
                            Object[] objArr5 = new Object[1];
                            d((byte) ($$e + 1), b2, b2, objArr5);
                            method2 = cls2.getMethod((String) objArr5[0], Long.TYPE, Long.TYPE, Long.TYPE, Integer.TYPE);
                            onCameraWillChange.PlaybackStateCompat.put(-454823659, method2);
                        }
                        jArr[i9] = ((Long) ((Method) method2).invoke(null, objArr4)).longValue();
                        Object[] objArr6 = {addonsourcechangedlistener, addonsourcechangedlistener};
                        Object method3 = onCameraWillChange.PlaybackStateCompat.get(1685680622);
                        if (method3 == null) {
                            Class cls3 = (Class) onCameraWillChange.read((char) (ExpandableListView.getPackedPositionType(0L) + 21967), (ViewConfiguration.getKeyRepeatTimeout() >> 16) + 1210, (ViewConfiguration.getMaximumDrawingCacheSize() >> 24) + 16);
                            byte b3 = (byte) 0;
                            Object[] objArr7 = new Object[1];
                            d((byte) 42, b3, b3, objArr7);
                            method3 = cls3.getMethod((String) objArr7[0], Object.class, Object.class);
                            onCameraWillChange.PlaybackStateCompat.put(1685680622, method3);
                        }
                        ((Method) method3).invoke(null, objArr6);
                    } catch (Throwable th) {
                        Throwable cause = th.getCause();
                        if (cause == null) {
                            throw th;
                        }
                        throw cause;
                    }
                } else {
                    int i10 = addonsourcechangedlistener.asBinder;
                    Object[] objArr8 = {Integer.valueOf(asBinder[i + addonsourcechangedlistener.asBinder])};
                    Object method4 = onCameraWillChange.PlaybackStateCompat.get(-876601150);
                    if (method4 == null) {
                        Class cls4 = (Class) onCameraWillChange.read((char) ((ViewConfiguration.getScrollFriction() > 0.0f ? 1 : (ViewConfiguration.getScrollFriction() == 0.0f ? 0 : -1)) + 58525), (ViewConfiguration.getMaximumDrawingCacheSize() >> 24) + 230, (SystemClock.uptimeMillis() > 0L ? 1 : (SystemClock.uptimeMillis() == 0L ? 0 : -1)) + 24);
                        byte b4 = (byte) 0;
                        Object[] objArr9 = new Object[1];
                        d((byte) ($$e + 2), b4, b4, objArr9);
                        method4 = cls4.getMethod((String) objArr9[0], Integer.TYPE);
                        onCameraWillChange.PlaybackStateCompat.put(-876601150, method4);
                    }
                    Object[] objArr10 = {Long.valueOf(((Long) ((Method) method4).invoke(null, objArr8)).longValue()), Long.valueOf(addonsourcechangedlistener.asBinder), Long.valueOf(read), Integer.valueOf(c)};
                    Object method5 = onCameraWillChange.PlaybackStateCompat.get(-454823659);
                    if (method5 == null) {
                        Class cls5 = (Class) onCameraWillChange.read((char) ((ViewConfiguration.getZoomControlsTimeout() > 0L ? 1 : (ViewConfiguration.getZoomControlsTimeout() == 0L ? 0 : -1)) + 3824), Color.rgb(0, 0, 0) + 16778166, 48 - (TypedValue.complexToFraction(0, 0.0f, 0.0f) > 0.0f ? 1 : (TypedValue.complexToFraction(0, 0.0f, 0.0f) == 0.0f ? 0 : -1)));
                        byte b5 = (byte) 0;
                        Object[] objArr11 = new Object[1];
                        d((byte) ($$e + 1), b5, b5, objArr11);
                        method5 = cls5.getMethod((String) objArr11[0], Long.TYPE, Long.TYPE, Long.TYPE, Integer.TYPE);
                        onCameraWillChange.PlaybackStateCompat.put(-454823659, method5);
                    }
                    jArr[i10] = ((Long) ((Method) method5).invoke(null, objArr10)).longValue();
                    Object[] objArr12 = {addonsourcechangedlistener, addonsourcechangedlistener};
                    Object method6 = onCameraWillChange.PlaybackStateCompat.get(1685680622);
                    if (method6 == null) {
                        Class cls6 = (Class) onCameraWillChange.read((char) (21967 - TextUtils.indexOf("", "", 0, 0)), 1210 - View.MeasureSpec.getMode(0), 16 - (ViewConfiguration.getDoubleTapTimeout() >> 16));
                        byte b6 = (byte) 0;
                        Object[] objArr13 = new Object[1];
                        d((byte) 42, b6, b6, objArr13);
                        method6 = cls6.getMethod((String) objArr13[0], Object.class, Object.class);
                        onCameraWillChange.PlaybackStateCompat.put(1685680622, method6);
                    }
                    ((Method) method6).invoke(null, objArr12);
                }
                i3 = 2;
                i5 = 0;
            }
            char[] cArr = new char[i2];
            addonsourcechangedlistener.asBinder = 0;
            int i11 = $11 + 113;
            $10 = i11 % 128;
            int i12 = i11 % 2;
            while (addonsourcechangedlistener.asBinder < i2) {
                cArr[addonsourcechangedlistener.asBinder] = (char) jArr[addonsourcechangedlistener.asBinder];
                Object[] objArr14 = {addonsourcechangedlistener, addonsourcechangedlistener};
                Object method7 = onCameraWillChange.PlaybackStateCompat.get(1685680622);
                if (method7 == null) {
                    Class cls7 = (Class) onCameraWillChange.read((char) (21968 - (SystemClock.elapsedRealtime() > 0L ? 1 : (SystemClock.elapsedRealtime() == 0L ? 0 : -1))), 1210 - (ViewConfiguration.getMinimumFlingVelocity() >> 16), (Process.myTid() >> 22) + 16);
                    byte b7 = (byte) 0;
                    Object[] objArr15 = new Object[1];
                    d((byte) 42, b7, b7, objArr15);
                    method7 = cls7.getMethod((String) objArr15[0], Object.class, Object.class);
                    onCameraWillChange.PlaybackStateCompat.put(1685680622, method7);
                }
                ((Method) method7).invoke(null, objArr14);
            }
            objArr[0] = new String(cArr);
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0028  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x0020  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0028 -> B:11:0x002a). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void c(int r5, int r6, short r7, java.lang.Object[] r8) {
            /*
                byte[] r0 = o.projectedMetersForLatLng.AnonymousClass53.$$a
                int r6 = r6 * 4
                int r6 = 97 - r6
                int r7 = r7 * 2
                int r7 = 4 - r7
                int r5 = r5 * 4
                int r1 = r5 + 8
                byte[] r1 = new byte[r1]
                int r5 = r5 + 7
                r2 = 0
                if (r0 != 0) goto L18
                r3 = r5
                r4 = r2
                goto L2a
            L18:
                r3 = r2
            L19:
                byte r4 = (byte) r6
                r1[r3] = r4
                int r4 = r3 + 1
                if (r3 != r5) goto L28
                java.lang.String r5 = new java.lang.String
                r5.<init>(r1, r2)
                r8[r2] = r5
                return
            L28:
                r3 = r0[r7]
            L2a:
                int r3 = -r3
                int r6 = r6 + r3
                int r6 = r6 + (-5)
                int r7 = r7 + 1
                r3 = r4
                goto L19
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass53.c(int, int, short, java.lang.Object[]):void");
        }

        /* JADX WARN: Removed duplicated region for block: B:10:0x0026  */
        /* JADX WARN: Removed duplicated region for block: B:8:0x001e  */
        /* JADX WARN: Unsupported multi-entry loop pattern (BACK_EDGE: B:10:0x0026 -> B:11:0x002d). Please report as a decompilation issue!!! */
        /*
            Code decompiled incorrectly, please refer to instructions dump.
            To view partially-correct add '--show-bad-code' argument
        */
        private static void d(int r6, short r7, byte r8, java.lang.Object[] r9) {
            /*
                int r7 = r7 * 4
                int r7 = 4 - r7
                int r6 = r6 + 66
                int r8 = r8 * 3
                int r0 = r8 + 1
                byte[] r1 = o.projectedMetersForLatLng.AnonymousClass53.$$d
                byte[] r0 = new byte[r0]
                r2 = 0
                if (r1 != 0) goto L15
                r6 = r7
                r4 = r8
                r3 = r2
                goto L2d
            L15:
                r3 = r2
            L16:
                r5 = r7
                r7 = r6
                r6 = r5
                byte r4 = (byte) r7
                r0[r3] = r4
                if (r3 != r8) goto L26
                java.lang.String r6 = new java.lang.String
                r6.<init>(r0, r2)
                r9[r2] = r6
                return
            L26:
                int r3 = r3 + 1
                r4 = r1[r6]
                r5 = r7
                r7 = r6
                r6 = r5
            L2d:
                int r7 = r7 + 1
                int r6 = r6 + r4
                goto L16
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass53.d(int, short, byte, java.lang.Object[]):void");
        }

        /*  JADX ERROR: NoSuchElementException in pass: ReplaceNewArray
            java.util.NoSuchElementException
                at java.base/java.util.TreeMap.key(TreeMap.java:1637)
                at java.base/java.util.TreeMap.lastKey(TreeMap.java:309)
                at jadx.core.dex.visitors.ReplaceNewArray.processNewArray(ReplaceNewArray.java:171)
                at jadx.core.dex.visitors.ReplaceNewArray.processInsn(ReplaceNewArray.java:72)
                at jadx.core.dex.visitors.ReplaceNewArray.visit(ReplaceNewArray.java:53)
            */
        public static java.lang.Object[] onTransact(android.content.Context r27, int r28, int r29) {
            /*
                Method dump skipped, instructions count: 4022
                To view this dump add '--comments-level debug' option
            */
            throw new UnsupportedOperationException("Method not decompiled: o.projectedMetersForLatLng.AnonymousClass53.onTransact(android.content.Context, int, int):java.lang.Object[]");
        }
    };
    public static Map<String, Object> ImmLeaksCleaner = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.51
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayerUsedTransactionHistory");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.51.5
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                    put("geofencing", "request:geofencing:required");
                    put("http_geofencing", "request:geofencing:required");
                }
            });
        }
    };
    public static Map<String, Object> setPadding = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.55
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/GetTurboJETTransactionHistory");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.55.5
                {
                    put("Authorization", "user:authorization:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("PlayerId", "user:playerId:required");
                    put("TicketID", "request:ticketId:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaSessionCompatQueueItem = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.52
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetHottestItems");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.52.2
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingDescription", "user:ranking:required");
                }
            });
        }
    };
    public static Map<String, Object> setChecked = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.54
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetRecommendComps");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.54.3
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("RankingDescription", "user:ranking:required");
                }
            });
        }
    };
    public static Map<String, Object> AudioAttributesImplApi21Parcelizer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.57
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetAllCategoryDetail");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.57.4
                {
                    put("Authorization", "user:authorization:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaDescriptionCompat = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.58
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetCategoryDetail");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.58.3
                {
                    put("Authorization", "user:authorization:required");
                    put("CategoryId", "request:categoryId:required");
                }
            });
        }
    };
    public static Map<String, Object> PlaybackStateCompat = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.60
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetMlifeBenefitInfo");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.60.3
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingNumber", "user:ranking");
                }
            });
        }
    };
    public static Map<String, Object> getContext = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.56
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPointEarnDetail");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.56.5
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                }
            });
        }
    };
    public static Map<String, Object> setWindowCallback = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.62
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/GetLatestVersion");
            put("method", "GET");
            put("background", Boolean.TRUE);
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.62.2
                {
                    put("Authorization", "user:authorization:required");
                }
            });
        }
    };
    public static Map<String, Object> AudioAttributesImplApi26Parcelizer = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.64
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/Delete");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.64.1
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                }
            });
        }
    };
    public static Map<String, Object> setPositiveButton = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.61
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Opera/GetPreCheckInPreference");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.61.5
                {
                    put("Authorization", "user:authorization:required");
                    put("RoomType", "request:roomType:required");
                    put("RankingNumber", "user:ranking:required");
                    put("PropertyId", "request:propertyId:required");
                }
            });
        }
    };
    public static Map<String, Object> OnBackPressedDispatcherLifecycleOnBackPressedCancellable = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.65
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Opera/GetPlayerRoomBookingInfo");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.65.2
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("RankingNumber", "user:ranking");
                }
            });
        }
    };
    public static Map<String, Object> setTitleOptional = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.63
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Opera/SavePreCheckInRecord");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.63.3
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.63.1
                {
                    put("PlayerId", "user:playerId:required");
                    put("EhostSessionId", "user:sessionId:required");
                    put("ConfirmationNo", "request:confirmationNo:required");
                    put("ArrivalTime", "request:arrivalTime:required");
                    put("Preferences", "request:preferences:required");
                    put("SpecialRequired", "request:specialRequired");
                    put("Salutation", "request:salutation");
                }
            });
        }
    };
    public static Map<String, Object> setContentView = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.68
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Limo/GetPlayerLimoBookingInfo");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.68.5
                {
                    put("Authorization", "user:authorization:required");
                    put("RankingNumber", "user:ranking");
                    put("PlayerId", "user:playerId:required");
                }
            });
        }
    };
    public static Map<String, Object> setVisibility = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.66
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/ReadNotificationMessage");
            put("method", "POST");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.66.5
                {
                    put("Authorization", "user:authorization:required");
                }
            });
            put("body", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.66.1
                {
                    put("CustomerID", "request:customerId:required");
                    put("MessageID", "request:messageId:required");
                }
            });
        }
    };
    public static Map<String, Object> MediaSessionCompatResultReceiverWrapper = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.70
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/InAllowedRegion");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.70.4
                {
                    put("X-DEVICE-ID", "user:mapDeviceId:required");
                }
            });
        }
    };
    public static Map<String, Object> ComponentActivity6 = new HashMap<String, Object>() { // from class: o.projectedMetersForLatLng.69
        {
            put("url", "https://mobileapp-non-gaming.mgm.mo/api/mlifeApp/v1.0/Patrons/GetPlayerEventCalendarList");
            put("method", "GET");
            put("header", new HashMap<String, String>() { // from class: o.projectedMetersForLatLng.69.3
                {
                    put("Authorization", "user:authorization:required");
                    put("PlayerId", "user:playerId:required");
                    put("RankingNumber", "user:ranking:required");
                    put("ShowOnOfferFlag", "request:ShowOnOfferFlag:required");
                    put("BeginDate", "request:BeginDate");
                    put("EndDate", "request:EndDate");
                }
            });
        }
    };
}
